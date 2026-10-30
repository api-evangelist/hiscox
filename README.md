# Hiscox

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

Hiscox Ltd is a diversified international specialist insurance and reinsurance group with roots in the Lloyd's of London market dating to 1901, domiciled in Bermuda and listed on the London Stock Exchange, operating from 31 offices across 13 countries. Its home market is the United Kingdom, where it underwrites through three segments: Hiscox Retail (small business, professional and specialty personal lines sold direct and through brokers in the UK, Europe and the USA), Hiscox London Market (larger and more complex specialty risks written out of London for a worldwide client base, including marine, energy, aviation, specialty property and casualty, and cyber), and Hiscox Re & ILS (reinsurance and insurance-linked securities). Its API posture is partner-gated rather than public. Hiscox operates a genuine first-party developer portal at developer.hiscox.com serving its US small-business arm, and that portal publicly enumerates three active APIs - Eligibility, Quote v4 and Setup Payment - but every reference document, sandbox credential and OpenAPI/Swagger file sits behind a login that is only issued after a Hiscox Partnership Manager approves a commercial partnership. There is no self-serve signup, no downloadable specification and no public claims or FNOL API. The group does ship APIs outside that portal: Hiscox London Market launched a Cargo API for small cargo and stock throughput risks in June 2025, built in-house and distributed through broker partners as coverholders, but it has no developer portal listing, no documentation and no specification - it is announced through the newsroom and reached through a broker partnership. Authentication is OAuth 2.0 plus a partner-issued API key over TLS 1.2 only, all APIs are REST, and both XML and JSON are supported. Hiscox's most concrete open-standards footprint is ACORD rather than REST: in July 2025 ACORD and Howden announced that ACORD Standards for digital accounting and invoicing went live in the UK retail insurance market with Hiscox as the receiving insurer, responding in real time to Howden's digital invoices through the ACORD Solutions Group ADEPT (ACORD Data Exchange Platform & Translator) receiver portal.

**Areas:** Insurance · United Kingdom · Property and Casualty · Specialty Insurance · Cyber Insurance · Underwriting · Reinsurance · Lloyd's of London · Small Business Insurance · Quotes · ACORD · Carrier

## Hiscox on APIs.io

Everything profiled for Hiscox is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/hiscox/](https://apis.io/providers/hiscox/)** — or go straight to one of the APIs or properties below.

### APIs (4)

- [Hiscox Eligibility API](https://apis.io/apis/hiscox/hiscox-eligibility-api/) — Partner-facing eligibility lookup that returns the list of US states and the Hiscox products offered by profession, used to determine whether a risk can be…
- [Hiscox Quote API v4](https://apis.io/apis/hiscox/hiscox-quote-api/) — Partner-facing quoting API that returns a competitive general liability, professional liability, business owner's policy (BOP) and/or cyber quote for…
- [Hiscox Setup Payment API](https://apis.io/apis/hiscox/hiscox-setup-payment-api/) — Partner-facing payment API that initiates the Hiscox policy payment process, completing the quote-to-buy flow for partner-distributed small business…
- [Hiscox Cargo API](https://apis.io/apis/hiscox/hiscox-cargo-api/) — Hiscox London Market API-based solution for underwriting small cargo and stock throughput risks, launched 30 June 2025 and distributed through broker…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Hiscox Authentication](https://apis.io/security/hiscox/hiscox-authentication/)
- [Hiscox Domain Security](https://apis.io/security/hiscox/hiscox-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.hiscoxgroup.com/)
- [Documentation](https://developer.hiscox.com/)
- [Getting started](https://developer.hiscox.com/support)
- [API reference](https://developer.hiscox.com/apis)
- [Sign up](https://developer.hiscox.com/login)
- [Support](https://developer.hiscox.com/support)
- [Blog](https://www.hiscoxgroup.com/news/blog)
- [Compliance](https://www.hiscoxgroup.com/news/blog/hiscox-gains-cyber-essentials-plus-accreditation)
- [Terms of service](https://developer.hiscox.com/terms-use)
- [Privacy policy](https://www.hiscox.com/privacy-policy)
- [GitHub](https://github.com/hiscox)

## API Evangelist rating

**Kin Score 31.5** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 0.0 |
| Contract governance | 18.2 |
| Operational transparency | 2.6 |
| Developer ergonomics | 64.3 |
| Access clarity | 42.1 |

**Agent readiness 2.5** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
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

**Regulatory alignment 26.3** — Insurance

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/hiscox/](https://apis.io/providers/hiscox/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Hiscox: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/hiscox/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
