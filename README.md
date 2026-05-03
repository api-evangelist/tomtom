# TomTom

TomTom provides a comprehensive suite of location technology APIs and SDKs including maps, search, routing, traffic, navigation, and automotive data services. Trusted by major automotive manufacturers, logistics companies, and application developers worldwide.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/tomtom/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

 - Maps, Traffic, Transportation, Navigation, Location, Geospatial, Routing, Geocoding

## Timestamps

- **Created:** 2025-01-07
- **Modified:** 2026-05-03

## APIs

### TomTom Maps API

Raster and vector map tiles for display in web and mobile applications. Supports 19+ zoom levels.

**Human URL:** [https://developer.tomtom.com/map-display-api/documentation/product-information/introduction](https://developer.tomtom.com/map-display-api/documentation/product-information/introduction)

#### Properties

- [Documentation](https://developer.tomtom.com/map-display-api/documentation/product-information/introduction)
- [OpenAPI](openapi/tomtom-maps-openapi.yml)

### TomTom Search API

Fuzzy search for addresses, points of interest, and geographic features. Includes geocoding, reverse geocoding, and batch search.

**Human URL:** [https://developer.tomtom.com/search-api/documentation/product-information/introduction](https://developer.tomtom.com/search-api/documentation/product-information/introduction)

#### Properties

- [Documentation](https://developer.tomtom.com/search-api/documentation/product-information/introduction)
- [OpenAPI](openapi/tomtom-search-openapi.yml)
- [API Explorer](https://developer.tomtom.com/search-api/api-explorer)

### TomTom Routing API

Route calculation with up to 150 waypoints, traffic optimization, EV routing, reachable range, and batch routing.

**Human URL:** [https://developer.tomtom.com/routing-api/documentation/tomtom-maps/product-information/introduction](https://developer.tomtom.com/routing-api/documentation/tomtom-maps/product-information/introduction)

#### Properties

- [Documentation](https://developer.tomtom.com/routing-api/documentation/tomtom-maps/product-information/introduction)
- [OpenAPI](openapi/tomtom-routing-openapi.yml)
- [API Explorer](https://developer.tomtom.com/routing-api/api-explorer)
- [Naftiko Capabilities](capabilities/location-intelligence.yaml)
- [Spectral Rules](rules/tomtom-rules.yml)
- [Vocabulary](vocabulary/tomtom-vocabulary.yml)

### TomTom Traffic API

Real-time traffic incidents and flow data, updated every minute. Supports raster and vector tile formats.

**Human URL:** [https://developer.tomtom.com/traffic-api/documentation/product-information/introduction](https://developer.tomtom.com/traffic-api/documentation/product-information/introduction)

#### Properties

- [Documentation](https://developer.tomtom.com/traffic-api/documentation/product-information/introduction)
- [OpenAPI](openapi/tomtom-traffic-openapi.yml)
- [API Explorer](https://developer.tomtom.com/traffic-api/api-explorer)

### TomTom Geocoding API

Structured address geocoding and reverse geocoding. Premium variant includes parking and building entrance data.

**Human URL:** [https://developer.tomtom.com/geocoding-api/documentation/product-information/introduction](https://developer.tomtom.com/geocoding-api/documentation/product-information/introduction)

### TomTom Fuel Prices API

Current fuel price information at specific fueling stations.

**Human URL:** [https://developer.tomtom.com/fuel-prices-api/documentation/tomtom-maps/product-information/introduction](https://developer.tomtom.com/fuel-prices-api/documentation/tomtom-maps/product-information/introduction)

### TomTom Parking Availability API

Real-time availability status of parking sites and on-street parking.

**Human URL:** [https://developer.tomtom.com/parking-availability-api/documentation/tomtom-maps/product-information/introduction](https://developer.tomtom.com/parking-availability-api/documentation/tomtom-maps/product-information/introduction)

### TomTom Geofencing API

Virtual geographic boundary creation and asset tracking with location history and notifications.

**Human URL:** [https://developer.tomtom.com/geofencing-api/documentation/product-information/introduction](https://developer.tomtom.com/geofencing-api/documentation/product-information/introduction)

### TomTom AutoStream API

Automotive map data delivery platform for on-demand and OTA cloud-to-device streaming.

**Human URL:** [https://developer.tomtom.com/autostream-sdk/documentation/product-information/introduction](https://developer.tomtom.com/autostream-sdk/documentation/product-information/introduction)

## Artifacts

### OpenAPI Specifications

| Spec | Description |
|------|-------------|
| [openapi/tomtom-maps-openapi.yml](openapi/tomtom-maps-openapi.yml) | Maps raster and vector tile API |
| [openapi/tomtom-search-openapi.yml](openapi/tomtom-search-openapi.yml) | Search, geocoding, and POI |
| [openapi/tomtom-routing-openapi.yml](openapi/tomtom-routing-openapi.yml) | Route calculation and reachable range |
| [openapi/tomtom-traffic-openapi.yml](openapi/tomtom-traffic-openapi.yml) | Traffic incidents and flow |

### Spectral Rules

- [rules/tomtom-rules.yml](rules/tomtom-rules.yml) — Governance ruleset for TomTom API conventions

### Naftiko Capabilities

| Capability | Description |
|------------|-------------|
| [location-intelligence.yaml](capabilities/location-intelligence.yaml) | Unified search, routing, and traffic (8 MCP tools) |

**Shared:**
- [capabilities/shared/tomtom-routing.yaml](capabilities/shared/tomtom-routing.yaml)
- [capabilities/shared/tomtom-search.yaml](capabilities/shared/tomtom-search.yaml)
- [capabilities/shared/tomtom-traffic.yaml](capabilities/shared/tomtom-traffic.yaml)

### JSON Schema

- [json-schema/tomtom-route-schema.json](json-schema/tomtom-route-schema.json)

### JSON Structure

- [json-structure/tomtom-route-structure.json](json-structure/tomtom-route-structure.json)

### JSON-LD

- [json-ld/tomtom-context.jsonld](json-ld/tomtom-context.jsonld)

### Examples

- [examples/tomtom-calculate-route-example.json](examples/tomtom-calculate-route-example.json)
- [examples/tomtom-traffic-incidents-example.json](examples/tomtom-traffic-incidents-example.json)

### Vocabulary

- [vocabulary/tomtom-vocabulary.yml](vocabulary/tomtom-vocabulary.yml)

## Common Properties

- [Website](https://www.tomtom.com/)
- [Developer Portal](https://developer.tomtom.com/)
- [Documentation](https://developer.tomtom.com/)
- [Sign Up](https://developer.tomtom.com/)
- [API Explorer](https://developer.tomtom.com/api-explorer-index/documentation/product-information/introduction)
- [MCP Server](https://developer.tomtom.com/tomtom-mcp-server)
- [Blog](https://developer.tomtom.com/blog)
- [GitHub Organization](https://github.com/tomtom-international)
- [Pricing](https://developer.tomtom.com/pricing)
- [Terms of Service](https://developer.tomtom.com/terms-and-conditions)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
