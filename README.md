# Petpooja (petpooja)

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

Petpooja is a restaurant point-of-sale (POS) and management platform serving 75,000+ restaurants across India, the Middle East, Canada, and South Africa. Its Online Ordering API lets aggregators and partner ordering platforms sync a restaurant's menu/catalog, push orders into the Petpooja POS, receive order-status callbacks, and toggle item stock and store availability.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/petpooja/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/petpooja/refs/heads/main/apis.yml)

## Tags

- Restaurant
- POS
- Online Ordering
- Menu
- Food Delivery

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Petpooja Menu / Catalog API

Fetch a mapped restaurant's full menu (categories, items, variations, add-on groups, attributes, taxes, discounts) from Petpooja, and receive Petpooja's Push Menu callback when a restaurant updates its catalog. Authenticated with app-key, app-secret, and access-token; scoped by restID.

- **Human URL:** [https://onlineorderingapisv210.docs.apiary.io/](https://onlineorderingapisv210.docs.apiary.io/)
- **Base URL:** `https://qle1yy2ydc.execute-api.ap-southeast-1.amazonaws.com/V1`

#### Tags

- Menu
- Catalog
- Items

#### Properties

- [Documentation](https://onlineorderingapisv210.docs.apiary.io/)
- [API Reference](https://onlineorderingapisv210.docs.apiary.io/)
- [OpenAPI](openapi/petpooja-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/petpooja.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/petpooja.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Petpooja Orders API

Push a new online order (customer, order, order items, taxes, discounts, delivery and packing charges, payment type, prep time, OTP) into the Petpooja POS via save_order. Authenticated with app_key, app_secret, and access_token in the request body.

- **Human URL:** [https://onlineorderingapisv210.docs.apiary.io/](https://onlineorderingapisv210.docs.apiary.io/)
- **Base URL:** `https://47pfzh5sf2.execute-api.ap-southeast-1.amazonaws.com/V1`

#### Tags

- Orders
- Save Order
- POS

#### Properties

- [Documentation](https://onlineorderingapisv210.docs.apiary.io/)
- [API Reference](https://onlineorderingapisv210.docs.apiary.io/)
- [OpenAPI](openapi/petpooja-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/petpooja.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/petpooja.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Petpooja Stores API

Turn a restaurant/store online ordering on or off and set a turn-on time (store availability). Documented via the turn_on_time mechanism; exact endpoint path and request schema are not publicly reconciled.

- **Human URL:** [https://onlineorderingapisv210.docs.apiary.io/](https://onlineorderingapisv210.docs.apiary.io/)
- **Base URL:** `https://qle1yy2ydc.execute-api.ap-southeast-1.amazonaws.com/V1`

#### Tags

- Stores
- Restaurant
- Availability

#### Properties

- [Documentation](https://onlineorderingapisv210.docs.apiary.io/)
- [OpenAPI](openapi/petpooja-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/petpooja.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/petpooja.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Petpooja Stock / Availability API

Mark menu items in stock or out of stock via the item in_stock flag so partner platforms reflect live availability against Petpooja POS inventory. Exact stock-toggle endpoint path and schema are not publicly reconciled.

- **Human URL:** [https://onlineorderingapisv210.docs.apiary.io/](https://onlineorderingapisv210.docs.apiary.io/)
- **Base URL:** `https://qle1yy2ydc.execute-api.ap-southeast-1.amazonaws.com/V1`

#### Tags

- Stock
- Availability
- In Stock

#### Properties

- [Documentation](https://onlineorderingapisv210.docs.apiary.io/)
- [OpenAPI](openapi/petpooja-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/petpooja.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/petpooja.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Petpooja Callbacks API

Partner-hosted endpoints that Petpooja calls. The order callback_url receives order-status updates (e.g., Accept / Reject / Food Ready), and the Push Menu endpoint receives full menu payloads when a restaurant updates its catalog.

- **Human URL:** [https://onlineorderingapisv210.docs.apiary.io/](https://onlineorderingapisv210.docs.apiary.io/)
- **Base URL:** `https://onlineorderingapisv210.docs.apiary.io`

#### Tags

- Callbacks
- Webhooks
- Order Status

#### Properties

- [Documentation](https://onlineorderingapisv210.docs.apiary.io/)
- [OpenAPI](openapi/petpooja-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/petpooja.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/petpooja.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/petpooja)
- [Website](https://www.petpooja.com)
- [Documentation](https://onlineorderingapisv210.docs.apiary.io/)
- [Plans](plans/petpooja-plans-pricing.yml)
- [Rate Limits](rate-limits/petpooja-rate-limits.yml)
- [Fin Ops](finops/petpooja-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
