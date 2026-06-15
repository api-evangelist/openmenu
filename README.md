# OpenMenu (openmenu)

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
