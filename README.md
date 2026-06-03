# Edamam (edamam)

Edamam is a leading provider of nutrition data and analytics. They offer
nutrition analysis, food database, recipe search, and meal planning APIs that
power thousands of health, fitness, and food apps. Their databases contain
close to 900,000 foods, over 2 million recipes, and comprehensive nutritional
information.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-search/edamam/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

- Restaurant
- Food
- Nutrition
- UPC

## Timestamps

- **Created:** 2024-11-13
- **Modified:** 2026-06-02

## APIs

### Edamam Nutrition Analysis API

The Edamam Nutrition Analysis API provides detailed nutrition data for recipes
and food items. Send a recipe or food description and receive comprehensive
nutritional information including calories, macros, and micronutrients.

**Human URL:** [https://developer.edamam.com/edamam-docs-nutrition-api](https://developer.edamam.com/edamam-docs-nutrition-api)

**Base URL:** https://api.edamam.com

#### Tags

- Food
- Health
- Nutrition

#### Properties

- [Documentation](https://developer.edamam.com/edamam-docs-nutrition-api)
- [Pricing](https://developer.edamam.com/edamam-nutrition-api)
- [OpenAPI](openapi/edamam-nutrition-analysis-api-openapi.yml)
- [NaftikoCapability](capabilities/nutrition-analysis-api-nutrition-analysis.yaml)

### Edamam Food and Grocery Database API

The Edamam Food and Grocery Database API provides access to a database of
close to 900,000 foods and over 680,000 unique UPC codes with full nutritional
information.

**Human URL:** [https://developer.edamam.com/food-database-api-docs](https://developer.edamam.com/food-database-api-docs)

**Base URL:** https://api.edamam.com

#### Tags

- Food
- Grocery
- Nutrition

#### Properties

- [Documentation](https://developer.edamam.com/food-database-api-docs)
- [Pricing](https://developer.edamam.com/food-database-api)
- [OpenAPI](openapi/edamam-food-and-grocery-database-api-openapi.yml)
- [NaftikoCapability](capabilities/food-and-grocery-database-api-food-database.yaml)

### Edamam Recipe Search API

The Edamam Recipe Search API provides access to over 2 million recipes with
full nutritional analysis, diet and health labels, ingredient details, and
cuisine type.

**Human URL:** [https://developer.edamam.com/edamam-docs-recipe-api](https://developer.edamam.com/edamam-docs-recipe-api)

**Base URL:** https://api.edamam.com

#### Tags

- Food
- Nutrition
- Recipes

#### Properties

- [Documentation](https://developer.edamam.com/edamam-docs-recipe-api)
- [Pricing](https://developer.edamam.com/edamam-recipe-api)
- [OpenAPI](openapi/edamam-recipe-search-api-openapi.yml)
- [NaftikoCapability](capabilities/recipe-search-api-recipe-search.yaml)

### Edamam Meal Planner API

The Edamam Meal Planner API provides personalized meal planning capabilities
based on dietary preferences, nutrition goals, and available ingredients.

**Human URL:** [https://developer.edamam.com/edamam-docs-meal-planner-api](https://developer.edamam.com/edamam-docs-meal-planner-api)

**Base URL:** https://api.edamam.com

#### Tags

- Food
- Meal Planning
- Nutrition

#### Properties

- [Documentation](https://developer.edamam.com/edamam-docs-meal-planner-api)
- [Pricing](https://developer.edamam.com/meal-planner-api)
- [OpenAPI](openapi/edamam-meal-planner-api-openapi.yml)
- [NaftikoCapability](capabilities/meal-planner-api-meal-planner.yaml)

## Common Properties

- [GitHubOrganization](https://github.com/edamam)
- [LinkedIn](https://www.linkedin.com/company/edamam)
- [Tools (MCP Server — Food Database)](https://github.com/edamam-llc/mcp-edamam-food)
- [Tools (Edamam Food MCP)](https://developer.edamam.com/mcp-edamam-food)
- [CodeExamples (Java Demo)](https://github.com/edamam-llc/edamam-api-demo)
- [Spectral Rules](rules/edamam-spectral-rules.yml)
- [Vocabulary](vocabulary/edamam-vocabulary.yaml)
- [Plans](plans/edamam-plans-pricing.yml)
- [RateLimits](rate-limits/edamam-rate-limits.yml)
- [FinOps](finops/edamam-finops.yml)
- [FAQ](https://developer.edamam.com/api/faq)
- [Attribution](https://developer.edamam.com/attribution)
- [DataLicensing](https://www.edamam.com/data-licensing/)
- [Partners](https://www.edamam.com/partners/)
- [Portal](https://www.edamam.com/)
- [PrivacyPolicy](https://www.edamam.com/privacy/)
- [TermsOfService](https://www.edamam.com/terms/api/)

## Tools (MCP Servers & Skills)

| Type | Name | URL |
|------|------|-----|
| MCP Server | Edamam Food MCP | [edamam-llc/mcp-edamam-food](https://github.com/edamam-llc/mcp-edamam-food) |

The official Edamam Food MCP exposes the Food Database and Vision capabilities as
LLM-friendly tools (`get_food_nutrition`, `analyze_food_image`) over Streamable
HTTP / JSON-RPC 2.0 at `https://mcp.edamam.com/mcp/food`.

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Edamam Nutrition Analysis API](openapi/edamam-nutrition-analysis-api-openapi.yml)
- [Edamam Food and Grocery Database API](openapi/edamam-food-and-grocery-database-api-openapi.yml)
- [Edamam Recipe Search API](openapi/edamam-recipe-search-api-openapi.yml)
- [Edamam Meal Planner API](openapi/edamam-meal-planner-api-openapi.yml)

### JSON Schema

19 JSON Schema files in [`json-schema/`](json-schema/) extracted from the OpenAPI component schemas across all four APIs.

### JSON Structure

19 JSON Structure files in [`json-structure/`](json-structure/) converted from the JSON Schema files.

### JSON-LD

- [Nutrition Analysis Context](json-ld/edamam-nutrition-analysis-api-context.jsonld)
- [Food Database Context](json-ld/edamam-food-and-grocery-database-api-context.jsonld)
- [Recipe Search Context](json-ld/edamam-recipe-search-api-context.jsonld)
- [Meal Planner Context](json-ld/edamam-meal-planner-api-context.jsonld)

### Examples

19 example payloads in [`examples/`](examples/), one per JSON Schema.

## Capabilities

Self-contained Naftiko capabilities, one per API business surface, each
declaring both a REST and an MCP exposer routed through an inline consumes block.

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Nutrition Analysis](capabilities/nutrition-analysis-api-nutrition-analysis.yaml) | Edamam Nutrition Analysis API | 2 | Nutrition Analyst |
| [Food Database](capabilities/food-and-grocery-database-api-food-database.yaml) | Edamam Food and Grocery Database API | 2 | Grocery App Builder |
| [Recipe Search](capabilities/recipe-search-api-recipe-search.yaml) | Edamam Recipe Search API | 2 | Recipe App Builder |
| [Meal Planner](capabilities/meal-planner-api-meal-planner.yaml) | Edamam Meal Planner API | 1 | Wellness Coach |

## Vocabulary

- [Edamam Vocabulary](vocabulary/edamam-vocabulary.yaml) — Unified taxonomy mapping 4 resources, 5 actions, 4 workflows, and 5 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Plans, Rate Limits & FinOps

- [Plans & Pricing](plans/edamam-plans-pricing.yml) — Prepaid Enterprise tiers (Basic $14, Core $69, Plus $299) plus a custom Unlimited tier, API Commons Plans 0.1
- [Rate Limits](rate-limits/edamam-rate-limits.yml) — Per-tier, per-category request-rate and monthly-quota limits, API Commons Rate Limits 0.1
- [FinOps](finops/edamam-finops.yml) — FOCUS-aligned tiered-subscription + pay-as-you-go billing model

## Rules

- [Edamam Spectral Rules](rules/edamam-spectral-rules.yml) — 39 rules across 13 categories enforcing Edamam API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
