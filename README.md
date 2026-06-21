# Okra (okra-ng)

Okra was an African open-finance / open-banking infrastructure company based in Lagos, Nigeria. Its REST API connected applications to Nigerian bank accounts to retrieve authentication details, balances, transactions, identity, and income data, and to initiate bank-to-bank payments, with a Link widget and webhooks. Okra wound down operations in May 2025; this catalog documents the API as it was publicly published.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/okra-ng/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/okra-ng/refs/heads/main/apis.yml)

## Tags

- Open Banking
- Open Finance
- Fintech
- Africa
- Nigeria
- Financial Data

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Okra Auth & Link API

Connects a customer's bank account via the Okra Link widget and retrieves authentication records - account and NUBAN numbers across current, savings, and domiciliary accounts - filterable by id, customer, bank, and date.

- **Human URL:** [https://docs.okra.ng/reference](https://docs.okra.ng/reference)
- **Base URL:** `https://api.okra.ng/v2`

#### Tags

- Auth
- Link
- Account Linking

#### Properties

- [Documentation](https://docs.okra.ng/docs/auth)
- [API Reference](https://docs.okra.ng/reference)
- [OpenAPI](openapi/okra-ng-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/okra-ng.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/okra-ng.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Okra Accounts & Balance API

Retrieves a record's linked accounts and real-time ledger and available balances, filterable by id, customer, account, balance type, and date range.

- **Human URL:** [https://docs.okra.ng/account-data/balance](https://docs.okra.ng/account-data/balance)
- **Base URL:** `https://api.okra.ng/v2`

#### Tags

- Accounts
- Balance
- Financial Data

#### Properties

- [Documentation](https://docs.okra.ng/docs/balance)
- [API Reference](https://docs.okra.ng/reference)
- [OpenAPI](openapi/okra-ng-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/okra-ng.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/okra-ng.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Okra Transactions API

Returns customer-authorized transaction history of up to 24 months across current, savings, and domiciliary accounts, filterable by customer, account, bank, and date, plus a spending-pattern analysis endpoint.

- **Human URL:** [https://docs.okra.ng/reference](https://docs.okra.ng/reference)
- **Base URL:** `https://api.okra.ng/v2`

#### Tags

- Transactions
- History
- Financial Data

#### Properties

- [Documentation](https://docs.okra.ng/docs/overview)
- [API Reference](https://docs.okra.ng/reference)
- [OpenAPI](openapi/okra-ng-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/okra-ng.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/okra-ng.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Okra Identity & Income API

Retrieves KYC identity on file with the bank (names, emails, phone numbers, addresses) and verifies a customer's income data drawn from their connected accounts.

- **Human URL:** [https://docs.okra.ng/docs/validate-customers](https://docs.okra.ng/docs/validate-customers)
- **Base URL:** `https://api.okra.ng/v2`

#### Tags

- Identity
- Income
- KYC

#### Properties

- [Documentation](https://docs.okra.ng/docs/validate-customers)
- [API Reference](https://docs.okra.ng/reference)
- [OpenAPI](openapi/okra-ng-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/okra-ng.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/okra-ng.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Okra Payments API

Collects one-time and recurring bank-to-bank payments via USSD and internet banking, creates instant and future payments, retrieves and verifies payment status, and supports bulk debits via CSV upload.

- **Human URL:** [https://okra.ng/products/payments](https://okra.ng/products/payments)
- **Base URL:** `https://api.okra.ng/v2`

#### Tags

- Payments
- Bank to Bank
- Direct Debit

#### Properties

- [Documentation](https://okra.ng/products/payments)
- [API Reference](https://docs.okra.ng/reference)
- [OpenAPI](openapi/okra-ng-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/okra-ng.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/okra-ng.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Okra Webhooks API

Delivers asynchronous callbacks to a configured callback_url when Okra finishes processing a product's data for a Record, and lets you re-trigger callbacks for a set of record ids.

- **Human URL:** [https://blog.okra.ng/understanding-webhooks/](https://blog.okra.ng/understanding-webhooks/)
- **Base URL:** `https://api.okra.ng/v2`

#### Tags

- Webhooks
- Callbacks
- Events

#### Properties

- [Documentation](https://blog.okra.ng/understanding-webhooks/)
- [API Reference](https://docs.okra.ng/reference)
- [OpenAPI](openapi/okra-ng-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/okra-ng.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/okra-ng.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/okraHQ)
- [LinkedIn](https://www.linkedin.com/company/okra-technologies)
- [Website](https://okra.ng/)
- [Documentation](https://docs.okra.ng/)
- [Plans](plans/okra-ng-plans-pricing.yml)
- [Rate Limits](rate-limits/okra-ng-rate-limits.yml)
- [Fin Ops](finops/okra-ng-finops.yml)

## Status

Okra wound down operations in May 2025. Both the core open-banking API business and its Nebula cloud product were discontinued, and a UK firm (Kernel) acquired remaining assets. No official public shutdown statement was issued. The documentation and API endpoints referenced in this catalog may no longer be live; they are documented here as they were publicly published.

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
