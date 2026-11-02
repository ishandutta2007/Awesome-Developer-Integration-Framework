# Awesome-Developer-Integration-Framework

# Awesome-Developer-Integration-Framework
**Top Developer Integration Framework (Opensource) 🌟 Star if you like it! 🌟**

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Embedded iPaaS, OAuth Management, Unified APIs, Workflow Automation & Self-Hosted Connectors*
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Developer Integration Frameworks**. These tools enable developers to connect their applications to external APIs, manage OAuth flows, build native integrations for customers, and orchestrate data between systems—from fully managed iPaaS platforms with visual builders to open-source frameworks that give teams control over their integration code and customer data.

**Examples** include MuleSoft Anypoint, Workato, Tray.ai, Zapier, Make, Boomi, Atlassian Connect, Postman, Singer, and Cloud Elements (the category leaders in commercial space).

**Open-source emphasis**: This section is expanded with every relevant project for self-hosted embedded iPaaS, OAuth management, and open integration infrastructure. **Critical note**: The open-source integration landscape has matured—**Nango** provides a single API for 400+ external APIs with OAuth management , **Hotglue** offers 600+ open-source connectors for embedded integrations , and **Terapi** delivers a self-hosted embedded iPaaS. No open-source project matches MuleSoft's enterprise governance or Workato's recipe library, but for developers building native integrations, the open-source options are production-capable.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **MuleSoft Anypoint Platform**
  **Enterprise integration and API management** platform. **Pricing**: **vCore-based**—list price per vCore, with premium connectors adding **15–40%** on top and required for every environment (production, staging, test, sandbox, development, DR) . **Free tier**: **30-day trial** covering full portfolio . **Best for**: large enterprises needing API-led connectivity with governance—**trade-off**: vCore commitments are opaque; unused capacity is common; test smaller worker sizes in sandbox before renewal .

- **Workato**
  **Enterprise automation platform** with recipe-based integrations. **Pricing**: **Free** with **50,000 one-time credits** that never expire; **Pro from $100/month** for 2,500 recurring credits, scaling to **$1,275/month for 50,000 credits**; **no credit rollover**—unused Pro credits expire monthly . **Free tier**: Yes, 50,000 one-time credits. **Best for**: teams wanting self-service automation without sales contact—**trade-off**: credit consumption applies to tasks, API calls, rows processed, and Genie Actions .

- **Tray.ai**
  **Low-code iPaaS for enterprise** with 700+ connectors. **Pricing**: **Quote-only**; three tiers—**Pro** (3 workspaces, individual/small teams), **Team** (20 workspaces, collaboration, version control), **Enterprise** (unlimited workspaces, SSO, log streaming) . Add-ons include **Agent Gateway for MCP** and **Merlin Agent Builder**, both extra cost . **Free tier**: None; sales-led. **Best for**: technical teams building complex multi-system workflows—**trade-off**: no published pricing; agent features add complexity.

- **Zapier**
  **No-code automation** with 9,000+ apps. **Pricing**: **Free** with two-step Zaps; **Professional** adds multi-step, faster polling (2 min); **Team** (25 seats) and **Enterprise** (unlimited seats, advanced governance) . **Free tier**: Yes, two-step Zaps only. **Best for**: non-technical teams wanting simple trigger-action automations—**trade-off**: multi-step and faster polling require paid plans.

- **Make**
  **Visual automation platform** with credit-based pricing. **Pricing**: **Freemium**, **$9/month annual** entry; credits bill per module action, not per task; annual billing lets credits pool across 12 months on Pro+ . **Free tier**: Yes, limited credits. **Best for**: power users wanting visual flows with more control than Zapier—**trade-off**: credit exhaustion pauses scenarios on lower tiers .

- **Boomi**
  **Cloud integration platform** with flexible pricing. **Pricing**: **Subscription plans** (Professional, Professional Plus, Enterprise, Enterprise Plus) plus **usage-based** option; **30-day free trial** with all features . **Free tier**: 30-day trial. **Best for**: organizations wanting consumption-based flexibility—**trade-off**: tier features vary significantly; Enterprise Plus adds messaging.

- **Atlassian Connect**
  **Framework for building Atlassian Cloud apps** that operate remotely over HTTP. Apps can be written in **any language or framework**; Atlassian provides official frameworks handling JWT authentication, host persistence, install/uninstall callbacks, and descriptor serving . **Free tier**: N/A (framework). **Best for**: developers extending Jira/Confluence with remote apps—**trade-off**: not a general integration platform; Atlassian-specific.

- **Postman**
  **API development and testing platform** with collections and mock servers. **Pricing**: Free tier; paid per user. **Free tier**: Yes, limited collection runs. **Best for**: teams wanting a polished API client—**trade-off**: data stored in vendor cloud.

- **Cloud Elements**
  **Embedded integration platform** with Hub APIs and bulk operations. **Pricing**: Quote-only. **Free tier**: None. **Best for**: SaaS vendors wanting standardized APIs across CRM, documents, and other hubs—**trade-off**: bulk APIs have vendor limits and pagination standards .

- **Singer**
  **Open-source ETL standard** for taps and targets. **Pricing**: Free (open source). **Free tier**: Yes. **Best for**: data engineers wanting composable extraction scripts—**trade-off**: Unix-pipe model requires orchestration; not a visual builder .

## Open-Source GitHub Projects

- **Nango**
  **Single API for all integrations** (open source, self-hostable) — **the most practical open-source embedded integration framework**, with **400+ pre-configured APIs** across 25+ categories including accounting (NetSuite, QuickBooks, Xero) . **Features**: **Unified API**—one API to interact with all external APIs; **OAuth management**—`nango.openConnectUI()` initiates auth flows from frontend; **structured objects**—`nango.listRecords<GithubIssue>({ providerConfigKey: 'github', connectionId, model })` ; **pre-built, custom, and managed integrations**; originally derived from Pizzly (OAuth service) . **Tech stack**: TypeScript. **Deploy**: Self-hosted or Nango Cloud. **Trade-off**: **Unified API abstraction**—requires mapping external schemas; less flexible than raw API calls for edge cases. **Best for**: SaaS products wanting to offer native integrations to customers without building each OAuth flow and API wrapper from scratch—the most developer-friendly open-source embedded iPaaS.

- **Hotglue**
  **Embedded iPaaS with 600+ open-source connectors** (open source, self-hostable) — **the most connector-rich open-source embedded integration platform**, built on Python . **Features**: **600+ open-source connectors**; **code-first approach**—no lock-in of traditional iPaaS; **CLI for programmatic configuration management**; **detailed job logs, webhooks, and observability integrations**; **embedded integrations** for SaaS products offering native connectors to customers . **Tech stack**: Python. **Deploy**: Self-hosted or Hotglue Cloud. **Trade-off**: **Python-centric**—less flexible for non-Python teams; smaller community than Nango. **Best for**: teams wanting maximum connector coverage with code-first control—especially those already in the Python ecosystem.

- **Terapi**
  **Open-source embedded integration platform** (self-hosted iPaaS) — **the most complete self-hosted iPaaS architecture** for SaaS products, created March 2026 . **Features**: **Pre-built connectors and unified APIs**; **authentication management**—handles OAuth and connection lifecycle; **connection handling and synchronization**; **workflow automation**; **REST API** for authentication management, connection handling, synchronization, and triggering actions across integrated services . **Tech stack**: Per repository. **Deploy**: Self-hosted. **Trade-off**: **Newer project** (created March 2026)—limited community validation; documentation still maturing. **Best for**: SaaS vendors wanting a self-hosted embedded iPaaS foundation—willing to evaluate an early-stage but architecturally complete option.

- **ByteChef**
  **Embedded API integration and workflow automation** (open source, with Embedded modules) — **the most modular open-source embedded iPaaS** for building native product integrations . **Features**: **ByteChef Embedded** modules define core infrastructure for embedded API integration and workflow automation; designed for SaaS products needing to offer native third-party integrations . **Tech stack**: Per repository. **Deploy**: Self-hosted. **Trade-off**: **Embedded modules are a subset** of the broader ByteChef platform; verify feature completeness for your use case. **Best for**: teams wanting a modular embedded iPaaS architecture with workflow automation built in.

### Additional Strong Open-Source Options

- **n8n** — Fair-code workflow automation with 400+ integrations and inline code nodes (Sustainable Use License) . **Note**: General workflow automation, not embedded iPaaS—no OAuth UI for customers or unified API abstraction. **Best for**: internal automation, not customer-facing integrations.
- **Activepieces** — MIT-licensed no-code automation with "pieces" model (MIT) . **Note**: Internal automation focus; no embedded customer integration features. **Best for**: teams wanting permissive licensing for internal workflows.
- **Automatisch** — Open-source Zapier alternative focused on data staying on your servers (open source) . **Note**: Internal automation; no embedded iPaaS capabilities. **Best for**: privacy-focused internal automation.

**Frameworks for building custom systems**: Combine **Nango** for OAuth and unified API access with **Hotglue** for broad connector coverage and **Terapi** for self-hosted embedded iPaaS architecture—creating a composable open-source integration stack. **None of these match MuleSoft's enterprise governance or Workato's recipe library**, but for developers building native integrations, the open-source options cover the critical layers.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Integration frameworks handling OAuth tokens and customer data must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls and token storage.
- **The "embedded iPaaS" vs. "enterprise iPaaS" vs. "workflow automation" vs. "ETL standard" distinction is critical.** **Nango, Hotglue, Terapi, and ByteChef** are **embedded iPaaS**—they help SaaS products offer native integrations to customers, with OAuth management and unified APIs . **MuleSoft, Workato, Tray.ai, and Boomi** are **enterprise iPaaS**—they integrate internal systems with governance and visual builders . **Zapier, Make, n8n, and Activepieces** are **workflow automation**—trigger-action tools for internal use . **Singer** is an **ETL standard**—taps and targets for data extraction . **Choose based on whether you need customer-facing integrations, internal automation, or data pipelines.**
- **Nango is the most practical open-source embedded integration framework.** 400+ pre-configured APIs, OAuth UI for frontend, and structured object retrieval make it the closest open-source analog to Workato Embedded . **The trade-off**: unified API abstraction requires schema mapping.
- **Hotglue has the broadest connector coverage**—600+ open-source connectors with code-first Python control . **The trade-off**: Python-centric; smaller community than Nango.
- **Terapi is the most architecturally complete self-hosted iPaaS** but is very new (March 2026) . **Evaluate maturity before production adoption.**
- **Workato's self-service pricing is genuinely transparent**—$100/month for 2,500 credits, scaling to $1,275 for 50,000 . **The trade-off**: no credit rollover; unused Pro credits expire monthly.
- **MuleSoft's vCore pricing is opaque and prone to over-commitment.** Premium connectors add 15–40% and require licensing for every environment . **Test smaller worker sizes in sandbox before renewal; ask for true-down rights at each anniversary.**
- **Tray.ai has no published pricing.** Pro (3 workspaces), Team (20 workspaces), and Enterprise (unlimited) are quote-only; Agent Gateway for MCP and Merlin Agent Builder are add-ons . **Do not evaluate without sales engagement.**
- **Atlassian Connect is not a general integration platform.** It is a framework for building Atlassian Cloud apps that operate remotely over HTTP, with official frameworks handling JWT auth and lifecycle callbacks . **Use it only for Atlassian ecosystem apps.**
- Self-hosted open-source solutions require proper infrastructure (TypeScript for Nango, Python for Hotglue, Docker for Terapi), security hardening for OAuth tokens, and ongoing maintenance. **Integration frameworks handle customer credentials and data flows**—ensure your deployment meets your organization's security and compliance requirements before connecting production APIs.

---

**Made for developers, integration engineers, and organizations building transparent integration framework solutions.**
Let's make Developer Integration Frameworks more open, data-driven, and connector-friendly.
