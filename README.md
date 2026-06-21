# WorkWave (workwave)

WorkWave builds field-service and last-mile delivery software for service professionals in pest control, lawn care, cleaning, security, and delivery. Its RouteManager product exposes the WorkWave Route Manager (WWRM) REST API for managing territories, depots, drivers, vehicles, orders, route optimization, time of arrival, and GPS tracking, with API-key authentication and webhook callbacks.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/workwave/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/workwave/refs/heads/main/apis.yml)

## Tags

- Field Service
- Route Optimization
- Last Mile Delivery
- Fleet
- GPS Tracking
- Logistics

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### WorkWave Route Manager - Orders, Routes & Territories

Core RouteManager resources for managing territories, depots, regions, companies, orders, and optimized routes (Time of Arrival). Write operations are asynchronous and queued per territory, returning a requestId resolved via webhook callback.

- **Human URL:** [https://wwrm.workwave.com/api/](https://wwrm.workwave.com/api/)
- **Base URL:** `https://wwrm.workwave.com/api/v1`

#### Tags

- Orders
- Routes
- Territories
- Route Optimization

#### Properties

- [Documentation](https://wwrm.workwave.com/api/)
- [API Reference](https://wwrm.workwave.com/api/)
- [OpenAPI](openapi/workwave-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/workwave.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workwave.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### WorkWave Route Manager - Drivers & Vehicles

Manage the driver roster and vehicle fleet within a territory, including per-vehicle and per-date settings used by the route optimizer.

- **Human URL:** [https://wwrm.workwave.com/api/](https://wwrm.workwave.com/api/)
- **Base URL:** `https://wwrm.workwave.com/api/v1`

#### Tags

- Drivers
- Vehicles
- Fleet

#### Properties

- [Documentation](https://wwrm.workwave.com/api/)
- [OpenAPI](openapi/workwave-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/workwave.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workwave.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### WorkWave Route Manager - GPS Tracking

Retrieve GPS tracking and real-time location data for drivers and vehicles, integrating telematics providers such as Verizon Connect, Linxup, Azuga, and any Geotab-powered GPS provider.

- **Human URL:** [https://wwrm.workwave.com/api/](https://wwrm.workwave.com/api/)
- **Base URL:** `https://wwrm.workwave.com/api/v1`

#### Tags

- GPS Tracking
- Telematics
- Real Time Location

#### Properties

- [Documentation](https://wwrm.workwave.com/api/)
- [OpenAPI](openapi/workwave-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/workwave.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workwave.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### WorkWave Route Manager - Webhooks

Register and manage the HTTP callback (webhook) URL that receives asynchronous notifications for completed write operations, data changes, and route approvals, with automatic retries on delivery failure.

- **Human URL:** [https://wwrm.workwave.com/api/](https://wwrm.workwave.com/api/)
- **Base URL:** `https://wwrm.workwave.com/api/v1`

#### Tags

- Webhooks
- Callbacks
- Notifications

#### Properties

- [Documentation](https://wwrm.workwave.com/api/)
- [OpenAPI](openapi/workwave-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/workwave.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workwave.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/WorkWave)
- [LinkedIn](https://www.linkedin.com/company/workwave)
- [Website](https://www.workwave.com)
- [Documentation](https://wwrm.workwave.com/api/)
- [Plans](plans/workwave-plans-pricing.yml)
- [Rate Limits](rate-limits/workwave-rate-limits.yml)
- [Fin Ops](finops/workwave-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
