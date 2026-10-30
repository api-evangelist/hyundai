# Hyundai

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

Hyundai Motor Company is a South Korean multinational automotive manufacturer and, through Hyundai Developers, the operator of a connected-car data platform for third-party developers. The platform exposes the Hyundai integrated account over OAuth 2.0 and serves nineteen documented REST operations covering user profile, vehicle list, connected-service contract dates, odometer, distance-to-empty, EV battery and charging state, and seven warning-light indicators, sourced from vehicles enrolled in Bluelink. Access is governed by a two-stage consent model built around the Korean Personal Information Protection Act — a per-vehicle OAuth consent plus a separate third-party data-provision consent — and a manual commercialization review before any real customer vehicle data is released. The API reference, a public sample-test tier with fixture vehicles, and the developer guide are all readable without an account; data is limited to vehicles in South Korea.

**Areas:** Automobiles · Cars · Connected Vehicles · Mobility · Vehicles · Automotive · Telematics · Electric Vehicles · Vehicle Data · South Korea

## Hyundai on APIs.io

Everything profiled for Hyundai is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/hyundai/](https://apis.io/providers/hyundai/)** — or go straight to one of the APIs or properties below.

### APIs (1)

- [Hyundai Developers Connected Car API](https://apis.io/apis/hyundai/hyundai-developer-api/) — Hyundai Developers exposes connected-car data from Bluelink-enrolled vehicles to third-party services over a REST API on prd.kr-ccapi.hyundai.com. Nineteen…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Hyundai Webhooks](https://apis.io/asyncapis/hyundai/hyundai-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [hyundai-mcp.yml](https://apis.io/servers/hyundai/hyundai-mcp-yml/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Hyundai Authentication](https://apis.io/security/hyundai/hyundai-authentication/)
- [Hyundai Domain Security](https://apis.io/security/hyundai/hyundai-domain-security/)
- [Hyundai Vulnerability Disclosure](https://apis.io/security/hyundai/hyundai-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Hyundai Plans Pricing](https://apis.io/plans/hyundai/hyundai-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Hyundai Rate Limits](https://apis.io/rate-limits/hyundai/hyundai-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Hyundai Finops](https://apis.io/finops/hyundai/hyundai-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.hyundai.com/)
- [Documentation](https://developers.hyundai.com/web/v1/hyundai/data_api)
- [Getting started](https://developers.hyundai.com/web/v1/hyundai/guide_developers)
- [API reference](https://developers.hyundai.com/web/v1/hyundai/specification/account)
- [Sign up](https://console.developers.hyundai.com/)
- [Support](https://developers.hyundai.com/web/v1/hyundai/tech_support)
- [Terms of service](https://developers.hyundai.com/web/v1/hyundai/terms_of_use)
- [Privacy policy](https://privacy.hyundai.com/overview/full-policy)

## API Evangelist rating

**Kin Score 46.9** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 74.1 |
| Contract quality | 45.3 |
| Contract governance | 18.2 |
| Operational transparency | 55.3 |
| Developer ergonomics | 61.9 |
| Access clarity | 23.7 |

**Agent readiness 29.3** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | yes |
| Agent Skills | — |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 26.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/hyundai/](https://apis.io/providers/hyundai/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Hyundai: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/hyundai/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
