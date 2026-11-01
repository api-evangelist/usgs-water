# USGS Water Services

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

The U.S. Geological Survey (USGS) National Water Information System (NWIS) exposes a suite of REST APIs providing access to real-time and historical water data from over 1.5 million monitoring locations across the United States and territories. The legacy WaterServices APIs (being decommissioned in early 2027) and the next-generation api.waterdata.usgs.gov OGC-compliant APIs together cover streamflow, groundwater levels, water quality, site metadata, and statistical summaries. All services are free, publicly funded, and require no authentication for standard use; API keys are available at no cost for higher rate-limit access.

**Areas:** Water · Streamflow · Groundwater · Water Quality · Hydrology · Environmental · USGS · NWIS · Government · Open Data · OGC

## USGS Water Services on APIs.io

Everything profiled for USGS Water Services is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/usgs-water/](https://apis.io/providers/usgs-water/)** — or go straight to one of the APIs or properties below.

### APIs (44)

- [USGS Instantaneous Values Service](https://apis.io/apis/usgs-water/instantaneous-values/) — Provides near real-time water data — streamflow, gage height, temperature, specific conductance, and hundreds of other parameters — from thousands of USGS…
- [USGS Daily Values Service](https://apis.io/apis/usgs-water/daily-values/) — Returns historical summarized daily hydrologic data (mean, median, maximum, minimum) for streams, lakes, estuaries, and wells. Many sites have more than 10…
- [USGS Site Service](https://apis.io/apis/usgs-water/site-service/) — Searches and retrieves metadata for millions of USGS hydrologic data collection sites including streams, springs, wells, lakes, reservoirs, estuaries, and…
- [USGS Statistics Service](https://apis.io/apis/usgs-water/statistics-service/) — Retrieves daily, monthly, or annual statistics (mean, minimum, maximum, median, and percentiles P05–P95) computed from approved historical time-series data.…
- [USGS Groundwater Levels Service](https://apis.io/apis/usgs-water/groundwater-levels/) — Provides historical manually-recorded groundwater level measurements from USGS wells and monitoring sites. Returns depth-to-water and…
- [Water Quality Portal (WQP) API](https://apis.io/apis/usgs-water/water-quality-portal/) — A cooperative service sponsored by USGS and EPA providing access to water quality data from over 400 agencies including USGS NWIS and EPA WQX. Endpoints…
- [USGS Water Data Statistics API](https://apis.io/apis/usgs-water/statistics-next-gen/) — Next-generation statistics API at api.waterdata.usgs.gov providing computed statistical summaries for USGS water time series. Part of the platform replacing…
- [USGS Water Services Agency Codes API](https://apis.io/apis/usgs-water/usgs-water-agency-codes-api/) — Code identifying the agency or organization used for site information, data sources, and permitting agencies. Agency codes are fixed values assigned by the…
- [USGS Water Services Altitude Datums API](https://apis.io/apis/usgs-water/usgs-water-altitude-datums-api/) — The recommended vertical datum is NAVD88 (North American Vertical Datum of 1988) where applicable as stated in Office of Information Technical Memo 2002.01.…
- [USGS Water Services Aquifer Codes API](https://apis.io/apis/usgs-water/usgs-water-aquifer-codes-api/) — Local aquifers in USGS data are identified by an aquifer name and geohydrologic unit code (a three-digit number related to the age of the formation,…
- [USGS Water Services Aquifer Types API](https://apis.io/apis/usgs-water/usgs-water-aquifer-types-api/) — Groundwater occurs in aquifers under two different conditions. Where water only partly fills an aquifer, the upper surface is free to rise and decline.…
- [USGS Water Services Channel Measurements API](https://apis.io/apis/usgs-water/usgs-water-channel-measurements-api/) — Channel measurements taken as part of streamflow field measurements.
- [USGS Water Services Citations API](https://apis.io/apis/usgs-water/usgs-water-citations-api/) — Citations associated with water measurement methods.
- [USGS Water Services Combined Metadata API](https://apis.io/apis/usgs-water/usgs-water-combined-metadata-api/) — This endpoint combines metadata from timeseries and field measurements collections by site.
- [USGS Water Services Continuous API](https://apis.io/apis/usgs-water/usgs-water-continuous-api/) — Continuous data are collected via automated sensors installed at a monitoring location. They are collected at a high frequency and often at a fixed…
- [USGS Water Services Coordinate Accuracy Codes API](https://apis.io/apis/usgs-water/usgs-water-coordinate-accuracy-codes-api/) — Appropriate code on the schedule to indicate the accuracy of the latitude-longitude values.
- [USGS Water Services Coordinate Datum Codes API](https://apis.io/apis/usgs-water/usgs-water-coordinate-datum-codes-api/) — Horizontal datum code for the latitude/longitude coordinates. There are currently more than 300 horizontal datums available for entry.
- [USGS Water Services Coordinate Method Codes API](https://apis.io/apis/usgs-water/usgs-water-coordinate-method-codes-api/) — Methods used to determine latitude-longitude values.
- [USGS Water Services Counties API](https://apis.io/apis/usgs-water/usgs-water-counties-api/) — The name of the county or county equivalent (parish, borough, planning reagion, etc.) in which the site is located. List includes Census Bureau FIPS county…
- [USGS Water Services Countries API](https://apis.io/apis/usgs-water/usgs-water-countries-api/) — FIPS country codes and names.
- [USGS Water Services Daily API](https://apis.io/apis/usgs-water/usgs-water-daily-api/) — Daily data provide one data value to represent water conditions for the day. Throughout much of the history of the USGS, the primary water data available…
- [USGS Water Services Field Measurements API](https://apis.io/apis/usgs-water/usgs-water-field-measurements-api/) — Field measurements are physically measured values collected during a visit to the monitoring location. Field measurements consist of measurements of gage…
- [USGS Water Services Field Measurements Metadata API](https://apis.io/apis/usgs-water/usgs-water-field-measurements-metadata-api/) — This endpoint provides metadata about field measurement collections, including when the earliest and most recent observations for a parameter occurred at a…
- [USGS Water Services Hydrologic Unit Codes API](https://apis.io/apis/usgs-water/usgs-water-hydrologic-unit-codes-api/) — Hydrologic units are geographic areas representing part or all of a surface drainage basin or distinct hydrologic feature identified by a unique number…
- [USGS Water Services Latest Continuous API](https://apis.io/apis/usgs-water/usgs-water-latest-continuous-api/) — This endpoint provides the most recent observation for each time series of continuous data. Continuous data are collected via automated sensors installed at…
- [USGS Water Services Latest Daily API](https://apis.io/apis/usgs-water/usgs-water-latest-daily-api/) — Daily data provide one data value to represent water conditions for the day. Throughout much of the history of the USGS, the primary water data available…
- [USGS Water Services Latest Field Measurements API](https://apis.io/apis/usgs-water/usgs-water-latest-field-measurements-api/) — Field measurements are physically measured values collected during a visit to the monitoring location. Field measurements consist of measurements of gage…
- [USGS Water Services Medium Codes API](https://apis.io/apis/usgs-water/usgs-water-medium-codes-api/) — Medium refers to the specific environmental medium from which the sample was collected. Medium type differs from site type because one site type, such as…
- [USGS Water Services Method Categories API](https://apis.io/apis/usgs-water/usgs-water-method-categories-api/) — Categorical standards for methods describing the associated data's appropriateness for an intended use.
- [USGS Water Services Method Citations API](https://apis.io/apis/usgs-water/usgs-water-method-citations-api/) — Citation identifiers for water measurement methods.
- [USGS Water Services Methods API](https://apis.io/apis/usgs-water/usgs-water-methods-api/) — Water measurement or water-quality analytical methods. Codes and descriptions defining a method for calculating or measuring the value of a water quality or…
- [USGS Water Services Monitoring Locations API](https://apis.io/apis/usgs-water/usgs-water-monitoring-locations-api/) — Location information is basic information about the monitoring location including the name, identifier, agency responsible for data collection, and the date…
- [USGS Water Services National Aquifer Codes API](https://apis.io/apis/usgs-water/usgs-water-national-aquifer-codes-api/) — National aquifers are the principal aquifers or aquifer systems in the United States, defined as regionally extensive aquifers or aquifer systems that have…
- [USGS Water Services Parameter Codes API](https://apis.io/apis/usgs-water/usgs-water-parameter-codes-api/) — Parameter codes are 5-digit codes and associated descriptions used to identify the constituent measured and the units of measure. Some parameter code…
- [USGS Water Services Peaks API](https://apis.io/apis/usgs-water/usgs-water-peaks-api/) — Annual peak flow values are the maximum instantaneous streamflow values recorded at a particular site for the entire water year from October 1 to September…
- [USGS Water Services Reliability Codes API](https://apis.io/apis/usgs-water/usgs-water-reliability-codes-api/) — Code indicating the reliability of the data available for the site.
- [USGS Water Services Server API](https://apis.io/apis/usgs-water/usgs-water-server-api/) — These APIs provide OGC-compliant interfaces to USGS water data, letting you download continuous sensor measurements, discrete field measurements, metadata…
- [USGS Water Services Site Types API](https://apis.io/apis/usgs-water/usgs-water-site-types-api/) — The hydrologic cycle setting or a man-made feature thought to affect the hydrologic conditions measured at a site. Primary and secondary site types…
- [USGS Water Services States API](https://apis.io/apis/usgs-water/usgs-water-states-api/) — State name or territory. Includes U.S. states and foreign entities classified under FIPS as 'Principal Administrative Divisions'.
- [USGS Water Services Statistic Codes API](https://apis.io/apis/usgs-water/usgs-water-statistic-codes-api/) — Statistic codes.
- [USGS Water Services Time Series Metadata API](https://apis.io/apis/usgs-water/usgs-water-time-series-metadata-api/) — Daily data and continuous measurements are grouped into time series, which represent a collection of observations of a single parameter, potentially…
- [USGS Water Services Time Zone Codes API](https://apis.io/apis/usgs-water/usgs-water-time-zone-codes-api/) — The ISO 8601 standard defines time zone offsets as a numerical value added to a local time to convert it to Coordinated Universal Time (UTC), either as…
- [USGS Water Services Topographic Codes API](https://apis.io/apis/usgs-water/usgs-water-topographic-codes-api/) — The code that best describes the topographic setting in which the site is located. Topographic setting refers to the geomorphic features in the vicinity of…
- [USGS Water Services](https://apis.io/apis/usgs-water/usgs-water-services/) — Water quality and level info for rivers and lakes

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Usgs Water Agentic Access](https://apis.io/agentic-access/usgs-water/usgs-water-agentic-access/)

#### JSON Schema (35)

The data models the API reads and writes.

- [Agency Codes](https://apis.io/schemas/usgs-water/agency-codes/)
- [Altitude Datums](https://apis.io/schemas/usgs-water/altitude-datums/)
- [Aquifer Codes](https://apis.io/schemas/usgs-water/aquifer-codes/)
- [Aquifer Types](https://apis.io/schemas/usgs-water/aquifer-types/)
- [Channel Measurements](https://apis.io/schemas/usgs-water/channel-measurements/)
- [Citations](https://apis.io/schemas/usgs-water/citations/)
- [Combined Metadata](https://apis.io/schemas/usgs-water/combined-metadata/)
- [Continuous](https://apis.io/schemas/usgs-water/continuous/)
- [Coordinate Accuracy Codes](https://apis.io/schemas/usgs-water/coordinate-accuracy-codes/)
- [Coordinate Datum Codes](https://apis.io/schemas/usgs-water/coordinate-datum-codes/)
- [Coordinate Method Codes](https://apis.io/schemas/usgs-water/coordinate-method-codes/)
- [Counties](https://apis.io/schemas/usgs-water/counties/)
- [Countries](https://apis.io/schemas/usgs-water/countries/)
- [Daily](https://apis.io/schemas/usgs-water/daily/)
- [Field Measurements](https://apis.io/schemas/usgs-water/field-measurements/)
- [Field Measurements Metadata](https://apis.io/schemas/usgs-water/field-measurements-metadata/)
- [Hydrologic Unit Codes](https://apis.io/schemas/usgs-water/hydrologic-unit-codes/)
- [Latest Continuous](https://apis.io/schemas/usgs-water/latest-continuous/)
- [Latest Daily](https://apis.io/schemas/usgs-water/latest-daily/)
- [Latest Field Measurements](https://apis.io/schemas/usgs-water/latest-field-measurements/)
- [Medium Codes](https://apis.io/schemas/usgs-water/medium-codes/)
- [Method Categories](https://apis.io/schemas/usgs-water/method-categories/)
- [Method Citations](https://apis.io/schemas/usgs-water/method-citations/)
- [Methods](https://apis.io/schemas/usgs-water/methods/)
- [Monitoring Locations](https://apis.io/schemas/usgs-water/monitoring-locations/)
- …and 10 more published on APIs.io

#### JSON-LD (2)

Linked-data contexts for the provider's vocabulary.

- [Usgs Water Api Context](https://apis.io/jsonld/usgs-water/usgs-water-api/)
- [Usgs Water Context](https://apis.io/jsonld/usgs-water/usgs-water-context/)

#### Examples (1)

Example requests and responses.

- [Usgs Water Examples](https://apis.io/examples/usgs-water/usgs-water-examples/)

#### Collections (36)

Postman and Open Collection request collections.

- [USGS Water Data OGC APIs agency-codes API](https://apis.io/collections/usgs-water/open-usgs-water-agency-codes-api/)
- [USGS Water Data OGC APIs agency-codes altitude-datums API](https://apis.io/collections/usgs-water/open-usgs-water-altitude-datums-api/)
- [USGS Water Data OGC APIs agency-codes aquifer-codes API](https://apis.io/collections/usgs-water/open-usgs-water-aquifer-codes-api/)
- [USGS Water Data OGC APIs agency-codes aquifer-types API](https://apis.io/collections/usgs-water/open-usgs-water-aquifer-types-api/)
- [USGS Water Data OGC APIs agency-codes channel-measurements API](https://apis.io/collections/usgs-water/open-usgs-water-channel-measurements-api/)
- [USGS Water Data OGC APIs agency-codes citations API](https://apis.io/collections/usgs-water/open-usgs-water-citations-api/)
- [USGS Water Data OGC APIs agency-codes combined-metadata API](https://apis.io/collections/usgs-water/open-usgs-water-combined-metadata-api/)
- [USGS Water Data OGC APIs agency-codes continuous API](https://apis.io/collections/usgs-water/open-usgs-water-continuous-api/)
- [USGS Water Data OGC APIs agency-codes coordinate-accuracy-codes API](https://apis.io/collections/usgs-water/open-usgs-water-coordinate-accuracy-codes-api/)
- [USGS Water Data OGC APIs agency-codes coordinate-datum-codes API](https://apis.io/collections/usgs-water/open-usgs-water-coordinate-datum-codes-api/)
- [USGS Water Data OGC APIs agency-codes coordinate-method-codes API](https://apis.io/collections/usgs-water/open-usgs-water-coordinate-method-codes-api/)
- [USGS Water Data OGC APIs agency-codes counties API](https://apis.io/collections/usgs-water/open-usgs-water-counties-api/)
- [USGS Water Data OGC APIs agency-codes countries API](https://apis.io/collections/usgs-water/open-usgs-water-countries-api/)
- [USGS Water Data OGC APIs agency-codes daily API](https://apis.io/collections/usgs-water/open-usgs-water-daily-api/)
- [USGS Water Data OGC APIs agency-codes field-measurements API](https://apis.io/collections/usgs-water/open-usgs-water-field-measurements-api/)
- [USGS Water Data OGC APIs agency-codes field-measurements-metadata API](https://apis.io/collections/usgs-water/open-usgs-water-field-measurements-metadata-api/)
- [USGS Water Data OGC APIs agency-codes hydrologic-unit-codes API](https://apis.io/collections/usgs-water/open-usgs-water-hydrologic-unit-codes-api/)
- [USGS Water Data OGC APIs agency-codes latest-continuous API](https://apis.io/collections/usgs-water/open-usgs-water-latest-continuous-api/)
- [USGS Water Data OGC APIs agency-codes latest-daily API](https://apis.io/collections/usgs-water/open-usgs-water-latest-daily-api/)
- [USGS Water Data OGC APIs agency-codes latest-field-measurements API](https://apis.io/collections/usgs-water/open-usgs-water-latest-field-measurements-api/)
- [USGS Water Data OGC APIs agency-codes medium-codes API](https://apis.io/collections/usgs-water/open-usgs-water-medium-codes-api/)
- [USGS Water Data OGC APIs agency-codes method-categories API](https://apis.io/collections/usgs-water/open-usgs-water-method-categories-api/)
- [USGS Water Data OGC APIs agency-codes method-citations API](https://apis.io/collections/usgs-water/open-usgs-water-method-citations-api/)
- [USGS Water Data OGC APIs agency-codes methods API](https://apis.io/collections/usgs-water/open-usgs-water-methods-api/)
- [USGS Water Data OGC APIs agency-codes monitoring-locations API](https://apis.io/collections/usgs-water/open-usgs-water-monitoring-locations-api/)
- …and 11 more published on APIs.io

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [USGS Water Services — jsonschema rules](https://apis.io/rules/usgs-water/usgs-water-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Usgs Water Authentication](https://apis.io/security/usgs-water/usgs-water-authentication/)
- [Usgs Water Domain Security](https://apis.io/security/usgs-water/usgs-water-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Usgs Water Plans](https://apis.io/plans/usgs-water/usgs-water-plans/)

#### Rate limits (1)

Published request limits.

- [Usgs Water Rate Limits](https://apis.io/rate-limits/usgs-water/usgs-water-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Usgs Water Finops](https://apis.io/finops/usgs-water/usgs-water-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://waterservices.usgs.gov/)
- [Documentation](https://waterservices.usgs.gov/docs/)
- [Terms of service](https://www.usgs.gov/information-policies-and-instructions/copyrights-and-credits)
- [Privacy policy](https://www.doi.gov/privacy)
- [Status](https://waterservices.usgs.gov/test-tools/)

## API Evangelist rating

**Kin Score 37.4** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 54.9 |
| Contract governance | 9.8 |
| Operational transparency | 21.1 |
| Developer ergonomics | 21.4 |
| Access clarity | 39.5 |

**Agent readiness 19.8** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 24.5** — Government & Public Sector

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/usgs-water/](https://apis.io/providers/usgs-water/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for USGS Water Services: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/usgs-water/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
