# OpenMenu (openmenu)

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

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/openmenu/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/openmenu/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Restaurant
- Menus
- Menu Data
- Search
- Nutrition
- Structured Data

## Timestamps

- **Created:** 2026-06-02
- **Modified:** 2026-06-03

## APIs

### OpenMenu API

The OpenMenu REST API returns structured restaurant and menu data built on the OpenMenu Format. Standard endpoints include search, restaurant, location, deals, and ingredients, returning menu items with prices, locations, and dietary attributes. An Enhanced enterprise tier adds DishDNA ML-driven analysis, trends, heatmaps, and gap analysis. Authentication uses an API key, with a sandbox mode for sample data.

- **Human URL:** [https://openmenu.com/api/](https://openmenu.com/api/)
- **Base URL:** `https://www.openmenu.com/api/v2/`

#### Tags

- Menus
- Search
- Restaurants
- Nutrition

#### Properties

- [Documentation](https://www.openmenu.com/api/docs/)
- [Getting Started](https://www.openmenu.com/api/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/openmenu/refs/heads/main/openapi/openmenu-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/openmenu/refs/heads/main/json-schema/openmenu-restaurant-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/openmenu/refs/heads/main/json-schema/openmenu-menu-item-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/openmenu/refs/heads/main/json-ld/openmenu-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Authentication](https://www.openmenu.com/api/docs/authentication.php)
- [Rate Limits](https://www.openmenu.com/api/docs/rate-limiting.php)
- [Plans](https://raw.githubusercontent.com/api-evangelist/openmenu/refs/heads/main/plans/openmenu-plans-pricing.yml)
- [Rate Limits Artifact](https://raw.githubusercontent.com/api-evangelist/openmenu/refs/heads/main/rate-limits/openmenu-rate-limits.yml)
- [Fin Ops](https://raw.githubusercontent.com/api-evangelist/openmenu/refs/heads/main/finops/openmenu-finops.yml)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/openmenu/refs/heads/main/vocabulary/openmenu-vocabulary.yml)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/openmenu/refs/heads/main/rules/openmenu-rules.yml)
- [Postman Collection](collections/openmenu.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openmenu.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenMenu Enhanced API

The OpenMenu Enhanced API is an enterprise tier powered by DishDNA machine learning, offering analysis_search, analysis, trends, heatmap, menu and menu_items taxonomy searches, and gap_analysis for competitive menu modeling and regional trend identification across structured menu data.

- **Human URL:** [https://openmenu.com/api/](https://openmenu.com/api/)
- **Base URL:** `https://www.openmenu.com/api/v2/`

#### Tags

- Analytics
- Trends
- Menus

#### Properties

- [Documentation](https://www.openmenu.com/api/docs/)
- [Postman Collection](collections/openmenu.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openmenu.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://openmenu.com/)
- [Documentation](https://www.openmenu.com/api/docs/)
- [API Reference](https://openmenu.com/api/)
- [Sign Up](https://www.openmenu.com/signup.php?at=developer)
- [Authentication](https://www.openmenu.com/api/docs/authentication.php)
- [Rate Limits](https://www.openmenu.com/api/docs/rate-limiting.php)
- [Terms of Service](https://www.openmenu.com/tos-api.php)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
