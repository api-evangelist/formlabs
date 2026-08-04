# Formlabs (formlabs)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
