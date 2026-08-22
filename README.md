# Okra (okra-ng)

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
