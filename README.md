# Craft CMS (craft-cms)

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

Craft CMS is a flexible, self-hosted PHP content management system built on Yii 2, designed for creating bespoke digital experiences. It features an auto-generated GraphQL API for headless implementations and an Element API plugin providing configurable JSON REST endpoints for any element type including entries, assets, categories, and custom fields.

APIs.json: [https://raw.githubusercontent.com/api-evangelist/craft-cms/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/craft-cms/refs/heads/main/apis.yml)

Naftiko: [https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=craft-cms-api-evangelist&utm_content=repo](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=craft-cms-api-evangelist&utm_content=repo)

## Tags

- CMS
- Content Management
- GraphQL
- REST
- Headless
- PHP

## APIs

| Name | Description | Docs |
|------|-------------|------|
| Craft CMS GraphQL API | Auto-generated GraphQL API for querying content via schema-based bearer token access | [Docs](https://craftcms.com/docs/5.x/development/graphql.html) |
| Craft CMS Element API | Official plugin providing configurable JSON REST endpoints for any element type | [Docs](https://github.com/craftcms/element-api) |

## Plans / Rate Limits / FinOps

- [Plans & Pricing](plans/craft-cms-plans-pricing.yml) — Solo (free), Team ($279/project), Pro ($399/project), Enterprise (custom)
- [Rate Limits](rate-limits/craft-cms-rate-limits.yml) — No built-in limits; Rate Limit plugin default: 4000 req/min per IP; HTTP 429 on throttle
- [FinOps](finops/craft-cms-finops.yml) — Perpetual per-project license with optional $99/year update renewals

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | https://craftcms.com |
| Documentation | https://craftcms.com/docs/5.x/ |
| GitHub Organization | https://github.com/craftcms |
| LinkedIn | https://www.linkedin.com/company/craftcms |
| X / Twitter | https://twitter.com/craftcms |
| Blog | https://craftcms.com/blog |
| Pricing | https://craftcms.com/pricing |
| Status Page | https://status.craftcms.com/ |

## Maintainers

- Kin Lane / kin@apievangelist.com
