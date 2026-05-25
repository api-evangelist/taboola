# Taboola (taboola)

Taboola (NASDAQ: TBLA) is a New-York-headquartered native and discovery advertising company founded in 2007 by Adam Singolda. Its Realize performance marketing platform serves recommendation widgets across major publishers — including a 30-year exclusive partnership with Yahoo signed in 2022 — and offers advertisers programmatic access via the Backstage API for campaign management, audience targeting, conversion tracking, and reporting. The company also operates Connexity (commerce media), Skimlinks (publisher monetization), and DeeperDive (content discovery), and recently shipped Abby (AI ad assistant), the GenAI Ad Maker, and an official Realize MCP server for AI-driven campaign management.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/taboola/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

- Advertising, Native Advertising, Discovery, Performance Marketing, AdTech, Realize, Backstage, Recommendation, Publisher, Programmatic

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## Company at a Glance

| Field | Value |
|---|---|
| Ticker | NASDAQ: TBLA |
| Founded | 2007 |
| Founder | Adam Singolda |
| HQ | New York, NY |
| Employees | ~2,000 |
| 2024 Revenue | $1.77B |
| Flagship platform | Realize (performance advertising) |
| Key partnership | Yahoo native exclusive (30-year, signed Nov 2022) |
| Acquisitions | Connexity ($800M, 2021); Skimlinks; Perfect Market; Convert Media; Gravity R&D |

## Authentication

The Backstage API uses OAuth 2.0 **Client Credentials** flow.

- **Token endpoint:** `https://backstage.taboola.com/backstage/oauth/token`
- **API base URL:** `https://backstage.taboola.com/backstage/api/1.0`
- **Grant type:** `client_credentials`
- **Credentials:** `client_id` + `client_secret` (issued by your Taboola account manager)

Pass the returned access token as `Authorization: Bearer <token>` on every Backstage call.

## APIs

### Taboola Backstage Campaigns API
Create, retrieve, update, duplicate, and delete Taboola Realize advertising campaigns. Includes bulk update across the network and a campaign reach estimator for pre-launch impression forecasting.

**Human URL:** [https://developers.taboola.com/backstage-api/reference/campaigns-overview](https://developers.taboola.com/backstage-api/reference/campaigns-overview)

- [Documentation](https://developers.taboola.com/backstage-api/reference/campaigns-overview)
- [Documentation — Create A Campaign](https://developers.taboola.com/backstage-api/reference/create-a-campaign)
- [OpenAPI](openapi/taboola-backstage-campaigns-api-openapi.yml)
- [JSON Schema — Campaign](json-schema/taboola-campaign-schema.json)
- [JSON-LD](json-ld/taboola-context.jsonld)
- [Naftiko Capability — Campaigns](capabilities/campaigns-campaigns.yaml)

### Taboola Backstage Campaign Items API
Manage individual ad items (creatives) and performance video items (motion ads) belonging to Taboola Realize campaigns. Supports per-campaign CRUD plus bulk create, update, and delete across multiple campaigns and across the network.

**Human URL:** [https://developers.taboola.com/backstage-api/reference/campaign-items-overview](https://developers.taboola.com/backstage-api/reference/campaign-items-overview)

- [OpenAPI](openapi/taboola-backstage-items-api-openapi.yml)
- [JSON Schema — Item](json-schema/taboola-item-schema.json)
- [Naftiko Capability — Items](capabilities/items-items.yaml)

### Taboola Backstage Audiences API
Manage first-party, custom, lookalike, marketplace, and combined audiences for Taboola Realize campaign targeting. Includes audience onboarding for hashed identifiers (CRM and pixel-based), plus audience-targeting endpoints applied at the campaign level.

**Human URL:** [https://developers.taboola.com/backstage-api/reference/audience-targeting](https://developers.taboola.com/backstage-api/reference/audience-targeting)

- [OpenAPI](openapi/taboola-backstage-audiences-api-openapi.yml)
- [Naftiko Capability — Audiences](capabilities/audiences-audiences.yaml)

### Taboola Backstage Conversions API
Create and manage conversion rules used to track purchases, leads, registrations, page views, and other outcomes. Supports event-based and URL-based rules with configurable look-back windows for both click-through and view-through attribution.

**Human URL:** [https://developers.taboola.com/conversion-tracking](https://developers.taboola.com/conversion-tracking)

- [OpenAPI](openapi/taboola-backstage-conversions-api-openapi.yml)
- [JSON Schema — Conversion Rule](json-schema/taboola-conversion-rule-schema.json)
- [Naftiko Capability — Conversions](capabilities/conversions-conversions.yaml)

### Taboola Backstage Reports API
Retrieve campaign-summary reports across many breakdown dimensions (day, week, month, campaign, site, country, region, platform, OS, browser, language, DMA, city, ad), top-content reports, and near real-time performance snapshots.

**Human URL:** [https://developers.taboola.com/backstage-api/reference](https://developers.taboola.com/backstage-api/reference)

- [OpenAPI](openapi/taboola-backstage-reports-api-openapi.yml)
- [Naftiko Capability — Reports](capabilities/reports-reports.yaml)

### Taboola Backstage Dictionary API
Reference data endpoints for campaign targeting. Returns supported countries, regions, cities, postal codes, US DMAs, browsers, operating systems, OS versions, platforms, languages, publishers, contextual segments, minimum CPC values, and campaign/item enumerations.

**Human URL:** [https://developers.taboola.com/backstage-api/reference/dictionary](https://developers.taboola.com/backstage-api/reference/dictionary)

- [OpenAPI](openapi/taboola-backstage-dictionary-api-openapi.yml)
- [Naftiko Capability — Dictionary](capabilities/dictionary-dictionary.yaml)

### Taboola Backstage Accounts API
Discover advertiser accounts allowed for the authenticated user, list all advertiser accounts in a Taboola network, and retrieve per-account configuration including currency, time zone, and partner types.

**Human URL:** [https://developers.taboola.com/backstage-api/reference](https://developers.taboola.com/backstage-api/reference)

- [OpenAPI](openapi/taboola-backstage-accounts-api-openapi.yml)
- [Naftiko Capability — Accounts](capabilities/accounts-accounts.yaml)

## Naftiko Capabilities

| Capability | Description |
|---|---|
| [campaigns-campaigns.yaml](capabilities/campaigns-campaigns.yaml) | List, get, create, update, delete Taboola campaigns. |
| [items-items.yaml](capabilities/items-items.yaml) | Manage creative items per campaign. |
| [audiences-audiences.yaml](capabilities/audiences-audiences.yaml) | First-party / lookalike / marketplace audiences. |
| [conversions-conversions.yaml](capabilities/conversions-conversions.yaml) | Conversion rule CRUD. |
| [reports-reports.yaml](capabilities/reports-reports.yaml) | Campaign-summary and top-content reporting. |
| [dictionary-dictionary.yaml](capabilities/dictionary-dictionary.yaml) | Reference data for targeting. |
| [accounts-accounts.yaml](capabilities/accounts-accounts.yaml) | Account discovery within a network. |

## SDKs, Tooling, and Integrations

- [Backstage API Java Client](https://github.com/taboola/backstage-api-java-client) — Official Java client.
- [Realize MCP Server](https://github.com/taboola/realize-mcp) — Official MCP server (Python, Apache-2.0) wrapping the Realize/Backstage API with OAuth 2.1 SSO for AI assistants.
- [Taboola Android SDK](https://github.com/taboola/taboola-android) and [V4 examples](https://github.com/taboola/android-sdk-examples-4x).
- [Taboola iOS SDK (SwiftPM)](https://github.com/taboola/taboola-spm-ios-sdk), [iOS SDK examples](https://github.com/taboola/ios-sdk-examples).
- [Taboola Flutter example](https://github.com/taboola/taboola-flutter-example) and [React Native examples](https://github.com/taboola/react-native-examples-3x).
- [Taboola iOS AdX Adapter](https://github.com/taboola/ios-adx) for Google AdX.
- [Prebid.js fork](https://github.com/taboola/Prebid.js) — header bidding integration.

## Products and Properties

- **[Realize](https://www.taboola.com/products/realize)** — Performance advertising platform (campaigns, items, audiences, conversions, reports).
- **[Abby](https://www.taboola.com/abby)** — AI ad assistant for campaign creation.
- **[GenAI Ad Maker](https://www.taboola.com/products/genai-ad-maker)** — Automated creative generation.
- **[DeeperDive](https://www.taboola.com/products/deeperdive)** — Content discovery.
- **[Connexity](https://www.taboola.com/products/connexity)** — Commerce media (acquired 2021).
- **[Skimlinks](https://www.taboola.com/products/skimlinks)** — Publisher monetization.
- **[Newsroom](https://www.taboola.com/products/newsroom)** — Publisher insights and recommendations.

## FinOps, Plans & Rate Limits

- [Plans & Pricing](plans/taboola-plans-pricing.yml) — Usage-based per-click / per-impression / per-conversion; minimum daily campaign budget typically $10.
- [Rate Limits](rate-limits/taboola-rate-limits.yml) — OAuth-client-scoped; bulk endpoints preferred over per-resource loops.
- [FinOps](finops/taboola-finops.yml) — FOCUS-aligned definition with click / impression / conversion meters tied to Backstage reports.

## Position

Producing — Taboola produces APIs (Backstage), SDKs (Mobile / Java / MCP), and a performance advertising platform consumed by advertisers, agencies, and AI assistants.

## Maintainer

- **Kin Lane** — [API Evangelist](https://apievangelist.com)
