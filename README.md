# Cashflows (cashflows)

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

Cashflows is a United Kingdom payment gateway and card acquirer, headquartered in London and a principal member of Visa and Mastercard, that helps businesses accept, process, and manage card payments across online, in-app, and in-person channels. It ships a genuine self-serve developer portal at [developer.cashflows.com](https://developer.cashflows.com/) with reference documentation, a dedicated integration/sandbox environment, and webhook-based payment notifications. Its API reference is hand-authored HTML — there is no downloadable OpenAPI/Swagger definition or public Postman collection. Authentication is header-based (ConfigurationId plus a SHA-512 request hash for the Gateway; auth_id/auth_pass for Remote Authentication).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cashflows/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cashflows/refs/heads/main/apis.yml)

## Tags

- Payments
- United Kingdom
- Payment Gateway
- Payment Processing
- Acquiring
- Card Payments
- In-Person Payments
- 3-D Secure
- Recurring Payments
- Webhooks

## Timestamps

- **Created:** 2026-07-24
- **Modified:** 2026-07-24

## APIs

### Cashflows Gateway API

REST API for creating and managing payment jobs and payments — create, retrieve, and cancel payment jobs; capture, refund, and cancel individual payments; card tokenisation; and recurring payments. Payment status changes are delivered asynchronously via webhook notifications (retried for up to a month).

- **Human URL:** [https://developer.cashflows.com/api_reference/cashflows_gateway.html](https://developer.cashflows.com/api_reference/cashflows_gateway.html)
- **Base URL:** `https://gateway.cashflows.com/api/gateway`

#### Properties

- [Documentation](https://developer.cashflows.com/gateway/cashflows_gateway.html)
- [API Reference](https://developer.cashflows.com/api_reference/cashflows_gateway.html)

### Cashflows Payments API

REST/JSON API for cardholder-not-present card payments with 3-D Secure support — authorisation, capture, void, refund, credit, IIN lookup, and 3-D Secure version 2 authentication and verification flows.

- **Human URL:** [https://developer.cashflows.com/api_reference/payments.html](https://developer.cashflows.com/api_reference/payments.html)

#### Properties

- [Documentation](https://developer.cashflows.com/onlinepayments)
- [API Reference](https://developer.cashflows.com/api_reference/payments.html)

### Cashflows Remote Authentication API

API for connecting directly to the Cashflows acquiring network to authorise card transactions, authenticated with auth_id and auth_pass credential headers.

- **Human URL:** [https://developer.cashflows.com/api_reference/remote_auth_api.html](https://developer.cashflows.com/api_reference/remote_auth_api.html)
- **Base URL:** `https://secure.cashflows.com/gateway/remote_auth`

#### Properties

- [API Reference](https://developer.cashflows.com/api_reference/remote_auth_api.html)

### Cashflows In-Person Payments API

Standalone REST API for PCI-PTS secure Kinetic payment devices, served locally from the terminal (default `http://127.0.0.1:8080`) under `/api/v2` — device info, ping/status, settings, transactions, screens, receipts, and printing.

- **Human URL:** [https://developer.cashflows.com/api_reference/ipp.html](https://developer.cashflows.com/api_reference/ipp.html)
- **Base URL:** `http://127.0.0.1:8080/api/v2`

#### Properties

- [API Reference](https://developer.cashflows.com/api_reference/ipp.html)

## Common Properties

- [Website](https://www.cashflows.com/)
- [Developer Portal](https://developer.cashflows.com/)
- [Documentation](https://developer.cashflows.com/)
- [API Reference](https://developer.cashflows.com/api_reference/api_reference_overview.html)
- [Getting Started](https://developer.cashflows.com/getting_started/getting_started.html)
- [Status Page](https://status.cashflows.com/)
- [Pricing](https://www.cashflows.com/pricing)
- [Blog](https://www.cashflows.com/blog)
- [Support](https://www.cashflows.com/contact/support)
- [Terms of Service](https://www.cashflows.com/legal/terms-and-conditions)
- [Privacy Policy](https://www.cashflows.com/legal/privacy-policy)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
