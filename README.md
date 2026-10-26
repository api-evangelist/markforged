# Markforged (markforged)

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
