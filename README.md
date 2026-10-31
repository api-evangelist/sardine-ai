# Sardine

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

Sardine is a San Francisco-based fraud prevention, AML compliance, and risk management platform for fintechs, banks, marketplaces, and crypto VASPs. It unifies onboarding (KYC, KYB, document and bank verification), device intelligence and behavioral biometrics, payment and card fraud scoring, AML transaction monitoring, sanctions screening, and case management into a single risk operating system. Sardine's "agentic" layer applies atomic agents (OSINT, data analysis, transaction monitoring, business due diligence, sanctions screening) to compress investigation time from days to minutes, while Sonar provides cross-industry fraud intelligence across the consortium. The platform serves 400+ enterprise customers including FIS, GoDaddy, Intuit, Nubank, Novo, and bunq, has screened $1.3T+ in payments, and profiled 5.4B+ devices. Sardine has raised ~$170M from Andreessen Horowitz, Visa, Experian, Google Ventures, FIS, and others. Public docs cover the risk landscape and integration overview; full API reference, SDKs, and sandbox access are gated and require a Sardine account.

**Areas:** Fraud Prevention · AML · Compliance · KYC · KYB · Identity Verification · Transaction Monitoring · Device Intelligence · Behavioral Biometrics · Risk Management · Financial Crime · AI Agents

## Sardine on APIs.io

Everything profiled for Sardine is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/sardine-ai/](https://apis.io/providers/sardine-ai/)** — or go straight to one of the APIs or properties below.

### APIs (6)

- [Sardine Customer API](https://apis.io/apis/sardine-ai/sardine-customer-api/) — Submit customer profile and onboarding signals (KYC, KYB, document verification, sanctions/PEP screening, identity fraud, synthetic ID detection, behavioral…
- [Sardine Device Intelligence API](https://apis.io/apis/sardine-ai/sardine-device-api/) — Capture device, network, and behavioral signals from web, iOS, and Android SDKs and resolve them to a Sardine device session for downstream scoring. Powers…
- [Sardine Transaction API](https://apis.io/apis/sardine-ai/sardine-transaction-api/) — Submit payment, ACH, wire, card, and crypto transactions for real-time fraud scoring and AML transaction monitoring. Backs Sardine's card chargeback…
- [Sardine Issuing API](https://apis.io/apis/sardine-ai/sardine-issuing-api/) — Real-time card authorization fraud scoring for card issuers. Returns an approve/decline/step-up recommendation on each authorization event using Sardine's…
- [Sardine Crypto API](https://apis.io/apis/sardine-ai/sardine-crypto-api/) — Crypto-specific risk and compliance APIs covering wallet screening, on-chain attribution, and Travel Rule messaging for VASPs (Virtual Asset Service…
- [Sardine Case Management API](https://apis.io/apis/sardine-ai/sardine-case-management-api/) — Programmatic access to Sardine's unified case management surface for fraud and AML investigations. Cases are routed through Sardine's "atomic agents" —…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Sardine Ai Domain Security](https://apis.io/security/sardine-ai/sardine-ai-domain-security/)
- [Sardine Ai Trust Center](https://apis.io/security/sardine-ai/sardine-ai-trust-center/)
- [Sardine Ai Vulnerability Disclosure](https://apis.io/security/sardine-ai/sardine-ai-vulnerability-disclosure/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.sardine.ai/)
- [Documentation](https://docs.sardine.ai)
- [Getting started](https://docs.sardine.ai/guides/public/getting-started/getting-started)
- [Pricing](https://www.sardine.ai/pricing)
- [Support](https://www.sardine.ai/contact)
- [Blog](https://www.sardine.ai/blog)
- [Trust centre](https://security.sardine.ai)
- [GitHub](https://github.com/sardine-ai)
- [Status](https://status.sardine.ai)

## API Evangelist rating

**Kin Score 20.0** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 0.0 |
| Contract governance | 0.0 |
| Operational transparency | 21.1 |
| Developer ergonomics | 38.1 |
| Access clarity | 18.4 |

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

**Regulatory alignment 16.0** — AI & Biometrics

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/sardine-ai/](https://apis.io/providers/sardine-ai/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Sardine: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/sardine-ai/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
