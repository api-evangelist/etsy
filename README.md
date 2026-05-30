# Etsy (etsy)

Etsy is a global marketplace for unique and creative handmade, vintage, and craft-supply goods. The Etsy Open API v3 is a REST + OAuth 2.0 surface that third-party developers, sellers, and integration partners use to manage shops, listings, inventory, receipts, transactions, payments, ledger entries, reviews, shipping profiles, processing profiles, production partners, return policies, and seller/buyer taxonomy. Webhooks deliver order lifecycle events (order.paid, order.canceled, order.shipped, order.delivered) to subscriber endpoints. This profile catalogs the public API surface, machine-readable artifacts, plans, rate limits, FinOps alignment, and Naftiko capabilities.

**URL:** [Visit APIs.json URL](https://developers.etsy.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=etsy-api-evangelist&utm_content=repo)

## Tags

- Marketplace, Ecommerce, Handmade, Listings, Orders, Payments, Reviews, Shipping, Taxonomy, OAuth2

## Timestamps

- **Created:** 2026-05-05
- **Modified:** 2026-05-30

## APIs

### Etsy Open API v3

The Etsy Open API v3 is the official REST + OAuth 2.0 surface used to build applications against the Etsy marketplace. It focuses on three primary use cases: listing management, post-purchase order management, and shop management. Authentication uses an x-api-key header (your keystring) on every request, with OAuth 2.0 Authorization Code + PKCE for user-scoped operations. Default base URL: `https://openapi.etsy.com` (production calls also resolve at `https://api.etsy.com/v3/application`).

**Human URL:** [https://developers.etsy.com/documentation](https://developers.etsy.com/documentation)

**Base URL:** `https://openapi.etsy.com`

#### Tags

- Open API v3, Marketplace, Listings, Receipts, Shop, Taxonomy, OAuth2

#### Properties

- [Documentation](https://developers.etsy.com/documentation)
- [Reference](https://developers.etsy.com/documentation/reference)
- [Authentication](https://developers.etsy.com/documentation/essentials/authentication)
- [OAuth2](https://developers.etsy.com/documentation/essentials/oauth2)
- [RateLimits](https://developers.etsy.com/documentation/essentials/rate-limits)
- [Requests](https://developers.etsy.com/documentation/essentials/requests)
- [Migration](https://developers.etsy.com/documentation/migration/index)
- [OpenAPI](openapi/etsy-openapi-original.yml)
- [Upstream OpenAPI JSON](https://www.etsy.com/openapi/generated/oas/3.0.0.json)
- [Open API repo](https://github.com/etsy/open-api)

### Etsy Open API v3 Webhooks

AsyncAPI 2.6 description of Etsy's outbound webhook surface for the Open API v3. Covers the four documented event types (order.paid, order.canceled, order.shipped, order.delivered), the common webhook envelope, the signing headers, HMAC-SHA256 signature verification procedure, and Etsy's documented retry schedule.

**Human URL:** [https://developers.etsy.com/documentation/essentials/webhooks](https://developers.etsy.com/documentation/essentials/webhooks)

#### Tags

- Webhooks, Events, AsyncAPI, Order Lifecycle

#### Properties

- [Documentation](https://developers.etsy.com/documentation/essentials/webhooks)
- [AsyncAPI](asyncapi/etsy-webhooks-asyncapi.yml)

## Common Properties

- [Website](https://www.etsy.com)
- [DeveloperPortal](https://developers.etsy.com/)
- [Documentation](https://developers.etsy.com/documentation)
- [Reference](https://developers.etsy.com/documentation/reference)
- [GitHubOrganization](https://github.com/etsy)
- [LinkedIn](https://www.linkedin.com/company/etsy)
- [TwitterAccount](https://twitter.com/etsy)
- [StatusPage](https://www.etsystatus.com/)
- [TermsOfService](https://www.etsy.com/legal/api/terms)
- [PrivacyPolicy](https://www.etsy.com/legal/privacy)
- [Pricing](https://developers.etsy.com/documentation/essentials/rate-limits)
- [Support](mailto:developers@etsy.com)
- [ChangeLog](https://developers.etsy.com/changelog)
- [CodeOfConduct](https://etsy.github.io/codeofconduct.html)
- [Plans](plans/etsy-plans-pricing.yml)
- [RateLimits](rate-limits/etsy-rate-limits.yml)
- [FinOps](finops/etsy-finops.yml)
- [Vocabulary](vocabulary/etsy-vocabulary.yml)
- [SpectralRules](rules/etsy-rules.yml)
- [Pinot MCP Server (Etsy fork)](https://github.com/etsy/mcp-pinot)
- [XCLogParser](https://github.com/etsy/XCLogParser)
- [Cartography](https://github.com/etsy/cartography)

## Features

| Name | Description |
|------|-------------|
| Listing Management | Create, update, retrieve, deactivate, and delete shop listings; manage listing images, videos, files, translations, personalization, variation images, inventory, offerings, and products. |
| Order & Receipt Management | Read shop receipts, transactions, payments, and ledger entries; mark receipts paid or shipped; create shipment tracking entries; manage post-purchase order workflows. |
| Shop Management | Update shop properties, sections, shipping profiles, processing profiles, production partners, return policies, and holiday preferences. |
| Taxonomy | Browse the buyer taxonomy used for navigation and the seller taxonomy used to classify listings. |
| Reviews | Retrieve transaction-level and shop-level reviews left by buyers. |
| Webhooks | Subscribe an HTTPS endpoint to order lifecycle events; verify with HMAC-SHA256 and the documented retry schedule. |
| OAuth 2.0 Authentication | Authorization Code + PKCE flow with refresh tokens for user-scoped operations; per-request x-api-key header for every call. |

## Use Cases

| Name | Description |
|------|-------------|
| Inventory Sync | Keep shop listings, prices, quantities, and product variations in sync between Etsy and a seller's inventory management system. |
| Multi-Channel Order Fulfillment | Pull paid Etsy receipts into a fulfillment platform, generate shipping labels, write tracking back to Etsy, and trigger seller notifications. |
| Shop Analytics | Aggregate ledger entries, payments, and receipts to produce seller revenue, fee, and payout reporting. |
| Listing Automation | Programmatically create and update listings from a product catalog, including images, videos, variations, and personalization options. |
| Customer Service | Surface reviews and message-related receipt context to seller-side customer service tooling. |
| Shipping Integration | Manage shop shipping profiles, attach tracking codes to fulfilled receipts, and configure region- and weight-based shipping rules. |

## Integrations

| Name | Description |
|------|-------------|
| QuickBooks | Sync Etsy sales, fees, and payouts into QuickBooks accounting. |
| ShipStation | Pull Etsy orders into ShipStation for label generation and tracking. |
| Printful / Printify | Connect print-on-demand fulfillment for Etsy listings. |
| Zapier | Trigger workflows from Etsy receipts, listings, and webhook events. |
| Make.com (Integromat) | Visual automation around Etsy shop, listings, and order events. |

## Solutions

| Name | Description |
|------|-------------|
| Inventory & Catalog Management | Maintain Etsy listings, inventory levels, and variations from a central PIM. |
| Order Operations | Run paid-order processing, shipping, refunds, and post-purchase messaging against Etsy receipts and transactions. |
| Financial Reporting | Reconcile Etsy ledger entries, payments, and refunds into bookkeeping, tax, and revenue recognition systems. |
| Marketplace Expansion | Use Etsy alongside other marketplaces to expand reach for handmade, vintage, and craft-supply sellers. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Etsy Open API v3](openapi/etsy-openapi-original.yml) — 74 operations, 81 schemas

### AsyncAPI

- [Etsy Open API v3 Webhooks](asyncapi/etsy-webhooks-asyncapi.yml) — 4 events

### JSON Schema

- 86 standalone JSON Schema files under [`json-schema/`](json-schema/)

### JSON Structure

- 86 JSON Structure files under [`json-structure/`](json-structure/)

### JSON-LD

- [Etsy Open API v3 Context](json-ld/etsy-open-api-v3-context.jsonld) — 81 types, 348 properties
- [Etsy Webhooks Context](json-ld/etsy-webhooks-context.jsonld) — 1 type, 3 properties

### Examples

- 86 example payloads under [`examples/`](examples/)

## Capabilities

Naftiko capabilities organized as one self-contained file per OpenAPI tag, each exposing both a REST adapter and an MCP adapter routed through an inline consumes block.

| Capability | Tag | Operations | File |
|---|---|---|---|
| Etsy Open API v3 — User | User | 2 | [open-api-v3-user.yaml](capabilities/open-api-v3-user.yaml) |
| Etsy Open API v3 — UserAddress | UserAddress | 3 | [open-api-v3-user-address.yaml](capabilities/open-api-v3-user-address.yaml) |
| Etsy Open API v3 — Shop | Shop | 4 | [open-api-v3-shop.yaml](capabilities/open-api-v3-shop.yaml) |
| Etsy Open API v3 — Shop Section | Shop Section | 5 | [open-api-v3-shop-section.yaml](capabilities/open-api-v3-shop-section.yaml) |
| Etsy Open API v3 — Shop ShippingProfile | Shop ShippingProfile | 14 | [open-api-v3-shop-shipping-profile.yaml](capabilities/open-api-v3-shop-shipping-profile.yaml) |
| Etsy Open API v3 — Shop ProcessingProfiles | Shop ProcessingProfiles | 5 | [open-api-v3-shop-processing-profiles.yaml](capabilities/open-api-v3-shop-processing-profiles.yaml) |
| Etsy Open API v3 — Shop ProductionPartner | Shop ProductionPartner | 1 | [open-api-v3-shop-production-partner.yaml](capabilities/open-api-v3-shop-production-partner.yaml) |
| Etsy Open API v3 — Shop Return Policy | Shop Return Policy | 6 | [open-api-v3-shop-return-policy.yaml](capabilities/open-api-v3-shop-return-policy.yaml) |
| Etsy Open API v3 — Shop HolidayPreferences | Shop HolidayPreferences | 2 | [open-api-v3-shop-holiday-preferences.yaml](capabilities/open-api-v3-shop-holiday-preferences.yaml) |
| Etsy Open API v3 — Shop Receipt | Shop Receipt | 4 | [open-api-v3-shop-receipt.yaml](capabilities/open-api-v3-shop-receipt.yaml) |
| Etsy Open API v3 — Shop Receipt Transactions | Shop Receipt Transactions | 4 | [open-api-v3-shop-receipt-transactions.yaml](capabilities/open-api-v3-shop-receipt-transactions.yaml) |
| Etsy Open API v3 — ShopListing | ShopListing | 16 | [open-api-v3-shop-listing.yaml](capabilities/open-api-v3-shop-listing.yaml) |
| Etsy Open API v3 — ShopListing File | ShopListing File | 4 | [open-api-v3-shop-listing-file.yaml](capabilities/open-api-v3-shop-listing-file.yaml) |
| Etsy Open API v3 — ShopListing Image | ShopListing Image | 4 | [open-api-v3-shop-listing-image.yaml](capabilities/open-api-v3-shop-listing-image.yaml) |
| Etsy Open API v3 — ShopListing Video | ShopListing Video | 4 | [open-api-v3-shop-listing-video.yaml](capabilities/open-api-v3-shop-listing-video.yaml) |
| Etsy Open API v3 — ShopListing Inventory | ShopListing Inventory | 2 | [open-api-v3-shop-listing-inventory.yaml](capabilities/open-api-v3-shop-listing-inventory.yaml) |
| Etsy Open API v3 — ShopListing Offering | ShopListing Offering | 1 | [open-api-v3-shop-listing-offering.yaml](capabilities/open-api-v3-shop-listing-offering.yaml) |
| Etsy Open API v3 — ShopListing Product | ShopListing Product | 1 | [open-api-v3-shop-listing-product.yaml](capabilities/open-api-v3-shop-listing-product.yaml) |
| Etsy Open API v3 — ShopListing Translation | ShopListing Translation | 3 | [open-api-v3-shop-listing-translation.yaml](capabilities/open-api-v3-shop-listing-translation.yaml) |
| Etsy Open API v3 — ShopListing Personalization | ShopListing Personalization | 3 | [open-api-v3-shop-listing-personalization.yaml](capabilities/open-api-v3-shop-listing-personalization.yaml) |
| Etsy Open API v3 — ShopListing VariationImage | ShopListing VariationImage | 2 | [open-api-v3-shop-listing-variation-image.yaml](capabilities/open-api-v3-shop-listing-variation-image.yaml) |
| Etsy Open API v3 — Payment | Payment | 3 | [open-api-v3-payment.yaml](capabilities/open-api-v3-payment.yaml) |
| Etsy Open API v3 — Ledger Entry | Ledger Entry | 2 | [open-api-v3-ledger-entry.yaml](capabilities/open-api-v3-ledger-entry.yaml) |
| Etsy Open API v3 — Review | Review | 2 | [open-api-v3-review.yaml](capabilities/open-api-v3-review.yaml) |
| Etsy Open API v3 — BuyerTaxonomy | BuyerTaxonomy | 2 | [open-api-v3-buyer-taxonomy.yaml](capabilities/open-api-v3-buyer-taxonomy.yaml) |
| Etsy Open API v3 — SellerTaxonomy | SellerTaxonomy | 2 | [open-api-v3-seller-taxonomy.yaml](capabilities/open-api-v3-seller-taxonomy.yaml) |
| Etsy Open API v3 — Other | Other | 2 | [open-api-v3-other.yaml](capabilities/open-api-v3-other.yaml) |

## Vocabulary

- [Etsy Vocabulary](vocabulary/etsy-vocabulary.yml) — Unified taxonomy mapping 27 resources, 5 actions, 27 workflows, and 5 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Etsy Spectral Rules](rules/etsy-rules.yml) — 56 rules across 13 categories enforcing Etsy Open API v3 conventions (kebab-case paths, snake_case schemas, camelCase operationIds, dual x-api-key + OAuth 2.0 security, Microcks compatibility)

## Plans

- [Etsy Plans & Pricing](plans/etsy-plans-pricing.yml) — Free developer tier (10k req/day, 10 req/s default) plus the seller-side marketplace fees (listing fee, 6.5% transaction fee, payment processing fees, Etsy Ads, Etsy Plus subscription)

## Rate Limits

- [Etsy Rate Limits](rate-limits/etsy-rate-limits.yml) — Application-scoped QPS + QPD limits with x-limit-per-second / x-limit-per-day / x-remaining-* response headers and retry-after on 429

## FinOps

- [Etsy FinOps](finops/etsy-finops.yml) — FOCUS-aligned marketplace FinOps view: take-rate + subscription billing, 8 meters (api_requests, listings_published, marketplace_transactions, GMV, payment_processing_fees, offsite_ads_attribution, etsy_ads_spend, refunds_and_chargebacks)

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
