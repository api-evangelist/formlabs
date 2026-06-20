# Formlabs (formlabs)

Formlabs designs and manufactures desktop and industrial 3D printers (SLA and SLS), materials, and software (PreForm, Dashboard). Its developer platform exposes the Formlabs Web API (Dashboard Developer API) for remote monitoring and management of Internet-connected printers, prints, consumables, events, and printer groups, plus a Local API (PreFormServer) for local-network job preparation and printer control.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/formlabs/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/formlabs/refs/heads/main/apis.yml)

## Tags

- 3D Printing
- Additive Manufacturing
- SLA
- SLS
- Hardware
- Dashboard

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Formlabs Web API (Dashboard) - Printers

Remote listing and retrieval of Formlabs printers registered to a Dashboard account, including status, firmware, machine type, and group membership, for fleet monitoring and ERP/MES integration.

- **Human URL:** [https://formlabs-dashboard-api-resources.s3.amazonaws.com/formlabs-web-api-latest.html](https://formlabs-dashboard-api-resources.s3.amazonaws.com/formlabs-web-api-latest.html)
- **Base URL:** `https://api.formlabs.com/developer/v1`

#### Tags

- Printers
- Fleet
- Monitoring

#### Properties

- [Documentation](https://support.formlabs.com/s/topic/Developer-Portal)
- [API Reference](https://formlabs-dashboard-api-resources.s3.amazonaws.com/formlabs-web-api-latest.html)
- [OpenAPI](openapi/formlabs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/formlabs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/formlabs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Formlabs Web API (Dashboard) - Prints

List and search prints across the account or by printer, filterable by date, material, name, status, and machine type, with full job metadata such as volume, layer count, duration, material, and consumables used.

- **Human URL:** [https://formlabs-dashboard-api-resources.s3.amazonaws.com/formlabs-web-api-latest.html](https://formlabs-dashboard-api-resources.s3.amazonaws.com/formlabs-web-api-latest.html)
- **Base URL:** `https://api.formlabs.com/developer/v1`

#### Tags

- Prints
- Jobs
- History

#### Properties

- [Documentation](https://support.formlabs.com/s/topic/Developer-Portal)
- [API Reference](https://formlabs-dashboard-api-resources.s3.amazonaws.com/formlabs-web-api-latest.html)
- [OpenAPI](openapi/formlabs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/formlabs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/formlabs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Formlabs Web API (Dashboard) - Consumables

List resin tanks and cartridges associated with the account, including material type, dispensed and remaining volume, layer/print-time usage, and the printer each consumable is connected to.

- **Human URL:** [https://formlabs-dashboard-api-resources.s3.amazonaws.com/formlabs-web-api-latest.html](https://formlabs-dashboard-api-resources.s3.amazonaws.com/formlabs-web-api-latest.html)
- **Base URL:** `https://api.formlabs.com/developer/v1`

#### Tags

- Tanks
- Cartridges
- Materials

#### Properties

- [Documentation](https://support.formlabs.com/s/topic/Developer-Portal)
- [API Reference](https://formlabs-dashboard-api-resources.s3.amazonaws.com/formlabs-web-api-latest.html)
- [OpenAPI](openapi/formlabs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/formlabs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/formlabs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Formlabs Web API (Dashboard) - Events

Poll the account event history (print started/finished, errors, consumable changes) filterable by printer, cartridge, tank, print run, type, and date range. Delivered as a paginated REST feed; no push webhooks are documented.

- **Human URL:** [https://formlabs-dashboard-api-resources.s3.amazonaws.com/formlabs-web-api-latest.html](https://formlabs-dashboard-api-resources.s3.amazonaws.com/formlabs-web-api-latest.html)
- **Base URL:** `https://api.formlabs.com/developer/v1`

#### Tags

- Events
- Notifications
- Polling

#### Properties

- [Documentation](https://support.formlabs.com/s/topic/Developer-Portal)
- [API Reference](https://formlabs-dashboard-api-resources.s3.amazonaws.com/formlabs-web-api-latest.html)
- [OpenAPI](openapi/formlabs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/formlabs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/formlabs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Formlabs Web API (Dashboard) - Groups

Create, update, and delete printer groups, move printers between groups, manage group memberships and invitations, and list each group's print queue.

- **Human URL:** [https://formlabs-dashboard-api-resources.s3.amazonaws.com/formlabs-web-api-latest.html](https://formlabs-dashboard-api-resources.s3.amazonaws.com/formlabs-web-api-latest.html)
- **Base URL:** `https://api.formlabs.com/developer/v1`

#### Tags

- Groups
- Queue
- Access Control

#### Properties

- [Documentation](https://support.formlabs.com/s/topic/Developer-Portal)
- [API Reference](https://formlabs-dashboard-api-resources.s3.amazonaws.com/formlabs-web-api-latest.html)
- [OpenAPI](openapi/formlabs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/formlabs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/formlabs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Formlabs Local API (PreFormServer)

Local-network REST API served by the PreFormServer application for automating job preparation (import, auto-orient, auto-support, auto-layout, hollow, label), scene management, print-time estimation, and sending jobs to a printer or Fleet Control without launching the PreForm GUI.

- **Human URL:** [https://formlabs-dashboard-api-resources.s3.amazonaws.com/formlabs-local-api-latest.html](https://formlabs-dashboard-api-resources.s3.amazonaws.com/formlabs-local-api-latest.html)
- **Base URL:** `http://localhost`

#### Tags

- Local API
- PreForm
- Job Preparation

#### Properties

- [Documentation](https://formlabs.my.site.com/customerV2/s/article/Formlabs-Local-API)
- [API Reference](https://formlabs-dashboard-api-resources.s3.amazonaws.com/formlabs-local-api-latest.html)
- [SDK](https://github.com/Formlabs/formlabs-api-python)

## Common Properties

- [GitHub Organization](https://github.com/Formlabs)
- [LinkedIn](https://www.linkedin.com/company/formlabs)
- [Website](https://formlabs.com)
- [Developer Platform](https://formlabs.com/materials/developer-platform/)
- [Documentation](https://support.formlabs.com/s/topic/Developer-Portal)
- [Plans](plans/formlabs-plans-pricing.yml)
- [Rate Limits](rate-limits/formlabs-rate-limits.yml)
- [Fin Ops](finops/formlabs-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
