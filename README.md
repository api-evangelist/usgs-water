# USGS Water Services (usgs-water)

The U.S. Geological Survey (USGS) National Water Information System (NWIS) exposes a suite of REST APIs providing access to real-time and historical water data from over 1.5 million monitoring locations across the United States and territories. The legacy WaterServices APIs (being decommissioned in early 2027) and the next-generation api.waterdata.usgs.gov OGC-compliant APIs together cover streamflow, groundwater levels, water quality, site metadata, and statistical summaries. All services are free, publicly funded, and require no authentication for standard use; API keys are available at no cost for higher rate-limit access.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/usgs-water/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/usgs-water/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Producer
- **Access:** Public

## Tags

- Water
- Streamflow
- Groundwater
- Water Quality
- Hydrology
- Environmental
- USGS
- NWIS
- Government
- Open Data
- OGC

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### USGS Instantaneous Values Service

Provides near real-time water data — streamflow, gage height, temperature, specific conductance, and hundreds of other parameters — from thousands of USGS monitoring sites. Values are typically recorded every 15 minutes and transmitted hourly. Data is available from October 1, 2007 onwards and is marked provisional until reviewed.

- **Human URL:** [https://waterservices.usgs.gov/docs/instantaneous-values/instantaneous-values-details/](https://waterservices.usgs.gov/docs/instantaneous-values/instantaneous-values-details/)
- **Base URL:** `https://waterservices.usgs.gov/nwis/iv/`

#### Tags

- Real-Time
- Streamflow
- Gage Height
- Water Parameters
- Time Series

#### Properties

- [Documentation](https://waterservices.usgs.gov/docs/instantaneous-values/instantaneous-values-details/)
- [Website](https://waterservices.usgs.gov/)

### USGS Daily Values Service

Returns historical summarized daily hydrologic data (mean, median, maximum, minimum) for streams, lakes, estuaries, and wells. Many sites have more than 10 years of record. Supports WaterML 1.1, WaterML 2.0, RDB (tab-delimited), and JSON output formats.

- **Human URL:** [https://waterservices.usgs.gov/docs/dv-service/daily-values-service-details/](https://waterservices.usgs.gov/docs/dv-service/daily-values-service-details/)
- **Base URL:** `https://waterservices.usgs.gov/nwis/dv/`

#### Tags

- Daily Values
- Historical Data
- Streamflow
- Hydrology
- WaterML

#### Properties

- [Documentation](https://waterservices.usgs.gov/docs/dv-service/daily-values-service-details/)
- [Website](https://waterservices.usgs.gov/)

### USGS Site Service

Searches and retrieves metadata for millions of USGS hydrologic data collection sites including streams, springs, wells, lakes, reservoirs, estuaries, and glaciers. Filtering options include site number, state, HUC, bounding box, county, site type, and parameter codes. Outputs include tab-delimited, KML, and GeoJSON.

- **Human URL:** [https://waterservices.usgs.gov/docs/site-service/site-service-details/](https://waterservices.usgs.gov/docs/site-service/site-service-details/)
- **Base URL:** `https://waterservices.usgs.gov/nwis/site/`

#### Tags

- Site Metadata
- Monitoring Locations
- Geospatial
- NWIS

#### Properties

- [Documentation](https://waterservices.usgs.gov/docs/site-service/site-service-details/)
- [Website](https://waterservices.usgs.gov/)

### USGS Statistics Service

Retrieves daily, monthly, or annual statistics (mean, minimum, maximum, median, and percentiles P05–P95) computed from approved historical time-series data. Supports up to 10 sites per request and returns data in RDB tab-delimited format.

- **Human URL:** [https://waterservices.usgs.gov/docs/statistics/statistics-details/](https://waterservices.usgs.gov/docs/statistics/statistics-details/)
- **Base URL:** `https://waterservices.usgs.gov/nwis/stats/`

#### Tags

- Statistics
- Percentiles
- Historical
- Streamflow
- Approved Data

#### Properties

- [Documentation](https://waterservices.usgs.gov/docs/statistics/statistics-details/)
- [Website](https://waterservices.usgs.gov/)

### USGS Groundwater Levels Service

Provides historical manually-recorded groundwater level measurements from USGS wells and monitoring sites. Returns depth-to-water and water-level-above-datum values in JSON or RDB format. For automated real-time groundwater data, the Instantaneous Values Service should be used.

- **Human URL:** [https://waterservices.usgs.gov/docs/groundwater-levels/groundwater-levels-details/](https://waterservices.usgs.gov/docs/groundwater-levels/groundwater-levels-details/)
- **Base URL:** `https://waterservices.usgs.gov/nwis/gwlevels/`

#### Tags

- Groundwater
- Water Levels
- Wells
- Aquifers
- Historical

#### Properties

- [Documentation](https://waterservices.usgs.gov/docs/groundwater-levels/groundwater-levels-details/)
- [Website](https://waterservices.usgs.gov/)

### USGS OGC Continuous Values API

Next-generation OGC API compliant service (api.waterdata.usgs.gov) providing real-time continuous sensor measurements including streamflow, gage height, and hundreds of other parameters. Implements OGC API – Features standard with CQL2 filtering, spatial bounding-box queries, and temporal filtering. Supports JSON, HTML, CSV, and JSON-LD output formats.

- **Human URL:** [https://api.waterdata.usgs.gov/docs/](https://api.waterdata.usgs.gov/docs/)
- **Base URL:** `https://api.waterdata.usgs.gov/ogcapi/v0/collections/continuous`

#### Tags

- Real-Time
- OGC
- Streamflow
- Continuous Data
- Next Generation

#### Properties

- [Documentation](https://api.waterdata.usgs.gov/docs/)
- [OpenAPI](https://api.waterdata.usgs.gov/ogcapi/v0/openapi?f=json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Website](https://api.waterdata.usgs.gov/)

### USGS OGC Daily Values API

OGC API compliant service for historical summarized daily water data with derived statistics. Part of the next-generation USGS Water Data API platform replacing the legacy WaterServices (slated for decommission in early 2027). Supports CQL2 filtering, geospatial queries, and multiple output formats.

- **Human URL:** [https://api.waterdata.usgs.gov/docs/](https://api.waterdata.usgs.gov/docs/)
- **Base URL:** `https://api.waterdata.usgs.gov/ogcapi/v0/collections/daily`

#### Tags

- Daily Values
- OGC
- Historical
- Next Generation

#### Properties

- [Documentation](https://api.waterdata.usgs.gov/docs/)
- [OpenAPI](https://api.waterdata.usgs.gov/ogcapi/v0/openapi?f=json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Website](https://api.waterdata.usgs.gov/)

### USGS OGC Monitoring Locations API

OGC API compliant service providing location details, geographic data, and site identifiers for USGS monitoring stations. Returns rich metadata including site type, drainage area, altitude, aquifer codes, and active parameter inventory.

- **Human URL:** [https://api.waterdata.usgs.gov/docs/](https://api.waterdata.usgs.gov/docs/)
- **Base URL:** `https://api.waterdata.usgs.gov/ogcapi/v0/collections/monitoring-locations`

#### Tags

- Monitoring Locations
- Site Metadata
- Geospatial
- OGC

#### Properties

- [Documentation](https://api.waterdata.usgs.gov/docs/)
- [OpenAPI](https://api.waterdata.usgs.gov/ogcapi/v0/openapi?f=json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Website](https://api.waterdata.usgs.gov/)

### Water Quality Portal (WQP) API

A cooperative service sponsored by USGS and EPA providing access to water quality data from over 400 agencies including USGS NWIS and EPA WQX. Endpoints cover monitoring sites, chemistry results, biological metrics, activity data, and detection limits. Supports spatial, temporal, characteristic, and organizational filters. Output formats include CSV, TSV, XLSX, XML, GeoJSON, KML, and KMZ.

- **Human URL:** [https://www.waterqualitydata.us/webservices_documentation/](https://www.waterqualitydata.us/webservices_documentation/)
- **Base URL:** `https://www.waterqualitydata.us/data/`

#### Tags

- Water Quality
- EPA
- Chemistry
- Biology
- Monitoring
- Multi-Agency

#### Properties

- [Documentation](https://www.waterqualitydata.us/webservices_documentation/)
- [Website](https://www.waterqualitydata.us/)

### USGS Water Data Statistics API

Next-generation statistics API at api.waterdata.usgs.gov providing computed statistical summaries for USGS water time series. Part of the platform replacing the legacy WaterServices statistics endpoint.

- **Human URL:** [https://api.waterdata.usgs.gov/statistics/v0/docs](https://api.waterdata.usgs.gov/statistics/v0/docs)
- **Base URL:** `https://api.waterdata.usgs.gov/statistics/v0/`

#### Tags

- Statistics
- Next Generation
- Time Series

#### Properties

- [Documentation](https://api.waterdata.usgs.gov/statistics/v0/docs)
- [Website](https://api.waterdata.usgs.gov/)

## Common Properties

- [Website](https://waterservices.usgs.gov/)
- [Website](https://api.waterdata.usgs.gov/)
- [Documentation](https://waterservices.usgs.gov/docs/)
- [Documentation](https://api.waterdata.usgs.gov/docs/)
- [Sign Up](https://api.waterdata.usgs.gov/signup/)
- [Privacy Policy](https://www.doi.gov/privacy)
- [Terms of Service](https://www.usgs.gov/information-policies-and-instructions/copyrights-and-credits)
- [Contact](mailto:wdfn@usgs.gov)
- [Status Page](https://waterservices.usgs.gov/test-tools/)
- [Plans](https://raw.githubusercontent.com/api-evangelist/usgs-water/refs/heads/main/plans/usgs-water-plans.yml)
- [Rate Limits](https://raw.githubusercontent.com/api-evangelist/usgs-water/refs/heads/main/rate-limits/usgs-water-rate-limits.yml)
- [Fin Ops](https://raw.githubusercontent.com/api-evangelist/usgs-water/refs/heads/main/finops/usgs-water-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
