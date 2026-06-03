# OpenMenu

OpenMenu — **structured menu data and publishing API built on the OpenMenu Format.**

OpenMenu provides structured restaurant and menu data through a public REST API (v2.2) built on the open OpenMenu Format specification. Standard endpoints cover search, restaurant profiles, location listings, deals, and ingredients, returning menu items with prices, locations, dietary attributes (vegetarian, vegan, kosher, halal, gluten-free), and allergen information. An Enhanced enterprise tier adds DishDNA machine-learning analysis, trends, heatmaps, and gap analysis.

- **Website:** https://openmenu.com/
- **API:** https://openmenu.com/api/
- **Documentation:** https://www.openmenu.com/api/docs/
- **Base URL:** `https://www.openmenu.com/api/v2/`
- **Authentication:** API key passed as the `key` query parameter (no Bearer token / custom header)
- **Sandbox:** `s=sample` or `id=sample` returns fixed sample JSON without consuming credits

## APIs

| API | Description |
|---|---|
| OpenMenu API | Standard endpoints: search, restaurant, location, deals, ingredients. |
| OpenMenu Enhanced API | DishDNA enterprise tier: analysis, trends, heatmap, gap_analysis (requires `enterprise_access`). |

## Endpoints

| Operation | Method | Path | Tier |
|---|---|---|---|
| Search Restaurants And Menu Items | GET | `/search.php` | Standard |
| Get Restaurant Profile | GET | `/restaurant.php` | Standard |
| List Restaurants By Location | GET | `/location.php` | Standard |
| Get Restaurant Deals | GET | `/deals.php` | Standard |
| Search Ingredient Database | GET | `/ingredients.php` | Standard |
| Get Menu Trends | GET | `/trends.php` | Enhanced |
| Get Menu Gap Analysis | GET | `/gap_analysis.php` | Enhanced |

## Artifacts

| Type | Location |
|---|---|
| OpenAPI 3.1 | [`openapi/openmenu-openapi.yml`](openapi/openmenu-openapi.yml) |
| JSON Schema | [`json-schema/`](json-schema/) — restaurant, menu, menu item |
| JSON Structure | [`json-structure/`](json-structure/) — menu item |
| JSON-LD context | [`json-ld/openmenu-context.jsonld`](json-ld/openmenu-context.jsonld) — schema.org Restaurant/Menu/MenuItem mapping |
| Examples | [`examples/`](examples/) — restaurant profile, search |
| Spectral rules | [`rules/openmenu-rules.yml`](rules/openmenu-rules.yml) |
| Naftiko capabilities | [`capabilities/`](capabilities/) — menu discovery, menu intelligence |
| Vocabulary | [`vocabulary/openmenu-vocabulary.yml`](vocabulary/openmenu-vocabulary.yml) |
| Plans / pricing | [`plans/openmenu-plans-pricing.yml`](plans/openmenu-plans-pricing.yml) |
| Rate limits | [`rate-limits/openmenu-rate-limits.yml`](rate-limits/openmenu-rate-limits.yml) |
| FinOps | [`finops/openmenu-finops.yml`](finops/openmenu-finops.yml) |

## Plans

| Plan | Daily Credits | Monthly Credits | Access |
|---|---|---|---|
| Free | 100 | 100 | Standard |
| Starter | 500 | 5,000 | Standard |
| Growth | 2,000 | 50,000 | Standard |
| Custom / Enterprise | Custom | Custom | Standard + Enhanced |

One successful API request consumes one credit. Sandbox calls are not metered. Additional credits sell at $0.02/credit in 2,000-credit packages.

## Notes

- There is no first-party OpenMenu GitHub organization; community wrappers exist (e.g. a Ruby parser). No official Python or Node.js SDK or MCP server was found at profiling time.
- The OpenMenu Format is the open specification underlying all menu data and maps cleanly onto schema.org Restaurant / Menu / MenuSection / MenuItem.

---

Maintained by [Kin Lane](mailto:kin@apievangelist.com) as part of [API Evangelist](https://apievangelist.com).
