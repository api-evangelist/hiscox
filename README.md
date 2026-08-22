# Hiscox (hiscox)

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

Hiscox Ltd is a diversified international specialist insurance and reinsurance group with roots in the Lloyd's of London market dating to 1901, domiciled in Bermuda and listed on the London Stock Exchange, operating from 31 offices across 13 countries. Its home market is the United Kingdom, where it underwrites through three segments: Hiscox Retail (small business, professional and specialty personal lines sold direct and through brokers in the UK, Europe and the USA), Hiscox London Market (larger and more complex specialty risks written out of London for a worldwide client base, including marine, energy, aviation, specialty property and casualty, and cyber), and Hiscox Re & ILS (reinsurance and insurance-linked securities).

Its API posture is partner-gated rather than public. Hiscox operates a genuine first-party developer portal at [developer.hiscox.com](https://developer.hiscox.com/) serving its US small-business arm, and that portal publicly enumerates three active APIs — Eligibility, Quote v4 and Setup Payment — but every reference document, sandbox credential and OpenAPI/Swagger file sits behind a login that is only issued after a Hiscox Partnership Manager approves a commercial partnership. There is no self-serve signup, no downloadable specification, no public claims or FNOL API, and no developer surface at all on the UK or London Market side of the group, where business is placed through brokers.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/hiscox/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/hiscox/refs/heads/main/apis.yml)

## Tags

- Insurance
- United Kingdom
- Property and Casualty
- Specialty Insurance
- Cyber Insurance
- Underwriting
- Reinsurance
- Lloyd's of London
- Small Business Insurance
- Quote
- ACORD
- Carrier

## Timestamps

- **Created:** 2026-07-25
- **Modified:** 2026-07-25

## APIs

### Hiscox Eligibility API

Partner-facing eligibility lookup that returns the list of US states and the Hiscox products offered by profession, used to determine whether a risk can be quoted before a quote is requested. Listed as Active on the public Hiscox Developer Portal API catalog; reference documentation and the OpenAPI/Swagger definition are behind the partner login and were not retrievable.

- **Human URL:** [https://developer.hiscox.com/apis](https://developer.hiscox.com/apis)

#### Tags

- Eligibility
- Underwriting
- Insurance

#### Properties

- [Documentation](https://developer.hiscox.com/apis)
- [API Reference](https://developer.hiscox.com/documentation) — login required

### Hiscox Quote API v4

Partner-facing quoting API that returns a competitive general liability, professional liability, business owner's policy (BOP) and/or cyber quote for purchase via partner portals or APIs. Listed as Active on the public Hiscox Developer Portal API catalog; access is granted only after approval by a Hiscox Partnership Manager, and the reference documentation and OpenAPI/Swagger definition are behind the partner login.

- **Human URL:** [https://developer.hiscox.com/apis](https://developer.hiscox.com/apis)

#### Tags

- Quote
- Rating
- Property and Casualty
- Cyber Insurance

#### Properties

- [Documentation](https://developer.hiscox.com/apis)
- [API Reference](https://developer.hiscox.com/documentation) — login required

### Hiscox Setup Payment API

Partner-facing payment API that initiates the Hiscox policy payment process, completing the quote-to-buy flow for partner-distributed small business policies. Listed as Active on the public Hiscox Developer Portal API catalog; reference documentation and the OpenAPI/Swagger definition are behind the partner login.

- **Human URL:** [https://developer.hiscox.com/apis](https://developer.hiscox.com/apis)

#### Tags

- Payments
- Bind
- Billing

#### Properties

- [Documentation](https://developer.hiscox.com/apis)
- [API Reference](https://developer.hiscox.com/documentation) — login required

## API Posture

| Signal | Finding |
| --- | --- |
| Developer portal | [https://developer.hiscox.com/](https://developer.hiscox.com/) — HTTP 200, real first-party portal |
| Self-serve? | No. Documentation is a login wall; access requires Partnership Manager approval |
| OpenAPI harvested | 0 — the FAQ places the Swagger/OpenAPI spec inside the gated SDBX sandbox |
| Auth model | OAuth 2.0, TLS 1.2 only, REST with XML and JSON payloads |
| Quote / Bind / Issue / FNOL | Quote and Buy (bind + payment) exposed to partners; no public claims or FNOL API |
| Webhooks / AsyncAPI | None published |
| Postman | No first-party workspace; one unverified third-party "Hiscox API" workspace exists |
| ACORD posture | ACORD digital accounting and invoicing live via the ACORD ADEPT receiver portal (Howden, UK retail, July 2025) |
| Home market | United Kingdom — note the developer portal serves Hiscox Inc. (US small business); the UK and London Market books have no developer surface |

## Common Properties

- [Website](https://www.hiscoxgroup.com/)
- [Developer Portal](https://developer.hiscox.com/)
- [API Catalog](https://developer.hiscox.com/apis)
- [FAQ](https://developer.hiscox.com/frequently-asked-questions)
- [Support](https://developer.hiscox.com/support)
- [Terms of Use](https://developer.hiscox.com/terms-use)
- [Privacy Policy](https://www.hiscox.com/privacy-policy)
- [Login / Request Access](https://developer.hiscox.com/login)
- [GitHub Organization](https://github.com/hiscox)
- [LinkedIn](https://www.linkedin.com/company/hiscox)

## Maintainers

- Kin Lane — kin@apievangelist.com
