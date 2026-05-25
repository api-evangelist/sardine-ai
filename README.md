# Sardine (sardine-ai)
Sardine is a San Francisco-based fraud prevention, AML compliance, and risk management platform for fintechs, banks, marketplaces, and crypto VASPs. It unifies onboarding (KYC, KYB, document and bank verification), device intelligence and behavioral biometrics, payment and card fraud scoring, AML transaction monitoring, sanctions screening, and case management into a single risk operating system. Sardine's agentic layer applies atomic agents — OSINT, data analysis, transaction monitoring, business due diligence, and sanctions screening — to compress investigation time from days to minutes, while the Sonar consortium shares fraud intelligence across customers. The platform serves 400+ enterprise customers (FIS, GoDaddy, Intuit, Nubank, Novo, bunq, Coastal, Experian, Kalshi, Ascensus, Gusto, Deel, SeatGeek, Whop, LHV), has screened $1.3T+ in payments, and profiled 5.4B+ devices. Sardine has raised ~$170M from Andreessen Horowitz, Visa, Experian, Google Ventures, FIS, Activant Capital, Moody's Analytics, Geodesic Capital, and Nyca Partners.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/sardine-ai/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - Fraud Prevention, AML, Compliance, KYC, KYB, Identity Verification, Transaction Monitoring, Device Intelligence, Behavioral Biometrics, Risk, Financial Crime, Agentic AI, Fintech

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## Documentation Access

Sardine maintains two tiers of documentation:

- **Public docs** at [docs.sardine.ai](https://docs.sardine.ai) — risk-category overviews, integration overview, billing model, and the [llms.txt index](https://docs.sardine.ai/llms.txt). No machine-readable API surface is published publicly.
- **Protected docs** — step-by-step integration guides, full API reference, SDKs, sandbox credentials, and sample apps. Requires a Sardine dashboard login. Request access from a Sardine representative or via [risksupport@sardine.ai](mailto:risksupport@sardine.ai).

This profile catalogs Sardine's API surface from public documentation, the [Sardine status page](https://status.sardine.ai) service inventory, and the [llms.txt](https://docs.sardine.ai/llms.txt) index. No placeholder OpenAPI specs, JSON Schemas, or capabilities are generated because no public machine-readable surface exists.

## APIs

### Sardine Customer API
Submit customer profile and onboarding signals (KYC, KYB, document verification, sanctions/PEP screening, identity fraud, synthetic ID detection, behavioral biometrics, device intelligence) and receive a real-time risk decision. The primary onboarding surface used by banks, fintechs, crypto exchanges, and marketplaces to verify individuals and businesses globally.

**Human URL:** [https://docs.sardine.ai](https://docs.sardine.ai)

- [Documentation — Account Risk](https://docs.sardine.ai/guides/public/risk/account-risk/account-risk)
- [Documentation — KYB](https://docs.sardine.ai/guides/public/risk/account-risk/kyb)
- [Documentation — API Access](https://docs.sardine.ai/guides/public/getting-started/apiaccess)

### Sardine Device Intelligence API
Capture device, network, and behavioral signals from web, iOS, and Android SDKs and resolve them to a Sardine device session for downstream scoring. Powers account takeover protection, bot detection, deepfake/synthetic identity flags, and policy abuse prevention. Sardine reports having profiled 5.4B+ devices across its consortium.

**Human URL:** [https://docs.sardine.ai](https://docs.sardine.ai)

- [Documentation — What Powers Sardine](https://docs.sardine.ai/guides/public/getting-started/what-powers-sardine)
- [Documentation — Account Takeover](https://docs.sardine.ai/guides/public/risk/account-risk/account-takeover)

### Sardine Transaction API
Submit payment, ACH, wire, card, and crypto transactions for real-time fraud scoring and AML transaction monitoring. Backs Sardine's card chargeback guarantee program and ACH indemnification for unauthorized returns (R05, R07, R10, R11, R29). Sardine reports having screened $1.3T+ in payments.

**Human URL:** [https://docs.sardine.ai](https://docs.sardine.ai)

- [Documentation — Funding Risk](https://docs.sardine.ai/guides/public/risk/funding-risk/funding-risk)
- [Documentation — ACH Indemnification](https://docs.sardine.ai/guides/public/risk/funding-risk/ach-indemnification)
- [Documentation — Card Chargeback Guarantee](https://docs.sardine.ai/guides/public/risk/funding-risk/card-indemnification)
- [Documentation — Transaction Monitoring](https://docs.sardine.ai/guides/public/risk/transaction-monitoring/transaction-monitoring)

### Sardine Issuing API
Real-time card authorization fraud scoring for card issuers. Returns an approve/decline/step-up recommendation on each authorization event using Sardine's issuer-specific ML models and configurable rules. Tracked as a separate service surface on the Sardine status page.

**Human URL:** [https://docs.sardine.ai](https://docs.sardine.ai)

- [Documentation — Card Spending Risk](https://docs.sardine.ai/guides/public/risk/card-spending-risk/card-spending)

### Sardine Crypto API
Crypto-specific risk and compliance APIs covering wallet screening, on-chain attribution, and Travel Rule messaging for VASPs (Virtual Asset Service Providers). Tracked as Crypto APIs and Crypto Web on the Sardine status page.

**Human URL:** [https://docs.sardine.ai](https://docs.sardine.ai)

- [Documentation — Risk Overview](https://docs.sardine.ai/guides/public/risk/overview)

### Sardine Case Management API
Programmatic access to Sardine's unified case management surface for fraud and AML investigations. Cases are routed through Sardine's atomic agents — OSINT search, data analysis, transaction monitoring, business due diligence, and sanctions screening — to compress investigation time from days to minutes. Backs the Agentic AML Ops and Agentic Fraud Ops products.

**Human URL:** [https://docs.sardine.ai](https://docs.sardine.ai)

- [Documentation — Transaction Monitoring](https://docs.sardine.ai/guides/public/risk/transaction-monitoring/transaction-monitoring)

## Common Properties

- [Portal — sardine.ai](https://www.sardine.ai)
- [Documentation — docs.sardine.ai](https://docs.sardine.ai)
- [Documentation — LLMs.txt Index](https://docs.sardine.ai/llms.txt)
- [GettingStarted — Getting Started With Risk](https://docs.sardine.ai/guides/public/getting-started/getting-started)
- [Documentation — Get Full Documentation Access](https://docs.sardine.ai/guides/public/getting-started/apiaccess)
- [Documentation — Integration Overview](https://docs.sardine.ai/guides/public/getting-started/integration-overview)
- [Documentation — What Powers Sardine](https://docs.sardine.ai/guides/public/getting-started/what-powers-sardine)
- [Documentation — How Sardine Bills](https://docs.sardine.ai/guides/public/getting-started/how-sardine-bills)
- [Documentation — Common Risk Problems](https://docs.sardine.ai/guides/public/getting-started/common-risk-problems)
- [Documentation — Risk Categories Overview](https://docs.sardine.ai/guides/public/risk/overview)
- [Documentation — Business Risk Operating System](https://docs.sardine.ai/guides/public/risk/business-risk/about-business-risk)
- [StatusPage](https://status.sardine.ai)
- [TrustCenter — Security Portal](https://security.sardine.ai)
- [Support — Contact](https://www.sardine.ai/contact)
- [Support — risksupport@sardine.ai](mailto:risksupport@sardine.ai)
- [AboutUs](https://www.sardine.ai/about)
- [CustomerCaseStudies](https://www.sardine.ai/customers)
- [Blog](https://www.sardine.ai/blog)
- [Careers](https://www.sardine.ai/careers)
- [LinkedIn](https://www.linkedin.com/company/sardine-ai)
- [Twitter](https://x.com/sardine)
- [GitHubOrganization — sardine-ai](https://github.com/sardine-ai)
- [Tool — Sardine OpenAPI MCP Server](https://github.com/sardine-ai/openapi-mcp-server)
- [Tool — Sardine MCP Server Manager](https://github.com/sardine-ai/mcp-server-manager)
- [Tool — Chronon (data platform for AI/ML)](https://github.com/sardine-ai/chronon)
- [Documentation — Sardine Mintlify Docs Source](https://github.com/sardine-ai/mintlify-docs)
- [Pricing — contact sales](https://www.sardine.ai/pricing)

## Status Page Service Inventory

The [Sardine status page](https://status.sardine.ai) tracks uptime for the following service surfaces, which align with the API groupings in this profile:

- Customer APIs
- Device APIs
- Issuing API
- Crypto APIs
- Crypto Web (external provider)
- Dashboard

## GitHub Organization Highlights

The [sardine-ai](https://github.com/sardine-ai) GitHub org has 55 public repositories, most of which are forks of GitHub Actions and developer tooling used in Sardine's own CI/CD. The notable original repositories are:

- [chronon](https://github.com/sardine-ai/chronon) — Scala data platform for serving ML applications (originally authored by Stripe; Sardine maintains a fork).
- [openapi-mcp-server](https://github.com/sardine-ai/openapi-mcp-server) — Wraps complex OpenAPI specs as an MCP server so AI agents can navigate them in plain language.
- [mcp-server-manager](https://github.com/sardine-ai/mcp-server-manager) — TypeScript MCP server manager.
- [mintlify-docs](https://github.com/sardine-ai/mintlify-docs) — Source for the Mintlify-hosted docs site at docs.sardine.ai.
- [zipline-chronon](https://github.com/sardine-ai/zipline-chronon) — Scala companion to chronon.

No public SDK repositories (e.g., `sardine-sdk-python`, `sardine-sdk-typescript`) are published in the org — SDKs and sample apps are distributed through the gated developer portal.

## Pricing and Billing Model

Sardine does not publish a self-serve price list. Pricing is enterprise/contract-based and product-specific (per-decision for risk APIs, per-device-session for device intelligence, per-investigation/case for AML ops, plus indemnification/guarantee programs that price as insurance). The public [How Sardine Bills](https://docs.sardine.ai/guides/public/getting-started/how-sardine-bills) page explains the billing model at a conceptual level. Plans, rate limits, and FinOps artifacts are not generated for this profile because the underlying commercial surface is not publicly documented.

## Artifacts

Sardine does not publish public OpenAPI, JSON Schema, JSON-LD, capability, plans, rate-limits, or FinOps artifacts. The full API reference, SDKs, and sandbox access are gated behind a Sardine account at [docs.sardine.ai](https://docs.sardine.ai). Per the API Evangelist pipeline policy (no placeholder specs), no machine-readable artifact folders are created in this repository.

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
