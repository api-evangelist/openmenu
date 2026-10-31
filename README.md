# OpenMenu

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

OpenMenu provides structured menu data and menu publishing for restaurants, built on the open OpenMenu Format specification. Its public REST API helps developers locate restaurants, menus, and menu items, returning structured data including names, descriptions, prices, locations, and dietary attributes such as vegan, vegetarian, halal, kosher, and gluten-free. The standard API covers search, restaurant, location, deals, and ingredients endpoints, while an Enhanced enterprise tier adds DishDNA machine-learning analysis, trends, heatmaps, and gap analysis. The API offers a sandbox mode (s=sample / id=sample), API key authentication via the key query parameter, and tiered pricing from a free plan up to enterprise on a daily/monthly credit model.

**Areas:** Restaurant · Menus · Menu Data · Search · Nutrition · Structured Data

## OpenMenu on APIs.io

Everything profiled for OpenMenu is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/openmenu/](https://apis.io/providers/openmenu/)** — or go straight to one of the APIs or properties below.

### APIs (6)

- [OpenMenu Enhanced API](https://apis.io/apis/openmenu/enhanced-api/) — The OpenMenu Enhanced API is an enterprise tier powered by DishDNA machine learning, offering analysis_search, analysis, trends, heatmap, menu and…
- [OpenMenu Analytics API](https://apis.io/apis/openmenu/openmenu-analytics-api/) — DishDNA machine-learning trends, heatmaps, and gap analysis (Enhanced tier).
- [OpenMenu Deals API](https://apis.io/apis/openmenu/openmenu-deals-api/) — Coupons, specials, and daily deals for a restaurant.
- [OpenMenu Ingredients API](https://apis.io/apis/openmenu/openmenu-ingredients-api/) — Ingredient database with nutrition labels, claims, and food groups.
- [OpenMenu Restaurants API](https://apis.io/apis/openmenu/openmenu-restaurants-api/) — Full restaurant profiles and geographic listings.
- [OpenMenu Search API](https://apis.io/apis/openmenu/openmenu-search-api/) — Find restaurants, menu items, and sample menus by location and term.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Openmenu Agentic Access](https://apis.io/agentic-access/openmenu/openmenu-agentic-access/)

#### JSON Schema (3)

The data models the API reads and writes.

- [OpenMenu Menu](https://apis.io/schemas/openmenu/openmenu-menu/)
- [OpenMenu Menu Item](https://apis.io/schemas/openmenu/openmenu-menu-item/)
- [OpenMenu Restaurant](https://apis.io/schemas/openmenu/openmenu-restaurant/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Openmenu Menu Item Structure](https://apis.io/json-structure/openmenu/openmenu-menu-item-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Openmenu Context](https://apis.io/jsonld/openmenu/openmenu-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Openmenu Vocabulary](https://apis.io/vocabularies/openmenu/openmenu-vocabulary/)

#### Examples (2)

Example requests and responses.

- [Openmenu Restaurant Example](https://apis.io/examples/openmenu/openmenu-restaurant-example/)
- [Openmenu Search Example](https://apis.io/examples/openmenu/openmenu-search-example/)

#### Collections (6)

Postman and Open Collection request collections.

- [OpenMenu API](https://apis.io/collections/openmenu/open-openmenu/)
- [OpenMenu Analytics API](https://apis.io/collections/openmenu/open-openmenu-analytics-api/)
- [OpenMenu Analytics Deals API](https://apis.io/collections/openmenu/open-openmenu-deals-api/)
- [OpenMenu Analytics Ingredients API](https://apis.io/collections/openmenu/open-openmenu-ingredients-api/)
- [OpenMenu Analytics Restaurants API](https://apis.io/collections/openmenu/open-openmenu-restaurants-api/)
- [OpenMenu Analytics Search API](https://apis.io/collections/openmenu/open-openmenu-search-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [OpenMenu — jsonschema rules](https://apis.io/rules/openmenu/openmenu-jsonschema-spectral-rules/)
- [OpenMenu API Rules](https://apis.io/rules/openmenu/openmenu-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Openmenu Authentication](https://apis.io/security/openmenu/openmenu-authentication/)
- [Openmenu Domain Security](https://apis.io/security/openmenu/openmenu-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Openmenu Plans Pricing](https://apis.io/plans/openmenu/openmenu-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Openmenu Rate Limits](https://apis.io/rate-limits/openmenu/openmenu-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Openmenu Finops](https://apis.io/finops/openmenu/openmenu-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://openmenu.com/)
- [Documentation](https://www.openmenu.com/api/docs/)
- [API reference](https://openmenu.com/api/)
- [Blog](https://www.openmenu.com/insights)
- [Terms of service](https://www.openmenu.com/tos-api.php)

## API Evangelist rating

**Kin Score 41.2** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 62.3 |
| Contract governance | 27.3 |
| Operational transparency | 0.0 |
| Developer ergonomics | 42.9 |
| Access clarity | 31.6 |

**Agent readiness 24.8** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 20.6** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/openmenu/](https://apis.io/providers/openmenu/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for OpenMenu: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/openmenu/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
