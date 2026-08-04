# Taboola (taboola)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Taboola (NASDAQ: TBLA) is a New-York-headquartered native and discovery advertising company founded in 2007 by Adam Singolda. Its Realize performance marketing platform serves recommendation widgets across major publishers (a 30-year exclusive partnership with Yahoo since 2022) and offers advertisers programmatic access via the Backstage API for campaign management, audience targeting, conversion tracking, and reporting. The company also operates Connexity (commerce media), Skimlinks (publisher monetization), and DeeperDive (content discovery), and recently shipped Abby (AI ad assistant), the GenAI Ad Maker, and an official Realize MCP server for AI-driven campaign management.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/taboola/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/taboola/refs/heads/main/apis.yml)

## Scope

- **Position:** Producing
- **Access:** 3rd-Party

## Tags

- Advertising
- Native Advertising
- Discovery
- Performance Marketing
- AdTech
- Realize
- Backstage
- Recommendation
- Publisher
- Programmatic

## Timestamps

- **Created:** 2026-05-25T00:00:00.000Z
- **Modified:** 2026-05-25

## APIs

### Taboola Backstage Campaigns API

Create, retrieve, update, duplicate, and delete Taboola Realize advertising campaigns. Includes bulk update across the network and a campaign reach estimator for pre-launch impression forecasting.

- **Human URL:** [https://developers.taboola.com/backstage-api/reference/campaigns-overview](https://developers.taboola.com/backstage-api/reference/campaigns-overview)

#### Tags

- Advertising
- Native Advertising
- Campaigns
- Realize

#### Properties

- [Documentation](https://developers.taboola.com/backstage-api/reference/campaigns-overview)
- [Documentation](https://developers.taboola.com/backstage-api/reference/create-a-campaign)
- [OpenAPI](openapi/taboola-backstage-campaigns-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/taboola-backstage-campaigns-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/taboola-backstage-campaigns-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/taboola-campaign-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/taboola-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Taboola Backstage Campaign Items API

Manage individual ad items (creatives) and performance video items (motion ads) belonging to Taboola Realize campaigns. Supports per-campaign CRUD plus bulk create, update, and delete across multiple campaigns and across the network.

- **Human URL:** [https://developers.taboola.com/backstage-api/reference/campaign-items-overview](https://developers.taboola.com/backstage-api/reference/campaign-items-overview)

#### Tags

- Advertising
- Creatives
- Items
- Video

#### Properties

- [Documentation](https://developers.taboola.com/backstage-api/reference/campaign-items-overview)
- [OpenAPI](openapi/taboola-backstage-items-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/taboola-backstage-items-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/taboola-backstage-items-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/taboola-item-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Taboola Backstage Audiences API

Manage first-party, custom, lookalike, marketplace, and combined audiences for Taboola Realize campaign targeting. Includes audience onboarding for hashed identifiers (CRM and pixel-based), plus audience-targeting endpoints applied at the campaign level.

- **Human URL:** [https://developers.taboola.com/backstage-api/reference/audience-targeting](https://developers.taboola.com/backstage-api/reference/audience-targeting)

#### Tags

- Advertising
- Audiences
- Targeting
- First-Party Data

#### Properties

- [Documentation](https://developers.taboola.com/backstage-api/reference/audience-targeting)
- [Documentation](https://developers.taboola.com/backstage-api/reference/onboarding-overview)
- [OpenAPI](openapi/taboola-backstage-audiences-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/taboola-backstage-audiences-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/taboola-backstage-audiences-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Taboola Backstage Conversions API

Create and manage conversion rules used to track purchases, leads, registrations, page views, and other outcomes. Supports event-based and URL-based rules with configurable look-back windows for both click-through and view-through attribution.

- **Human URL:** [https://developers.taboola.com/conversion-tracking](https://developers.taboola.com/conversion-tracking)

#### Tags

- Advertising
- Conversions
- Measurement
- Attribution

#### Properties

- [Documentation](https://developers.taboola.com/backstage-api/reference/conversion-rule-fields)
- [Documentation](https://developers.taboola.com/conversion-tracking)
- [OpenAPI](openapi/taboola-backstage-conversions-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/taboola-backstage-conversions-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/taboola-backstage-conversions-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/taboola-conversion-rule-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Taboola Backstage Reports API

Retrieve campaign-summary reports across many breakdown dimensions (day, week, month, campaign, site, country, region, platform, OS, browser, language, DMA, city, ad), top-content reports, and near real-time performance snapshots.

- **Human URL:** [https://developers.taboola.com/backstage-api/reference](https://developers.taboola.com/backstage-api/reference)

#### Tags

- Advertising
- Reporting
- Analytics
- Performance

#### Properties

- [Documentation](https://developers.taboola.com/backstage-api/reference)
- [OpenAPI](openapi/taboola-backstage-reports-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/taboola-backstage-reports-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/taboola-backstage-reports-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Taboola Backstage Dictionary API

Reference data endpoints for campaign targeting. Returns supported countries, regions, cities, postal codes, US DMAs, browsers, operating systems, OS versions, platforms, languages, publishers, contextual segments, minimum CPC values, and campaign/item enumerations.

- **Human URL:** [https://developers.taboola.com/backstage-api/reference/dictionary](https://developers.taboola.com/backstage-api/reference/dictionary)

#### Tags

- Advertising
- Reference Data
- Targeting

#### Properties

- [Documentation](https://developers.taboola.com/backstage-api/reference/dictionary)
- [OpenAPI](openapi/taboola-backstage-dictionary-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/taboola-backstage-dictionary-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/taboola-backstage-dictionary-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Taboola Backstage Accounts API

Discover advertiser accounts allowed for the authenticated user, list all advertiser accounts in a Taboola network, and retrieve per-account configuration including currency, time zone, and partner types.

- **Human URL:** [https://developers.taboola.com/backstage-api/reference](https://developers.taboola.com/backstage-api/reference)

#### Tags

- Advertising
- Accounts
- Network

#### Properties

- [Documentation](https://developers.taboola.com/backstage-api/reference/get-allowed-accounts)
- [OpenAPI](openapi/taboola-backstage-accounts-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/taboola-backstage-accounts-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/taboola-backstage-accounts-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://www.taboola.com)
- [Documentation](https://developers.taboola.com/)
- [Documentation](https://developers.taboola.com/backstage-api/reference)
- [Documentation](https://developers.taboola.com/llms.txt)
- [Authentication](https://developers.taboola.com/backstage-api/reference/authentication-basics)
- [Authentication](https://developers.taboola.com/backstage-api/reference/client-credentials-flow)
- [Authentication](https://developers.taboola.com/backstage-api/reference/getting-an-access-token)
- [Authentication](https://backstage.taboola.com/backstage/oauth/token)
- [Base U R L](https://backstage.taboola.com/backstage/api/1.0)
- [GitHub Organization](https://github.com/taboola)
- [SDK](https://github.com/taboola/backstage-api-java-client)
- [Tool](https://github.com/taboola/realize-mcp)
- [SDK](https://github.com/taboola/taboola-spm-ios-sdk)
- [SDK](https://github.com/taboola/taboola-android)
- [SDK](https://github.com/taboola/taboola-flutter-example)
- [Code Examples](https://github.com/taboola/ios-sdk-examples)
- [Code Examples](https://github.com/taboola/android-sdk-examples-4x)
- [Code Examples](https://github.com/taboola/react-native-examples-3x)
- [SDK](https://github.com/taboola/ios-adx)
- [Tool](https://github.com/taboola/Prebid.js)
- [Terms of Service](https://www.taboola.com/legal-policies)
- [Privacy Policy](https://www.taboola.com/policies/privacy-policy)
- [Trust Center](https://trust.taboola.com/)
- [Support](https://help.taboola.com/)
- [Blog](https://www.taboola.com/blog)
- [News](https://www.taboola.com/press)
- [Investor Relations](https://investors.taboola.com/)
- [LinkedIn](https://www.linkedin.com/company/taboola)
- [X- Twitter](https://x.com/taboola)
- [YouTube](https://www.youtube.com/user/taboola)
- [Sign In](https://realize.taboola.com/)
- [Portal](https://www.taboola.com/products/realize)
- [Portal](https://www.taboola.com/abby)
- [Portal](https://www.taboola.com/products/genai-ad-maker)
- [Portal](https://www.taboola.com/products/deeperdive)
- [Portal](https://www.taboola.com/products/connexity)
- [Portal](https://www.taboola.com/products/skimlinks)
- [Portal](https://www.taboola.com/products/newsroom)
- [Documentation](https://developers.taboola.com/taboolasdk/docs/overview)
- [Documentation](https://developers.taboola.com/dynamic-creative/docs/overview)
- [Plans](plans/taboola-plans-pricing.yml)
- [Rate Limits](rate-limits/taboola-rate-limits.yml)
- [Fin Ops](finops/taboola-finops.yml)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
