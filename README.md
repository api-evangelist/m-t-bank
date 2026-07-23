# M&T Bank (m-t-bank)

M&T Bank is a US super-regional bank holding company (M&T Bank Corporation, NYSE: MTB) headquartered in Buffalo, New York, operating through its national bank subsidiary Manufacturers and Traders Trust Company and its custody/wealth arm Wilmington Trust. With roughly $200 billion in assets it is one of the twenty largest US commercial banks, serving consumers, businesses, and institutional clients across the eastern United States.

M&T runs a real first-party **Developer Portal / "API Store"** at [developer.mtb.com](https://developer.mtb.com/) aimed at institutional and wholesale clients. It is an Azure API Management portal gated behind Microsoft Entra login and per-app API key + client secret; the individual product OpenAPI references are visible only after authentication. The catalog is organized into a **Banking & Treasury** API group (payments, cash reporting/projection, event notifications) and a **Wilmington Trust Custody** API group (custody end-of-day, fund accounting, valuations, position exposure). Consumer-permissioned account data is shared through aggregators (Plaid) rather than a public first-party consumer API. No public FDX conformance or CFPB Section 1033 data-access API is documented on the portal at review time.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/m-t-bank/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/m-t-bank/refs/heads/main/apis.yml)

## Tags

- Financial Services
- Banking
- United States
- Super-Regional Bank
- Treasury Management
- Payments
- Custody
- Fund Accounting
- Open Finance
- Data Aggregation

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

The following API products are named in M&T's Developer Portal catalog. Human URLs point to the portal's API listing; each product's detailed reference and OpenAPI is available only after Entra login and an Azure APIM subscription.

### Banking and Treasury API Group

- **Payment Initiation API** — institutional payment initiation.
- **Payment Status API** — payment status lookup.
- **Cash Activity API** — cash activity reporting for treasury clients.
- **Cash Projection API** — cash forecasting/projection.
- **Pending Transactions API** — pending transaction reporting.
- **Event Notification API** — callback/webhook setup and subscription with request signing.

### Custody API Group (Wilmington Trust)

- **Custody End of Day API** — custody end-of-day positions and activity.
- **Fund Accounting API** — fund valuation and accounting / transfer-agency services.
- **Account Valuations API** — account valuations for custody/portfolio reporting.
- **Position Exposure API** — position exposure for institutional portfolios.

- **Human URL:** [https://developer.mtb.com/apis](https://developer.mtb.com/apis)
- **Portal:** [https://developer.mtb.com/](https://developer.mtb.com/)

## Common Properties

- [Website](https://www.mtb.com/)
- [Developer Portal](https://developer.mtb.com/)
- [Documentation](https://developer.mtb.com/apis)
- [Getting Started](https://developer.mtb.com/getting-started)
- [Support](https://developer.mtb.com/support)
- [LinkedIn](https://www.linkedin.com/company/m&t-bank)
- [Newsroom / Blog](https://newsroom.mtb.com/)
- [Terms of Service](https://www.mtb.com/help-center/bank-policies/terms-of-use)
- [Privacy Policy](https://www.mtb.com/privacy)
- [Treasury Management](https://www.mtb.com/commercial/treasury-management)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
