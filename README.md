# Cashflows (cashflows)

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
