# M&T Bank (m-t-bank)

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
