# Petpooja (petpooja)

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
