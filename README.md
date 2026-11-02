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

Curated open-source integration frameworks, workflow automation platforms, embedded connectors, and ETL standards. Projects are sorted in descending order of GitHub star count:

- **[n8n](https://github.com/n8n-io/n8n)** [![GitHub stars](https://img.shields.io/github/stars/n8n-io/n8n?style=social&color=white)](https://github.com/n8n-io/n8n/stargazers) — **Fair-code workflow automation & integration platform** with 400+ pre-built integrations, visual node-based editor, and inline JavaScript/Python code nodes (Sustainable Use License). Designed for complex self-hosted workflow automation and orchestrating internal APIs.

- **[Huginn](https://github.com/huginn/huginn)** [![GitHub stars](https://img.shields.io/github/stars/huginn/huginn?style=social&color=white)](https://github.com/huginn/huginn/stargazers) — **Self-hosted agent-based system for automating online tasks** (MIT). Hackable, open-source alternative to IFTTT and Zapier that monitors events, parses JSON/XML/HTML, and runs automated actions on external web services and APIs.

- **[Kestra](https://github.com/kestra-io/kestra)** [![GitHub stars](https://img.shields.io/github/stars/kestra-io/kestra?style=social&color=white)](https://github.com/kestra-io/kestra/stargazers) — **Declarative, event-driven orchestrator & integration platform** (Apache 2.0). Connects modern data pipelines, microservices, and external cloud APIs with 500+ plugins, YAML workflows, and real-time event triggers.

- **[Activepieces](https://github.com/activepieces/activepieces)** [![GitHub stars](https://img.shields.io/github/stars/activepieces/activepieces?style=social&color=white)](https://github.com/activepieces/activepieces/stargazers) — **Open-source no-code workflow automation** (MIT). Provides a modular "pieces" architecture with 250+ community-built connectors, designed as a lightweight, developer-friendly alternative to Zapier for internal business automations.

- **[Temporal](https://github.com/temporalio/temporal)** [![GitHub stars](https://img.shields.io/github/stars/temporalio/temporal?style=social&color=white)](https://github.com/temporalio/temporal/stargazers) — **Durable execution platform & distributed integration orchestration** (MIT). Eliminates complex state machine and queue code when integrating multi-step distributed microservices and external APIs, ensuring fault-tolerant workflow completion.

- **[Airbyte](https://github.com/airbytehq/airbyte)** [![GitHub stars](https://img.shields.io/github/stars/airbytehq/airbyte?style=social&color=white)](https://github.com/airbytehq/airbyte/stargazers) — **Open-source data integration & ELT engine** (ELv2). Powers scalable data replication with 350+ pre-built connectors from SaaS APIs, databases, and message queues into modern data warehouses and lakes.

- **[Windmill](https://github.com/windmill-labs/windmill)** [![GitHub stars](https://img.shields.io/github/stars/windmill-labs/windmill?style=social&color=white)](https://github.com/windmill-labs/windmill/stargazers) — **Fast, multi-language developer platform for scripts, workflows, and internal UIs** (AGPL v3/Enterprise). Runs TypeScript, Python, Go, and Bash scripts as endpoints, webhooks, and distributed flows with auto-generated UIs.

- **[Automatisch](https://github.com/automatisch/automatisch)** [![GitHub stars](https://img.shields.io/github/stars/automatisch/automatisch?style=social&color=white)](https://github.com/automatisch/automatisch/stargazers) — **Self-hosted Zapier alternative for privacy-conscious teams** (AGPL v3). Stores all integration tokens, API credentials, and sync data strictly on your own infrastructure without vendor data leaks.

- **[Nango](https://github.com/NangoHQ/nango)** [![GitHub stars](https://img.shields.io/github/stars/NangoHQ/nango?style=social&color=white)](https://github.com/NangoHQ/nango/stargazers) — **Open-source unified API & OAuth integration framework for product teams** (AGPL v3/Apache 2.0). Provides 400+ pre-configured SaaS API integrations, frontend OAuth Connect UI (`nango.openConnectUI()`), two-way sync, and structured object models for embedded product integrations.

- **[Apache Camel](https://github.com/apache/camel)** [![GitHub stars](https://img.shields.io/github/stars/apache/camel?style=social&color=white)](https://github.com/apache/camel/stargazers) — **Battle-tested enterprise integration framework (EIP)** (Apache 2.0). Implements core enterprise integration patterns with 300+ components, allowing developers to define routing and mediation rules across almost any messaging or transport protocol.

- **[Meltano](https://github.com/meltano/meltano)** [![GitHub stars](https://img.shields.io/github/stars/meltano/meltano?style=social&color=white)](https://github.com/meltano/meltano/stargazers) — **Declarative, code-first data integration and ELT engine** (MIT). Built on top of the Singer tap/target ecosystem with integrated dbt transformation orchestration and GitOps workflows.

- **[Singer](https://github.com/singer-io/getting-started)** [![GitHub stars](https://img.shields.io/github/stars/singer-io/getting-started?style=social&color=white)](https://github.com/singer-io/getting-started/stargazers) — **Open-source standard for data extraction and loading** (Apache 2.0). Defines a Unix-pipe specification for composable, CLI-based taps (data sources) and targets (data destinations).

- **[ByteChef](https://github.com/bytechefhq/bytechef)** [![GitHub stars](https://img.shields.io/github/stars/bytechefhq/bytechef?style=social&color=white)](https://github.com/bytechefhq/bytechef/stargazers) — **Open-source embedded API integration & workflow automation** (Apache 2.0). Provides embedded integration modules and visual workflow orchestration designed specifically for SaaS platforms offering native integrations to their customers.

- **[Hotglue Connectors](https://github.com/hotgluexyz/recipes)** [![GitHub stars](https://img.shields.io/github/stars/hotgluexyz/recipes?style=social&color=white)](https://github.com/hotgluexyz/recipes/stargazers) — **Code-first embedded iPaaS & open-source connector library** (Open Source / MIT). Provides 600+ open-source Python connectors, taps, and recipes under [@hotgluexyz](https://github.com/hotgluexyz) for developers building custom native integration pipelines.


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
