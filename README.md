# Timoni (timoni)

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

Timoni is a package manager for Kubernetes powered by CUE that provides a type-safe alternative to Helm charts. It enables software vendors to define complex application deployments packaged as Modules using CUE definitions, distributed as OCI artifacts in container registries with semantic versioning and cryptographic signing.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/timoni/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/timoni/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** Open Source

## Tags

- Containers
- Kubernetes
- Package Manager
- CUE

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-05-19

## APIs

### Timoni Module Registry API

Timoni modules are distributed as OCI artifacts in container registries. The registry API provides operations for listing module tags, retrieving OCI manifests, and downloading module blobs containing CUE definitions and Kubernetes configurations.

- **Human URL:** [https://timoni.sh/](https://timoni.sh/)
- **Base URL:** `https://ghcr.io`

#### Tags

- Containers
- Kubernetes
- Package Manager
- OCI Registry

#### Properties

- [Documentation](https://timoni.sh/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/timoni/refs/heads/main/openapi/timoni-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [GitHub Repository](https://github.com/stefanprodan/timoni)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/timoni/refs/heads/main/json-schema/timoni-module-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/timoni/refs/heads/main/json-structure/timoni-module-structure.json)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/timoni/refs/heads/main/json-ld/timoni-context.jsonld)
- [Postman Collection](collections/timoni.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/timoni.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://timoni.sh/)
- [Documentation](https://timoni.sh/)
- [GitHub Organization](https://github.com/stefanprodan/timoni)
- [Getting Started](https://timoni.sh/quickstart/)
- [Concepts](https://timoni.sh/concepts/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/timoni/refs/heads/main/openapi/timoni-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/timoni/refs/heads/main/json-schema/timoni-module-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/timoni/refs/heads/main/json-ld/timoni-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/timoni/refs/heads/main/vocabulary/timoni-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
