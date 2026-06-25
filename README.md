# Bayou Energy (bayou-energy)

Bayou Energy provides a utility-bill and usage-data API that lets companies collect their customers' utility account, bill, and interval meter data from US utilities. Customers link their utility credentials through a hosted onboarding flow, and Bayou continuously fetches the full bill and interval history, exposing it through a REST API secured with HTTP Basic authentication.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/bayou-energy/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/bayou-energy/refs/heads/main/apis.yml)

## Tags

- Utility Data
- Energy
- Utility Bills
- Interval Data
- Metering

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Bayou Energy Customers API

Create and manage customers, generate a hosted onboarding link for the customer to connect their utility credentials, and poll customer status fields such as has_filled_credentials, bills_are_ready, and intervals_are_ready.

- **Human URL:** [https://docs.bayou.energy/reference](https://docs.bayou.energy/reference)
- **Base URL:** `https://bayou.energy/api/v2`

#### Tags

- Customers
- Connections
- Credentials
- Onboarding

#### Properties

- [Documentation](https://docs.bayou.energy/docs/quickstart)
- [API Reference](https://docs.bayou.energy/reference)
- [OpenAPI](openapi/bayou-energy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bayou-energy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bayou-energy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bayou Energy Bills API

Retrieve a customer's utility bills with account numbers, meters, tariffs, billing periods, consumption, and itemized delivery and supply charges; upload, update, and unlock bill data.

- **Human URL:** [https://docs.bayou.energy/docs/data-provided-bills](https://docs.bayou.energy/docs/data-provided-bills)
- **Base URL:** `https://bayou.energy/api/v2`

#### Tags

- Bills
- Utility Bills
- Charges
- Tariffs

#### Properties

- [Documentation](https://docs.bayou.energy/docs/data-provided-bills)
- [API Reference](https://docs.bayou.energy/reference)
- [OpenAPI](openapi/bayou-energy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bayou-energy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bayou-energy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bayou Energy Intervals API

Retrieve a customer's interval meter data organized by meter, returned at 15-minute, hourly, or daily granularity depending on the utility, covering the customer's available usage history.

- **Human URL:** [https://docs.bayou.energy/docs/interval-data-availability](https://docs.bayou.energy/docs/interval-data-availability)
- **Base URL:** `https://bayou.energy/api/v2`

#### Tags

- Intervals
- Usage
- Interval Data
- Meters

#### Properties

- [Documentation](https://docs.bayou.energy/docs/interval-data-availability)
- [API Reference](https://docs.bayou.energy/reference)
- [OpenAPI](openapi/bayou-energy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bayou-energy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bayou-energy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bayou Energy Meters API

Surface meter details across a customer's bills and intervals, and look up supported utilities and their coverage, availability, and performance through the utilities endpoints.

- **Human URL:** [https://www.bayou.energy/utilities](https://www.bayou.energy/utilities)
- **Base URL:** `https://bayou.energy/api/v2`

#### Tags

- Meters
- Utilities
- Coverage

#### Properties

- [Documentation](https://docs.bayou.energy/reference)
- [API Reference](https://docs.bayou.energy/reference)
- [OpenAPI](openapi/bayou-energy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bayou-energy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bayou-energy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bayou Energy Webhooks API

Subscribe to event notifications - customer_has_filled_credentials, customer_must_reauthenticate, new_bill, updated_bill, new_unparsed_bill, bills_ready, and intervals_ready - so production integrations react to data availability instead of polling.

- **Human URL:** [https://docs.bayou.energy/reference](https://docs.bayou.energy/reference)
- **Base URL:** `https://bayou.energy/api/v2`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://docs.bayou.energy/reference)
- [API Reference](https://docs.bayou.energy/reference)
- [OpenAPI](openapi/bayou-energy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bayou-energy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bayou-energy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/bayouenergy)
- [Website](https://www.bayou.energy/)
- [Documentation](https://docs.bayou.energy/)
- [Plans](plans/bayou-energy-plans-pricing.yml)
- [Rate Limits](rate-limits/bayou-energy-rate-limits.yml)
- [Fin Ops](finops/bayou-energy-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
