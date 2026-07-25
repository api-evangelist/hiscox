# Hiscox (hiscox)

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
