# TomTom (tomtom)

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
