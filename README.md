# Spree Commerce (spree-commerce)

Spree Commerce is an open-source headless eCommerce platform originally released in 2007 and built on Ruby on Rails. The Spree server exposes a modern Store API (v3), an Admin API (v3), a Platform API (v2) used by internal/back-office integrations, and a Storefront API (v2) based on the JSON:API spec - all described with OpenAPI 3 - plus an OAuth 2.0 token endpoint for authentication. Developer surface includes the TypeScript Store and Admin SDKs (@spree/sdk and @spree/admin-sdk), the @spree/cli for managing Spree projects, the create-spree-app scaffolder, the open-source Next.js storefront, the spree-starter application template, the spree_extension generator for building Rails extensions, the deface view-customization plugin, official payments integrations (Stripe, Adyen, PayPal), marketing integrations (Klaviyo, Google Analytics), an Avalara/AvaTax extension, the spree_multi_vendor marketplace extension, and a Webhook event system for reacting to store events.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/spree-commerce/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/spree-commerce/refs/heads/main/apis.yml)

## Tags

- Commerce
- Headless
- eCommerce
- Open Source
- Ruby on Rails
- Ruby
- TypeScript

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Spree Store API

Public Spree Store API v3 - the modern customer-facing REST API used by headless storefronts, mobile apps, and integrations. Covers products, variants, collections, taxonomies, cart and order flows, checkout, payments, account, and search. Described with OpenAPI 3.

- **Human URL:** [https://dev-docs.spreecommerce.org/api-reference/store-api/introduction](https://dev-docs.spreecommerce.org/api-reference/store-api/introduction)
- **Base URL:** `https://demo.spreecommerce.org`

#### Tags

- REST
- Storefront
- Carts
- Orders
- Products

#### Properties

- [Documentation](https://dev-docs.spreecommerce.org/api-reference/store-api/introduction)
- [OpenAPI](openapi/spree-commerce-store-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/spree-commerce-store-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-store-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](https://raw.githubusercontent.com/spree/spree/main/docs/api-reference/store.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Spree Admin API

Spree Admin API v3 - administrative REST API for managing products, orders, customers, payments, shipping, and store configuration. Authenticated via a secret API key passed in the x-spree-api-key header and used by the Spree Admin dashboard and back-office automation.

- **Human URL:** [https://dev-docs.spreecommerce.org/api-reference/admin-api/introduction](https://dev-docs.spreecommerce.org/api-reference/admin-api/introduction)
- **Base URL:** `https://demo.spreecommerce.org`

#### Tags

- REST
- Admin
- Back-Office
- Orders
- Products

#### Properties

- [Documentation](https://dev-docs.spreecommerce.org/api-reference/admin-api/introduction)
- [OpenAPI](openapi/spree-commerce-admin-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/spree-commerce-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](https://raw.githubusercontent.com/spree/spree/main/docs/api-reference/admin.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Spree Platform API

Spree Platform API v2 - the broad REST API that backs the legacy admin and platform-level integrations. Provides full CRUD coverage of the Spree data model including addresses, taxons, classifications, line items, payments, refunds, shipments, stock items, and platform configuration. Authenticated with OAuth 2.0 bearer tokens.

- **Human URL:** [https://dev-docs.spreecommerce.org/api-reference/platform-api/introduction](https://dev-docs.spreecommerce.org/api-reference/platform-api/introduction)
- **Base URL:** `https://demo.spreecommerce.org`

#### Tags

- REST
- Platform
- Admin

#### Properties

- [Documentation](https://dev-docs.spreecommerce.org/api-reference/platform-api/introduction)
- [OpenAPI](openapi/spree-commerce-platform-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/spree-commerce-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](https://raw.githubusercontent.com/spree/spree/main/docs/api-reference/platform.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Spree Storefront API (JSON:API)

Spree Storefront API v2 - the JSON:API-compliant REST API used by Spree's reference Next.js and Rails storefronts. Includes account, addresses, cart, checkout, products, taxons, orders, payments, store credits, and gift cards. Distributed as an OpenAPI 3 specification.

- **Human URL:** [https://dev-docs.spreecommerce.org/api-reference/storefront-api/introduction](https://dev-docs.spreecommerce.org/api-reference/storefront-api/introduction)
- **Base URL:** `https://demo.spreecommerce.org`

#### Tags

- REST
- JSON API
- Storefront
- Checkout

#### Properties

- [Documentation](https://dev-docs.spreecommerce.org/api-reference/storefront-api/introduction)
- [OpenAPI](openapi/spree-commerce-storefront-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/spree-commerce-storefront-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-storefront-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](https://raw.githubusercontent.com/spree/spree/main/docs/api-reference/storefront.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Spree OAuth API

OAuth 2.0 token endpoint used to create and refresh short-lived bearer tokens for the Spree Storefront, Platform, and Admin APIs. Supports password, client_credentials, and refresh_token grants on the /spree_oauth/token path.

- **Human URL:** [https://dev-docs.spreecommerce.org/api-reference/authentication](https://dev-docs.spreecommerce.org/api-reference/authentication)
- **Base URL:** `https://demo.spreecommerce.org`

#### Tags

- OAuth
- Authentication
- Tokens

#### Properties

- [Documentation](https://dev-docs.spreecommerce.org/api-reference/authentication)
- [OpenAPI](openapi/spree-commerce-oauth-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/spree-commerce-oauth-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-oauth-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](https://raw.githubusercontent.com/spree/spree/main/docs/api-reference/oauth.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Spree Webhooks

Outbound webhook event system - the Spree server emits signed JSON payloads for order, product, customer, payment, and shipment lifecycle events. The webhook envelope carries an id, event name, created_at, data, and metadata block, with payloads sharing the Store API v3 serializers.

- **Human URL:** [https://dev-docs.spreecommerce.org/api-reference/webhooks-events](https://dev-docs.spreecommerce.org/api-reference/webhooks-events)
- **Base URL:** `https://dev-docs.spreecommerce.org/api-reference/webhooks-events`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://dev-docs.spreecommerce.org/api-reference/webhooks-events)
- [Documentation](https://dev-docs.spreecommerce.org/developer/core-concepts/webhooks)
- [Postman Collection](collections/spree-commerce-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-oauth-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-oauth-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-store-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-store-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-storefront-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-storefront-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### @spree/sdk (TypeScript Store API SDK)

Official TypeScript SDK for the Spree Store API - typed clients, auth helpers, and resource methods. Distributed via npm as @spree/sdk and consumed by the Next.js storefront, custom storefronts, and server-side integrations.

- **Human URL:** [https://www.npmjs.com/package/@spree/sdk](https://www.npmjs.com/package/@spree/sdk)
- **Base URL:** `https://github.com/spree/spree/tree/main/packages/sdk`

#### Tags

- SDK
- TypeScript
- JavaScript
- Storefront

#### Properties

- [Repository](https://github.com/spree/spree/tree/main/packages/sdk)
- [Package](https://www.npmjs.com/package/@spree/sdk)
- [Postman Collection](collections/spree-commerce-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-oauth-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-oauth-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-store-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-store-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-storefront-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-storefront-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### @spree/admin-sdk (TypeScript Admin API SDK)

Official TypeScript SDK for the Spree Admin API. Provides a typed client for managing products, orders, customers, and store configuration from Node.js services and admin tools.

- **Human URL:** [https://www.npmjs.com/package/@spree/admin-sdk](https://www.npmjs.com/package/@spree/admin-sdk)
- **Base URL:** `https://github.com/spree/spree/tree/main/packages/admin-sdk`

#### Tags

- SDK
- TypeScript
- Admin

#### Properties

- [Repository](https://github.com/spree/spree/tree/main/packages/admin-sdk)
- [Package](https://www.npmjs.com/package/@spree/admin-sdk)
- [Postman Collection](collections/spree-commerce-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-oauth-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-oauth-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-store-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-store-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-storefront-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-storefront-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### @spree/cli

Command-line tool for managing Spree Commerce projects - scaffolding new apps, running the dev server, managing Docker, and orchestrating common project tasks. Installed via npm and exposed as the spree binary.

- **Human URL:** [https://www.npmjs.com/package/@spree/cli](https://www.npmjs.com/package/@spree/cli)
- **Base URL:** `https://github.com/spree/spree/tree/main/packages/cli`

#### Tags

- CLI
- Tooling
- Developer Experience

#### Properties

- [Repository](https://github.com/spree/spree/tree/main/packages/cli)
- [Package](https://www.npmjs.com/package/@spree/cli)
- [Postman Collection](collections/spree-commerce-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-oauth-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-oauth-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-store-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-store-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-storefront-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-storefront-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### create-spree-app

One-line project generator for new Spree Commerce installations - mirrors create-next-app and create-medusa-app patterns. Bootstraps a working Rails-based Spree project from the spree-starter template.

- **Human URL:** [https://www.npmjs.com/package/create-spree-app](https://www.npmjs.com/package/create-spree-app)
- **Base URL:** `https://github.com/spree/spree/tree/main/packages/create-spree-app`

#### Tags

- CLI
- Scaffolding
- Starter

#### Properties

- [Repository](https://github.com/spree/spree/tree/main/packages/create-spree-app)
- [Package](https://www.npmjs.com/package/create-spree-app)
- [Postman Collection](collections/spree-commerce-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-oauth-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-oauth-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-store-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-store-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-storefront-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-storefront-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spree Next.js Storefront

Open-source Next.js storefront talking to the Spree Storefront API - cart, checkout, account, multi-region, one-page checkout, and Stripe, Adyen, and PayPal payments. MIT licensed.

- **Human URL:** [https://github.com/spree/storefront](https://github.com/spree/storefront)
- **Base URL:** `https://github.com/spree/storefront`

#### Tags

- Storefront
- Next.js
- Starter
- TypeScript

#### Properties

- [Repository](https://github.com/spree/storefront)
- [Postman Collection](collections/spree-commerce-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-oauth-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-oauth-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-store-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-store-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-storefront-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-storefront-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spree Rails Storefront

Spree 5 storefront built with Ruby on Rails and a visual page builder. Reference implementation for teams that want a Rails-monolith storefront on top of Spree rather than a separate JavaScript runtime.

- **Human URL:** [https://github.com/spree/spree-rails-storefront](https://github.com/spree/spree-rails-storefront)
- **Base URL:** `https://github.com/spree/spree-rails-storefront`

#### Tags

- Storefront
- Rails
- Page Builder

#### Properties

- [Repository](https://github.com/spree/spree-rails-storefront)
- [Postman Collection](collections/spree-commerce-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-oauth-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-oauth-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-store-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-store-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-storefront-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-storefront-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### spree-starter (Application Template)

Reference Spree application template used to bootstrap new Spree installations - includes Docker Compose, the recommended gem set, and a sensible default configuration for self-hosted deployments.

- **Human URL:** [https://github.com/spree/spree-starter](https://github.com/spree/spree-starter)
- **Base URL:** `https://github.com/spree/spree-starter`

#### Tags

- Starter
- Application
- Docker

#### Properties

- [Repository](https://github.com/spree/spree-starter)
- [Postman Collection](collections/spree-commerce-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-oauth-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-oauth-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-store-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-store-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-storefront-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-storefront-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)


#### Tags

- Marketplace
- Multi Vendor
- Extension

#### Properties

- [Repository](https://github.com/spree/spree_multi_vendor)
- [Postman Collection](collections/spree-commerce-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-oauth-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-oauth-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-store-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-store-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-storefront-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-storefront-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### spree-multi-store

Extension for running and administering multiple stores from a single Spree installation - per-store products, taxonomies, domains, and configuration.

- **Human URL:** [https://github.com/spree/spree-multi-store](https://github.com/spree/spree-multi-store)
- **Base URL:** `https://github.com/spree/spree-multi-store`

#### Tags

- Multi Store
- Extension

#### Properties

- [Repository](https://github.com/spree/spree-multi-store)
- [Postman Collection](collections/spree-commerce-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-oauth-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-oauth-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-store-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-store-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-storefront-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-storefront-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spree Stripe Integration

Official Stripe payments integration for Spree, including support for Stripe Connect. Wires Spree's payment lifecycle to Stripe Payment Intents and Webhooks.

- **Human URL:** [https://github.com/spree/spree_stripe](https://github.com/spree/spree_stripe)
- **Base URL:** `https://github.com/spree/spree_stripe`

#### Tags

- Payments
- Stripe
- Integration

#### Properties

- [Repository](https://github.com/spree/spree_stripe)
- [Postman Collection](collections/spree-commerce-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-oauth-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-oauth-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-store-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-store-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-storefront-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-storefront-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spree Adyen Integration

Official Adyen payments platform integration for Spree Commerce - payment methods, capture, refund, and webhook handling against the Adyen API.

- **Human URL:** [https://github.com/spree/spree_adyen](https://github.com/spree/spree_adyen)
- **Base URL:** `https://github.com/spree/spree_adyen`

#### Tags

- Payments
- Adyen
- Integration

#### Properties

- [Repository](https://github.com/spree/spree_adyen)
- [Postman Collection](collections/spree-commerce-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-oauth-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-oauth-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-store-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-store-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-storefront-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-storefront-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spree PayPal Checkout Integration

Official PayPal Checkout integration extension for Spree - PayPal buttons, order flow, capture, and refund.

- **Human URL:** [https://github.com/spree/spree_paypal_checkout](https://github.com/spree/spree_paypal_checkout)
- **Base URL:** `https://github.com/spree/spree_paypal_checkout`

#### Tags

- Payments
- PayPal
- Integration

#### Properties

- [Repository](https://github.com/spree/spree_paypal_checkout)
- [Postman Collection](collections/spree-commerce-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-oauth-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-oauth-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-store-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-store-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-storefront-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-storefront-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spree Avalara AvaTax Integration

Officially certified Avalara AvaTax tax-calculation integration for Spree - real-time tax calculation, address validation, and document filing against AvaTax.

- **Human URL:** [https://github.com/spree/spree_avatax_official](https://github.com/spree/spree_avatax_official)
- **Base URL:** `https://github.com/spree/spree_avatax_official`

#### Tags

- Tax
- Avalara
- AvaTax
- Integration

#### Properties

- [Repository](https://github.com/spree/spree_avatax_official)
- [Postman Collection](collections/spree-commerce-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-oauth-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-oauth-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-store-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-store-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-storefront-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-storefront-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spree Klaviyo Integration

Official Klaviyo marketing-platform integration for Spree - syncs customers, orders, and product events to Klaviyo for email and SMS lifecycle marketing.

- **Human URL:** [https://github.com/spree/spree_klaviyo](https://github.com/spree/spree_klaviyo)
- **Base URL:** `https://github.com/spree/spree_klaviyo`

#### Tags

- Marketing
- Klaviyo
- Email
- Integration

#### Properties

- [Repository](https://github.com/spree/spree_klaviyo)
- [Postman Collection](collections/spree-commerce-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-oauth-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-oauth-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-store-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-store-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-storefront-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-storefront-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spree Google Analytics 4 Integration

Official Google Analytics 4 integration for Spree - ecommerce event tracking and measurement on top of the Spree storefronts.

- **Human URL:** [https://github.com/spree/spree_google_analytics](https://github.com/spree/spree_google_analytics)
- **Base URL:** `https://github.com/spree/spree_google_analytics`

#### Tags

- Analytics
- Google Analytics
- Integration

#### Properties

- [Repository](https://github.com/spree/spree_google_analytics)
- [Postman Collection](collections/spree-commerce-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-oauth-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-oauth-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-store-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-store-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-storefront-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-storefront-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### spree_extension (Extension Generator CLI)

CLI tool for generating and managing Spree Commerce extensions - scaffolds the gemspec, engine, migrations, and conventions used by the Spree extension ecosystem.

- **Human URL:** [https://github.com/spree/spree_extension](https://github.com/spree/spree_extension)
- **Base URL:** `https://github.com/spree/spree_extension`

#### Tags

- CLI
- Extension
- Tooling

#### Properties

- [Repository](https://github.com/spree/spree_extension)
- [Postman Collection](collections/spree-commerce-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-oauth-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-oauth-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-store-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-store-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-storefront-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-storefront-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spree Dev Tools

Internal developer tooling for working on Spree itself - debuggers, profilers, dummy data generators, and helpers used by Spree's core contributors and extension authors.

- **Human URL:** [https://github.com/spree/spree_dev_tools](https://github.com/spree/spree_dev_tools)
- **Base URL:** `https://github.com/spree/spree_dev_tools`

#### Tags

- Developer Tools
- Tooling

#### Properties

- [Repository](https://github.com/spree/spree_dev_tools)
- [Postman Collection](collections/spree-commerce-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-oauth-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-oauth-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-store-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-store-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-storefront-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-storefront-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### deface (Rails View Customization)

Rails plugin maintained under the Spree organization that lets Spree stores customize ERB views without forking the underlying templates. Core extension primitive in the Spree ecosystem.

- **Human URL:** [https://github.com/spree/deface](https://github.com/spree/deface)
- **Base URL:** `https://github.com/spree/deface`

#### Tags

- Rails
- Views
- Customization
- Plugin

#### Properties

- [Repository](https://github.com/spree/deface)
- [Postman Collection](collections/spree-commerce-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-oauth-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-oauth-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-store-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-store-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-storefront-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-storefront-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spree Core Repository (spree/spree)

Monorepo with the Spree Rails engine, Admin, Store/Admin/Platform/ Storefront APIs, OpenAPI specs, TypeScript SDKs, CLI, and Next.js storefront. Released since 2007; latest stable release v5.4.3.

- **Human URL:** [https://github.com/spree/spree](https://github.com/spree/spree)
- **Base URL:** `https://github.com/spree/spree`

#### Tags

- Open Source
- Repository
- Monorepo
- Rails
- Ruby

#### Properties

- [Repository](https://github.com/spree/spree)
- [Postman Collection](collections/spree-commerce-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-oauth-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-oauth-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-store-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-store-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spree-commerce-storefront-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spree-commerce-storefront-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://spreecommerce.org/)
- [Documentation](https://dev-docs.spreecommerce.org/)
- [A P I  Reference](https://dev-docs.spreecommerce.org/api-reference/introduction)
- [Git Hub](https://github.com/spree)
- [Pricing](https://spreecommerce.org/pricing/)
- [Demo](https://demo.spreecommerce.org/)
- [Releases](https://github.com/spree/spree/releases)
- [LinkedIn](https://www.linkedin.com/company/spree-commerce/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
