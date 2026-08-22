# TomTom (tomtom)

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

TomTom provides a comprehensive suite of location technology APIs and SDKs including maps, search, routing, traffic, navigation, and automotive data services. The TomTom developer platform is trusted by major automotive manufacturers, logistics companies, and application developers. APIs cover real-time traffic incidents and flow, route calculation, geocoding, points of interest search, geofencing, parking availability, fuel prices, and electric vehicle routing. TomTom also provides an MCP Server for AI integration with location intelligence.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/tomtom/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/tomtom/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Maps
- Traffic
- Transportation
- Navigation
- Location
- Geospatial
- Routing
- Geocoding

## Timestamps

- **Created:** 2025-01-07
- **Modified:** 2026-05-19

## APIs

### TomTom Maps API

The TomTom Maps API provides raster and vector map tiles for display in web and mobile applications. Includes copyright information endpoints and supports 19+ zoom levels. Returns PNG/JPG tiles for raster and Protocol Buffer format for vector tiles.

- **Human URL:** [https://developer.tomtom.com/map-display-api/documentation/product-information/introduction](https://developer.tomtom.com/map-display-api/documentation/product-information/introduction)
- **Base URL:** `https://api.tomtom.com`

#### Tags

- Maps
- Tiles
- Raster
- Vector

#### Properties

- [Documentation](https://developer.tomtom.com/map-display-api/documentation/product-information/introduction)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/tomtom/refs/heads/main/openapi/tomtom-maps-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tomtom-maps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomtom-maps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/tomtom-routing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomtom-routing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/tomtom-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomtom-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/tomtom-traffic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomtom-traffic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TomTom Search API

The TomTom Search API provides fuzzy search for addresses, points of interest, and geographic features. Returns latitude/longitude coordinates, place details, and geometry data. Includes additional data retrieval, structured geocoding, and batch search capabilities.

- **Human URL:** [https://developer.tomtom.com/search-api/documentation/product-information/introduction](https://developer.tomtom.com/search-api/documentation/product-information/introduction)
- **Base URL:** `https://api.tomtom.com`

#### Tags

- Search
- Geocoding
- Points of Interest
- Location

#### Properties

- [Documentation](https://developer.tomtom.com/search-api/documentation/product-information/introduction)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/tomtom/refs/heads/main/openapi/tomtom-search-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [A P I  Explorer](https://developer.tomtom.com/search-api/api-explorer)
- [Postman Collection](collections/tomtom-maps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomtom-maps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/tomtom-routing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomtom-routing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/tomtom-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomtom-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/tomtom-traffic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomtom-traffic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TomTom Routing API

The TomTom Routing API calculates routes between origins and destinations with support for up to 150 waypoints, real-time and historical traffic, vehicle type optimization, EV consumption models, reachable range calculation, and batch routing for multiple route requests.

- **Human URL:** [https://developer.tomtom.com/routing-api/documentation/tomtom-maps/product-information/introduction](https://developer.tomtom.com/routing-api/documentation/tomtom-maps/product-information/introduction)
- **Base URL:** `https://api.tomtom.com`

#### Tags

- Routing
- Navigation
- Transportation
- Electric Vehicle

#### Properties

- [Documentation](https://developer.tomtom.com/routing-api/documentation/tomtom-maps/product-information/introduction)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/tomtom/refs/heads/main/openapi/tomtom-routing-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [A P I  Explorer](https://developer.tomtom.com/routing-api/api-explorer)
- [Postman Collection](collections/tomtom-maps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomtom-maps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/tomtom-routing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomtom-routing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/tomtom-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomtom-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/tomtom-traffic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomtom-traffic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TomTom Traffic API

The TomTom Traffic API provides real-time traffic incidents and flow data. The Traffic Incidents service delivers accurate information about jams, accidents, and delays. The Traffic Flow service provides observed speeds and travel times updated every minute for key roads. Includes raster and vector tile formats.

- **Human URL:** [https://developer.tomtom.com/traffic-api/documentation/product-information/introduction](https://developer.tomtom.com/traffic-api/documentation/product-information/introduction)
- **Base URL:** `https://api.tomtom.com`

#### Tags

- Traffic
- Incidents
- Real-Time
- Transportation

#### Properties

- [Documentation](https://developer.tomtom.com/traffic-api/documentation/product-information/introduction)
- [A P I  Explorer](https://developer.tomtom.com/traffic-api/api-explorer)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/tomtom/refs/heads/main/openapi/tomtom-traffic-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/tomtom/refs/heads/main/rules/tomtom-rules.yml)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/tomtom/refs/heads/main/vocabulary/tomtom-vocabulary.yml)
- [Postman Collection](collections/tomtom-maps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomtom-maps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/tomtom-routing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomtom-routing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/tomtom-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomtom-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/tomtom-traffic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomtom-traffic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TomTom Geocoding API

The TomTom Geocoding API converts structured addresses into geographic coordinates and supports reverse geocoding to translate coordinates into human-readable addresses. The Premium Geocoding API adds parking and building entrance location data.

- **Human URL:** [https://developer.tomtom.com/geocoding-api/documentation/product-information/introduction](https://developer.tomtom.com/geocoding-api/documentation/product-information/introduction)
- **Base URL:** `https://api.tomtom.com`

#### Tags

- Geocoding
- Location
- Address

#### Properties

- [Documentation](https://developer.tomtom.com/geocoding-api/documentation/product-information/introduction)
- [A P I  Explorer](https://developer.tomtom.com/geocoding-api/api-explorer)
- [Postman Collection](collections/tomtom-maps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomtom-maps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/tomtom-routing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomtom-routing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/tomtom-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomtom-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/tomtom-traffic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomtom-traffic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TomTom Fuel Prices API

The TomTom Fuel Prices API provides current fuel price information at specific fueling stations, including price by fuel type.

- **Human URL:** [https://developer.tomtom.com/fuel-prices-api/documentation/tomtom-maps/product-information/introduction](https://developer.tomtom.com/fuel-prices-api/documentation/tomtom-maps/product-information/introduction)
- **Base URL:** `https://api.tomtom.com`

#### Tags

- Fuel
- Prices
- Automotive

#### Properties

- [Documentation](https://developer.tomtom.com/fuel-prices-api/documentation/tomtom-maps/product-information/introduction)
- [Postman Collection](collections/tomtom-maps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomtom-maps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/tomtom-routing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomtom-routing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/tomtom-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomtom-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/tomtom-traffic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomtom-traffic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TomTom Parking Availability API

The TomTom Parking Availability API provides real-time availability status of parking sites and on-street parking, including pricing information.

- **Human URL:** [https://developer.tomtom.com/parking-availability-api/documentation/tomtom-maps/product-information/introduction](https://developer.tomtom.com/parking-availability-api/documentation/tomtom-maps/product-information/introduction)
- **Base URL:** `https://api.tomtom.com`

#### Tags

- Parking
- Transportation
- Real-Time

#### Properties

- [Documentation](https://developer.tomtom.com/parking-availability-api/documentation/tomtom-maps/product-information/introduction)
- [Postman Collection](collections/tomtom-maps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomtom-maps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/tomtom-routing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomtom-routing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/tomtom-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomtom-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/tomtom-traffic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomtom-traffic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TomTom Geofencing API

The TomTom Geofencing API enables creation and management of geofence boundaries, location history tracking, and notification delivery when assets enter or exit defined perimeters.

- **Human URL:** [https://developer.tomtom.com/geofencing-api/documentation/product-information/introduction](https://developer.tomtom.com/geofencing-api/documentation/product-information/introduction)
- **Base URL:** `https://api.tomtom.com`

#### Tags

- Geofencing
- Location
- Tracking
- Notifications

#### Properties

- [Documentation](https://developer.tomtom.com/geofencing-api/documentation/product-information/introduction)
- [Postman Collection](collections/tomtom-maps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomtom-maps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/tomtom-routing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomtom-routing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/tomtom-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomtom-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/tomtom-traffic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomtom-traffic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TomTom AutoStream API

TomTom AutoStream is a map data delivery platform optimized for on-demand and over-the-air cloud-to-device and cloud-to-cloud data streaming for automotive applications.

- **Human URL:** [https://developer.tomtom.com/autostream-sdk/documentation/product-information/introduction](https://developer.tomtom.com/autostream-sdk/documentation/product-information/introduction)
- **Base URL:** `https://api.tomtom.com`

#### Tags

- Maps
- Streaming
- Automotive

#### Properties

- [Documentation](https://developer.tomtom.com/autostream-sdk/documentation/product-information/introduction)
- [Postman Collection](collections/tomtom-maps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomtom-maps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/tomtom-routing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomtom-routing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/tomtom-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomtom-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/tomtom-traffic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tomtom-traffic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/tomtom)
- [Website](https://www.tomtom.com/)
- [Developer  Portal](https://developer.tomtom.com/)
- [Documentation](https://developer.tomtom.com/)
- [Sign Up](https://developer.tomtom.com/)
- [A P I  Explorer](https://developer.tomtom.com/api-explorer-index/documentation/product-information/introduction)
- [M C P  Server](https://developer.tomtom.com/tomtom-mcp-server)
- [Blog](https://developer.tomtom.com/blog)
- [GitHub Organization](https://github.com/tomtom-international)
- [Pricing](https://developer.tomtom.com/pricing)
- [Terms of Service](https://developer.tomtom.com/terms-and-conditions)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
