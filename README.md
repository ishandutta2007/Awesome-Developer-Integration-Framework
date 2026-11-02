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

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## Sector Overview & Market Dynamics

The global Integration Platform as a Service (iPaaS) and developer integration market is estimated at **$8B to $16B+** (growing at a 15-25% CAGR toward $30B+ by 2030), driven by cloud-native transitions, GenAI agent tooling, and hybrid API architectures. The sector exhibits a **hybrid market structure**: it is **concentrated at the top** among established enterprise titans capturing massive enterprise contract values, yet **highly fragmented across mid-market, SMB, and developer tiers** where agile low-code tools, embedded iPaaS (e-iPaaS), and open-source alternatives rapidly innovate.

## SaaS/Hosted Platforms

| Product | Company Valuation / Revenue | Pricing (Starting Tier) | Free Tier / Trial Limits | Category / Focus | Key Trade-off / Notes |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Atlassian Connect** | **$49B Market Cap** ($6.57B FY26 Revenue) | **$0/month** (Framework is free; hosting on user infrastructure, paid cloud plans scale from $7.90/user/mo) | **Free forever Developer Bundle** (Standard Jira/Confluence Cloud access capped at small developer teams, 2 GB storage limit, subject to inactivity purge) | App Developer Framework | Restricted to Atlassian Cloud ecosystem; external app hosting, auth servers, and database are self-managed. |
| **MuleSoft Anypoint Platform** | **$6.5B Deal Valuation** (Salesforce unit; ~$350M+ ARR at buyout) | **$2,000/month** ($24,000/year billed annually for Integration Starter) | **30-day free trial** with access to Anypoint Design Center, API Manager, Exchange, and full portfolio capabilities | Enterprise iPaaS & API Mgmt | Opaque vCore / credit-based pricing model; premium connectors incur 15-40% surcharges per environment. |
| **Workato** | **$5.7B Valuation** (Series E; ~$250M+ ARR) | **$100/month** (Pro plan for 2,500 recurring monthly credits, scaling to $1,275/mo for 50,000 credits) | **Free forever plan** with **50,000 one-time credits** (never expire; no recurring monthly top-up) | Enterprise Automation & iPaaS | No credit rollover on paid tiers (unused Pro credits expire monthly); all tasks, API calls, and rows consume credits. |
| **Postman** | **$5.6B Valuation** (Series D; $100M+ ARR) | **$9/month** billed annually ($12/mo monthly) for Solo plan; **$19/user/month** for Team tier | **Free forever plan** for **1 solo user**, unlimited collection runs, unlimited local/cloud mock servers, and 1,000 API monitoring runs/month | API Development & Testing | Team workspaces, collection collaboration, and shared mocks require paid Team seats ($19/user/mo). |
| **Zapier** | **$5.0B Valuation** (~$310M ARR) | **$19.99/month** billed annually ($29.99/mo monthly) for Professional plan (750 tasks/mo) | **Free forever plan** limited to **100 tasks/month**, single-user, two-step Zaps only (1 trigger, 1 action), and 15-minute polling | No-Code Workflow Automation | Multi-step automations, conditional logic paths, webhooks, and fast 2-minute polling require paid plans. |
| **Boomi** | **$4.0B Deal Valuation** (TPG / Francisco Partners private buyout) | **$99/month** (Pay-As-You-Go entry tier plus metered usage at ~$0.05 per message; Professional starts at ~$20,000/yr) | **30-day free trial** with unrestricted full-featured access to AtomSphere platform, connectors, and environment runtimes | Enterprise Cloud iPaaS | Connector-based licensing scales costs rapidly as endpoints grow; advanced message queuing requires higher tiers. |
| **Tray.ai** | **$600M+ Valuation** (Series C-ext; $150M+ raised) | **$595/month** (Pro starter tier, 3 workspaces, 250k task credits, 7-day log retention) | **14-day free trial** available upon request/sales qualification with basic workflow sandboxing; no permanent free plan | Low-Code Enterprise iPaaS | Sales-led quotes; high entry pricing; advanced Merlin AI agents and Agent Gateway for MCP require paid add-ons. |
| **Make** | **$50M+ ARR** (Celonis unit; parent valued at $13.2B) | **$9/month** billed annually ($10.59/mo monthly) for Core plan (10,000 operations/month) | **Free forever plan** with **1,000 operations/month**, maximum 2 active scenarios, and 15-minute execution interval | Visual Workflow Automation | Operations bill per module execution rather than per workflow scenario; credit exhaustion halts scenarios on lower tiers. |
| **Cloud Elements** | **Acquired by UiPath** ($7.2B Market Cap, $1.7B Revenue; legacy purchase undisclosed) | **$0/month Community**; UiPath Automation Cloud entry packages start at **$420/month** ($5,040/year) | **Free forever Community Plan** (UiPath Automation Cloud: 1 Pro developer license, 1 unattended robot, AI credits pool, capped at businesses <$5M revenue) | Embedded iPaaS & Hub APIs | Acquired and folded into UiPath Integration Service; standalone embedded developer portal deprecated. |

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
