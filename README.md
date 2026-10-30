# M&T Bank

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

M&T Bank is a US super-regional bank holding company (M&T Bank Corporation, NYSE: MTB) headquartered in Buffalo, New York, operating through its national bank subsidiary Manufacturers and Traders Trust Company. With roughly $200 billion in assets it is one of the twenty largest US commercial banks, serving consumers, businesses, and institutional clients across the eastern United States, and it owns Wilmington Trust, its custody, fund-administration, and wealth arm. Unlike UK/AU open banking there is no single mandated contract in the US, so M&T's public API posture is split: it runs a real first-party Developer Portal / "API Store" at developer.mtb.com for institutional and wholesale clients (Banking & Treasury plus Wilmington Trust Custody APIs), gated behind Microsoft Entra login and Azure API Management subscription keys with per-product OpenAPI reference available only after authentication. Consumer-permissioned account data is shared through aggregators (Plaid) rather than a public first-party consumer API. No public FDX conformance or CFPB Section 1033 data-access API is documented on the portal at review time.

**Areas:** Financial Services · Banking · United States · Super-Regional Bank · Treasury Management · Payments · Custody · Fund Accounting · Open Finance

## M&T Bank on APIs.io

Everything profiled for M&T Bank is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/m-t-bank/](https://apis.io/providers/m-t-bank/)** — or go straight to one of the APIs or properties below.

### APIs (10)

- [Payment Initiation API](https://apis.io/apis/m-t-bank/payment-initiation/) — Institutional payment initiation product listed in M&T's Banking and Treasury API group on the developer portal. Per-product reference is available after…
- [Payment Status API](https://apis.io/apis/m-t-bank/payment-status/) — Payment status lookup product in the Banking and Treasury API group. Reference gated behind portal authentication.
- [Cash Activity API](https://apis.io/apis/m-t-bank/cash-activity/) — Cash activity reporting product in the Banking and Treasury API group for treasury-management clients. Reference gated behind portal authentication.
- [Cash Projection API](https://apis.io/apis/m-t-bank/cash-projection/) — Cash projection / forecasting product in the Banking and Treasury API group. Reference gated behind portal authentication.
- [Pending Transactions API](https://apis.io/apis/m-t-bank/pending-transactions/) — Pending transactions reporting product in the Banking and Treasury API group. Reference gated behind portal authentication.
- [Event Notification API](https://apis.io/apis/m-t-bank/event-notification/) — Event notification setup and subscription product enabling callback/webhook delivery with request signing, listed in the Banking and Treasury API group.…
- [Custody End of Day API](https://apis.io/apis/m-t-bank/custody-end-of-day/) — Wilmington Trust custody end-of-day product for institutional clients, listed in the portal's Custody API group. Reference gated behind portal authentication.
- [Fund Accounting API](https://apis.io/apis/m-t-bank/fund-accounting/) — Fund valuation and accounting product (transfer-agency / fund-administration services) in the Custody API group. Reference gated behind portal authentication.
- [Account Valuations API](https://apis.io/apis/m-t-bank/account-valuations/) — Account valuations product supporting custody and institutional portfolio reporting. Reference gated behind portal authentication.
- [Position Exposure API](https://apis.io/apis/m-t-bank/position-exposure/) — Position exposure product for institutional custody/portfolio clients. Reference gated behind portal authentication.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [M T Bank Domain Security](https://apis.io/security/m-t-bank/m-t-bank-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.mtb.com/)
- [Documentation](https://developer.mtb.com/apis)
- [Getting started](https://developer.mtb.com/getting-started)
- [Support](https://developer.mtb.com/support)
- [Blog](https://newsroom.mtb.com/)
- [Terms of service](https://www.mtb.com/help-center/bank-policies/terms-of-use)
- [Privacy policy](https://www.mtb.com/privacy)

## API Evangelist rating

**Kin Score 11.6** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 69.6 |
| Contract quality | 0.0 |
| Contract governance | 0.0 |
| Operational transparency | 0.0 |
| Developer ergonomics | 2.4 |
| Access clarity | 27.6 |

**Agent readiness 0.0** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 11.0** — Banking & Open Finance

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/m-t-bank/](https://apis.io/providers/m-t-bank/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for M&T Bank: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/m-t-bank/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
