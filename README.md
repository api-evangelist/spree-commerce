# Spree Commerce

Spree Commerce is an open-source headless eCommerce platform originally released in 2007 and built on Ruby on Rails. The Spree server exposes a modern Store API (v3), an Admin API (v3), a Platform API (v2), and a JSON:API-compliant Storefront API (v2) — all described with OpenAPI 3 — plus an OAuth 2.0 token endpoint for authentication, and a webhooks event system for downstream integrations. Spree ships with a TypeScript Store SDK and Admin SDK, a CLI, a `create-spree-app` scaffolder, a Next.js storefront, a Rails storefront, official payment integrations (Stripe, Adyen, PayPal), tax (Avalara/AvaTax), marketing (Klaviyo, Google Analytics), and the `spree_multi_vendor` marketplace extension.

- Website: https://spreecommerce.org/
- Documentation: https://dev-docs.spreecommerce.org/
- API Reference: https://dev-docs.spreecommerce.org/api-reference/introduction
- GitHub: https://github.com/spree
- Core Repository: https://github.com/spree/spree
- Pricing: https://spreecommerce.org/pricing/
- Demo: https://demo.spreecommerce.org/
- Releases: https://github.com/spree/spree/releases

## APIs and Components

- `spree-commerce:store-api` — Spree Store API v3 (modern REST for storefronts)
- `spree-commerce:admin-api` — Spree Admin API v3 (administrative REST)
- `spree-commerce:platform-api` — Spree Platform API v2 (full platform REST, OAuth 2.0)
- `spree-commerce:storefront-api` — Spree Storefront API v2 (JSON:API REST)
- `spree-commerce:oauth-api` — Spree OAuth 2.0 token endpoint
- `spree-commerce:webhooks` — Spree Webhooks (signed JSON event delivery)
- `spree-commerce:sdk` — `@spree/sdk` (TypeScript Store API SDK)
- `spree-commerce:admin-sdk` — `@spree/admin-sdk` (TypeScript Admin API SDK)
- `spree-commerce:cli` — `@spree/cli`
- `spree-commerce:create-spree-app` — `create-spree-app` scaffolder
- `spree-commerce:nextjs-storefront` — Next.js Storefront
- `spree-commerce:rails-storefront` — Rails Storefront with page builder
- `spree-commerce:starter` — `spree-starter` application template
- `spree-commerce:multi-vendor` — `spree_multi_vendor` marketplace extension
- `spree-commerce:multi-store` — `spree-multi-store` extension
- `spree-commerce:stripe` — `spree_stripe` integration
- `spree-commerce:adyen` — `spree_adyen` integration
- `spree-commerce:paypal-checkout` — `spree_paypal_checkout` integration
- `spree-commerce:avatax` — `spree_avatax_official` integration
- `spree-commerce:klaviyo` — `spree_klaviyo` integration
- `spree-commerce:google-analytics` — `spree_google_analytics` integration
- `spree-commerce:extension` — `spree_extension` generator CLI
- `spree-commerce:dev-tools` — `spree_dev_tools`
- `spree-commerce:deface` — `deface` Rails view customization
- `spree-commerce:core-repo` — `spree/spree` monorepo

## Profile Artifacts

| Artifact | Path |
|---|---|
| API index | [`apis.yml`](apis.yml) |
| OpenAPI — Store API v3 | [`openapi/spree-commerce-store-api-openapi.yml`](openapi/spree-commerce-store-api-openapi.yml) |
| OpenAPI — Admin API v3 | [`openapi/spree-commerce-admin-api-openapi.yml`](openapi/spree-commerce-admin-api-openapi.yml) |
| OpenAPI — Platform API v2 | [`openapi/spree-commerce-platform-api-openapi.yml`](openapi/spree-commerce-platform-api-openapi.yml) |
| OpenAPI — Storefront API v2 (JSON:API) | [`openapi/spree-commerce-storefront-api-openapi.yml`](openapi/spree-commerce-storefront-api-openapi.yml) |
| OpenAPI — OAuth | [`openapi/spree-commerce-oauth-api-openapi.yml`](openapi/spree-commerce-oauth-api-openapi.yml) |
| Plans / Pricing (API Commons Plans 0.1) | [`plans/spree-commerce-plans-pricing.yml`](plans/spree-commerce-plans-pricing.yml) |
| Rate Limits (API Commons Rate Limits 0.1) | [`rate-limits/spree-commerce-rate-limits.yml`](rate-limits/spree-commerce-rate-limits.yml) |
| FinOps (FOCUS-aligned) | [`finops/spree-commerce-finops.yml`](finops/spree-commerce-finops.yml) |

## Type

`opensource` — Spree's core is BSD-3-Clause licensed open-source software with a commercial Spree Enterprise / Spree Cloud offering. This profile follows the GitHub-first open-source pipeline; commercial artifacts (plans, rate limits, FinOps) are scaffolded for the Enterprise / Cloud tier and reconciled against the published terms on https://spreecommerce.org/pricing/.

## References

Profiled with assistance from Anthropic's Claude under the API Evangelist research pipeline — https://www.anthropic.com/
