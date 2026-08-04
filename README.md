# SAP America

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

**Type:** Company (US subsidiary)
**Parent:** [`sap`](https://github.com/api-evangelist/sap) — SAP SE, Walldorf, Germany
**Tier:** 3 (`no-apis` — subsidiary surface, all API artifacts live in the parent repo)
**US Headquarters:** Newtown Square, Pennsylvania
**Profiled:** 2026-05

## What this repo is

SAP America, Inc. is the US operating subsidiary of SAP SE and the
Americas headquarters for the SAP enterprise software portfolio. This
repository exists as a thin subsidiary placeholder so the API Evangelist
network can cross-link US-specific surfaces — partnership, public-sector
procurement, FedRAMP / GovCloud workloads — back to the parent SAP
profile without duplicating API artifacts.

**There is no SAP-America-specific developer portal.** All API
documentation, OpenAPI specs, SDKs, capabilities, plans, rate limits,
and FinOps artifacts are catalogued under the sibling repos listed
below.

## Cross-references

### Parent
- [`sap`](https://github.com/api-evangelist/sap) — global SAP SE profile,
  api.sap.com, Business Accelerator Hub, BTP, S/4HANA, SuccessFactors,
  AI Core, Business One Service Layer.

### Related US-only subsidiary
- **SAP NS2 (SAP National Security Services)** — independent US
  subsidiary serving federal civilian, DoD, and Intelligence Community
  customers from three cloud environments (CIE / DoD / CRE). Tracked as
  an API entry in [`apis.yml`](./apis.yml). If a dedicated `sap-ns2`
  repo is later created, the entry should move there.

### Sibling product repos (global, surfaced inside the US through SAP America)
- [`sap-business-technology-platform`](https://github.com/api-evangelist/sap-business-technology-platform)
- [`sap-api-management`](https://github.com/api-evangelist/sap-api-management)
- [`sap-integration-suite`](https://github.com/api-evangelist/sap-integration-suite)
- [`sap-successfactors`](https://github.com/api-evangelist/sap-successfactors)
- [`sap-ariba`](https://github.com/api-evangelist/sap-ariba)
- [`sap-concur`](https://github.com/api-evangelist/sap-concur)
- [`sap-fieldglass`](https://github.com/api-evangelist/sap-fieldglass)

## US-specific surfaces of note

| Surface | URL |
|---|---|
| US homepage | https://www.sap.com/usa/index.html |
| Americas office locations | https://www.sap.com/about/company/office-locations/north-america.html |
| US careers | https://jobs.sap.com/?locale=en_US |
| Partner finder (PartnerEdge) | https://partneredge.sap.com/en/partnership/sales/find-partner.html |
| Trust center | https://www.sap.com/about/trust-center.html |
| SAP NS2 (US federal subsidiary) | https://sapns2.com/ |

## Why no OpenAPI / capabilities / plans here

Per the API Evangelist pipeline's no-empty-artifact rule, this repo
intentionally omits:

- `openapi/`, `asyncapi/`, `json-schema/`, `json-structure/`, `json-ld/`
- `examples/`, `capabilities/`, `rules/`, `vocabulary/`
- `plans/`, `rate-limits/`, `finops/`

All of those live under the parent [`sap`](https://github.com/api-evangelist/sap)
repository or under per-product sibling repos. Creating placeholder
duplicates here would fragment the registry and break the parent-repo
contract.

## Sources

- Wikipedia, "SAP" — corroborates Newtown Square, PA Americas HQ and
  ~19,311 US employees.
- Wikipedia, "SAP NS2" — corroborates NS2 as an independent US
  subsidiary headquartered in Pennsylvania, three cloud environments
  (CIE / DoD / CRE), and partnerships with AWS, Microsoft Azure, and
  Google Cloud.
- SAP corporate pages returned HTTP 403 to automated fetches at the time
  of this pipeline run; all SAP-domain URLs above are recorded as
  references rather than as fetched, quoted content.

## Maintainer

Kin Lane, API Evangelist — <info@apievangelist.com> — <https://apievangelist.com>
