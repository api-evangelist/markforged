# Markforged (markforged)

Markforged builds industrial additive manufacturing systems - composite (FX, Onyx, X-series) and metal (Metal X, PX100) 3D printers - managed through the Eiger cloud software platform. The Eiger API (V3) exposes a REST interface over HTTP Basic Auth for managing devices, builds, print jobs, and parts, letting customers integrate Markforged additive workflows into ERP, MES, PLM, and other factory systems. Digital Source extends the platform with secure, licensed distribution of manufacturer-certified parts for distributed manufacturing.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/markforged/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/markforged/refs/heads/main/apis.yml)

## Tags

- 3D Printing
- Additive Manufacturing
- Industrial
- Eiger
- Fleet Management

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Eiger Devices API

Lists Markforged printers (devices) in an Eiger organization, reads device state, sends builds to a printer, and manages each device's print queue.

- **Human URL:** [https://www.eiger.io/developer/spec](https://www.eiger.io/developer/spec)
- **Base URL:** `https://www.eiger.io/api/v3`

#### Tags

- Devices
- Printers
- Fleet

#### Properties

- [Documentation](https://www.eiger.io/developer)
- [API Reference](https://www.eiger.io/developer/spec)
- [OpenAPI](openapi/markforged-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/markforged.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/markforged.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Eiger Builds API

Lists and retrieves builds, manages the approved-builds list, and routes builds to the backlog or the job-request queue for production.

- **Human URL:** [https://www.eiger.io/developer/spec](https://www.eiger.io/developer/spec)
- **Base URL:** `https://www.eiger.io/api/v3`

#### Tags

- Builds
- Approvals
- Job Requests

#### Properties

- [Documentation](https://www.eiger.io/developer)
- [API Reference](https://www.eiger.io/developer/spec)
- [OpenAPI](openapi/markforged-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/markforged.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/markforged.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Eiger Print Jobs API

Lists print jobs and retrieves print job details and scan report URLs for in-process inspection and traceability.

- **Human URL:** [https://www.eiger.io/developer/spec](https://www.eiger.io/developer/spec)
- **Base URL:** `https://www.eiger.io/api/v3`

#### Tags

- Print Jobs
- Production
- Scan Reports

#### Properties

- [Documentation](https://www.eiger.io/developer)
- [API Reference](https://www.eiger.io/developer/spec)
- [OpenAPI](openapi/markforged-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/markforged.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/markforged.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Eiger Parts API

Retrieves parts and part versions, uploads STL files, checks slice job status, downloads part versions, and lists organization settings presets.

- **Human URL:** [https://www.eiger.io/developer/spec](https://www.eiger.io/developer/spec)
- **Base URL:** `https://www.eiger.io/api/v3`

#### Tags

- Parts
- STL Upload
- Slicing

#### Properties

- [Documentation](https://www.eiger.io/developer)
- [API Reference](https://www.eiger.io/developer/spec)
- [OpenAPI](openapi/markforged-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/markforged.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/markforged.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Eiger Printed Parts API

Lists physically printed parts, retrieves printed part details, and fetches per-printed-part scan reports for the additive digital inventory.

- **Human URL:** [https://www.eiger.io/developer/spec](https://www.eiger.io/developer/spec)
- **Base URL:** `https://www.eiger.io/api/v3`

#### Tags

- Printed Parts
- Inventory
- Scan Reports

#### Properties

- [Documentation](https://www.eiger.io/developer)
- [API Reference](https://www.eiger.io/developer/spec)
- [OpenAPI](openapi/markforged-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/markforged.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/markforged.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Eiger Organizations API

Lists and retrieves users scoped to the Eiger organization and exports custom analytics CSV from the dashboard for organization-level reporting.

- **Human URL:** [https://www.eiger.io/developer/spec](https://www.eiger.io/developer/spec)
- **Base URL:** `https://www.eiger.io/api/v3`

#### Tags

- Organizations
- Users
- Analytics

#### Properties

- [Documentation](https://www.eiger.io/developer)
- [API Reference](https://www.eiger.io/developer/spec)
- [OpenAPI](openapi/markforged-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/markforged.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/markforged.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Markforged Digital Source

Secure, licensed distribution of manufacturer-certified parts for distributed (point-of-need) manufacturing. Built on the Markforged platform (ISO 27001 certified); no separate public developer API is documented as of this catalog date - integration is via the Eiger platform and partner arrangements.

- **Human URL:** [https://markforged.com/management-integration](https://markforged.com/management-integration)

#### Tags

- Digital Source
- Distributed Manufacturing
- Licensing

#### Properties

- [Documentation](https://markforged.com/management-integration)

## Common Properties

- [GitHub Organization](https://github.com/MarkForged)
- [LinkedIn](https://www.linkedin.com/company/markforged)
- [Website](https://markforged.com)
- [Documentation](https://www.eiger.io/developer)
- [Plans](plans/markforged-plans-pricing.yml)
- [Rate Limits](rate-limits/markforged-rate-limits.yml)
- [Fin Ops](finops/markforged-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
