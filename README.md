# Awesome-B2B-Pricing-Management

# Awesome-B2B-Pricing-Management
**Top B2B Pricing Management (Opensource) 🌟 Star if you like it! 🌟**

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Price Lists, Deal Desk, Usage-Based Pricing, Discount Governance & Pricing Experimentation*
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **B2B Pricing Management**. These tools enable organizations to manage price lists, negotiate customer-specific contracts, govern discounts, experiment with pricing models, and bill complex usage-based agreements—from fully managed enterprise pricing optimization suites to self-hosted pricing engines and commerce platforms that give teams complete control over their pricing logic.

**Examples** include PROS Pricing, Pricefx, Vendavo, Zilliant, Competera, Prisync, Omnia Retail, Flintfox, and Shopify Price Lists (the category leaders in commercial space).

**Open-source emphasis**: This section is expanded with every relevant project for self-hosting, price list management, and open pricing infrastructure. **Critical note**: True open-source B2B pricing optimization—with AI-driven price elasticity, competitive intelligence, and margin optimization—is essentially nonexistent. The projects below address **price list execution**, **pricing and billing infrastructure**, and **commerce platform pricing engines**, not the optimization layer that PROS or Pricefx provide.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[PROS Pricing](https://www.pros.com/)**
  **AI-driven pricing optimization and revenue management** for B2B enterprises. **Pricing**: Quote-only; enterprise contracts. **Free tier**: None. **Best for**: large enterprises wanting AI-powered price optimization, deal guidance, and margin analytics across complex product portfolios.

- **[Pricefx](https://www.pricefx.com/)**
  **Cloud-native pricing platform** with price optimization, CPQ, rebate management, and deal desk. **Pricing**: Quote-only; modular pricing. **Free tier**: None. **Best for**: mid-market to enterprise organizations wanting a comprehensive, modular pricing suite with strong analytics.

- **[Vendavo](https://www.vendavo.com/)**
  **B2B pricing and profitability management** platform with price execution, deal guidance, and margin analytics. **Pricing**: Quote-only. **Free tier**: None. **Best for**: manufacturers and distributors wanting to align pricing with profitability goals.

- **[Zilliant](https://www.zilliant.com/)**
  **AI-powered pricing and sales guidance** for B2B. **Pricing**: Quote-only. **Free tier**: None. **Best for**: enterprises wanting data-driven price recommendations and sales intelligence at scale.

- **[Competera](https://competera.net/)**
  **AI-powered price optimization** with competitive intelligence and elasticity modeling. **Pricing**: Quote-only. **Free tier**: None. **Best for**: retailers and B2B sellers wanting competitor-aware price optimization.

- **[Prisync](https://prisync.com/)**
  **Competitor price tracking and dynamic pricing** for e-commerce. **Pricing**: Tiered plans; free trial available. **Free tier**: Trial available. **Best for**: online sellers wanting automated competitor price monitoring and repricing rules.

- **[Omnia Retail](https://www.omniaretail.com/)**
  **Dynamic pricing and retail intelligence** platform. **Pricing**: Quote-only. **Free tier**: None. **Best for**: retailers wanting AI-driven pricing strategies based on market and competitor data.

- **[Flintfox](https://flintfox.com/)**
  **Pricing and rebate management** for Microsoft Dynamics 365. **Pricing**: Quote-only. **Free tier**: None. **Best for**: Dynamics 365 customers wanting integrated price and rebate management.

- **[Shopify Price Lists](https://help.shopify.com/en/manual/b2b/catalogs/price-lists)**
  **B2B price lists** within Shopify's B2B commerce capabilities. **Pricing**: Included with Shopify Plus B2B features; quote-based. **Free tier**: None. **Best for**: Shopify Plus merchants wanting customer-specific pricing within the Shopify ecosystem.

## Open-Source GitHub Projects

- **[Lotus](https://github.com/uselotus/lotus)**
  **Open-source pricing and packaging infrastructure for SaaS** (MIT) — **the most directly relevant open-source project for B2B pricing and billing** with a self-hosted, production-oriented engine. **Features**: Usage-based pricing and flexible prorations; plan management with versioning and deployments; **pricing experimentation** with backtests, A/B tests, and forecasts; integrations with payments, CRM, and data stacks; a simple API for custom integrations . **Tech stack**: Python (Django), React TypeScript, PostgreSQL (TimescaleDB), Redpanda, Redis, Celery, Go microservices . **Deploy**: Self-hosted (Docker); `git clone` and run the self-hosting script . **Trade-off**: **Pricing and billing engine, not a price optimization platform**—it executes and experiments with pricing models but does not provide AI-driven elasticity or competitive intelligence like PROS or Pricefx. **Best for**: SaaS and API companies wanting to deploy, monitor, and experiment with custom subscription and usage-based pricing models without building billing infrastructure from scratch.

- **[Spree Commerce 5.3 Pricing Engine](https://github.com/spree/spree)**
  **Open-source eCommerce platform with native Price Lists** (AGPL-3.0 for core) — **the most complete open-source implementation of B2B price list logic** in a commerce platform. **Features**: **Price Lists** assignable to customer groups, geographic zones, organizations, or individual accounts; **volume pricing** with quantity-based tiers; **user-specific negotiated pricing**; time-based activation with start/end dates; bulk editor for multi-currency price management; integration with Customer Groups and Events engines . **Tech stack**: Ruby on Rails. **Deploy**: Self-hosted. **Trade-off**: **Commerce platform pricing, not enterprise pricing optimization**—it executes price lists at checkout but does not provide deal guidance, margin analytics, or AI optimization. **Best for**: B2B distributors, wholesalers, and multi-region brands wanting native price list execution without custom development.

- **[Medusa Price Lists](https://github.com/medusajs/medusa)**
  **Open-source headless commerce platform with Price Lists module** (MIT for core) — **a modern, developer-friendly option for B2B price management**. **Features**: Price Lists with **Sale or Override** types; customer group availability; start and expiry dates; per-currency and per-region pricing; bulk editing; publish/unpublish workflow; API-first architecture . **Tech stack**: Node.js, TypeScript, PostgreSQL. **Deploy**: Self-hosted or Medusa Cloud. **Trade-off**: **Commerce pricing execution**, not optimization—price lists are managed manually or via API; no AI recommendations or competitive intelligence. **Best for**: developers building B2B commerce experiences wanting programmatic price list management with a modern stack.

- **[LiteERP](https://github.com/liteerp-oss/liteerp)**
  **Lightweight open-source ERP for SMEs** (license per repo) — **an operational ERP with built-in pricing rules and discounts**. **Features**: Product and inventory management; pricing rules and discounts as core functionality; extension-first architecture; Laravel/React/MySQL stack . **Tech stack**: Laravel 12, ReactJS, MySQL 8, PHP 8.4+. **Deploy**: Self-hosted. **Trade-off**: **Basic pricing rules within an ERP**, not a dedicated B2B pricing platform—no price lists per customer group, volume tiers, or deal guidance. **Best for**: small businesses wanting simple pricing and discount rules within a lightweight ERP.

- **[Odoo Pricelists](https://github.com/odoo/odoo)**
  **Open-source ERP with advanced pricelist functionality** (LGPL-3 for Community) — **a mature, widely adopted pricing rules engine within an ERP**. **Features**: Pricelists with **fixed price, discount, or formula** rules; quantity-based tiers; customer group and country group targeting; currency-specific lists; date ranges; and "Selectable" option for eCommerce . **Tech stack**: Python (Odoo framework), PostgreSQL. **Deploy**: Self-hosted or Odoo.sh. **Trade-off**: **ERP pricing engine, not a pricing optimization platform**—rules are configured manually; no AI or competitive intelligence. **Best for**: organizations already on Odoo wanting native price list management integrated with sales and inventory.

- **[Obydullah B2B Portal](https://wordpress.org/plugins/obydullah-b2b-portal/)**
  **WordPress B2B portal plugin with per-customer price lists** (GPL) — **a self-service quoting channel for B2B customers on WordPress**. **Features**: Company and contact management; **customer-specific price lists** with validity windows; RFQ workflow with state machines; quotations with line-item pricing and discounts; partial acceptance; purchase orders; CSV import/export; tenant isolation and transactional integrity . **Tech stack**: WordPress (PHP). **Deploy**: WordPress plugin. **Trade-off**: **RFQ and quoting workflow**, not a full pricing management platform—no optimization, margin analytics, or AI. **Best for**: small B2B businesses on WordPress wanting customer-specific pricing and quote-to-order workflows.

- **[entirius-django-pricefighter](https://pypi.org/project/entirius-django-pricefighter/)**
  **Competitive pricing engine for Django** (MPL-2.0) — **a decision engine for price recommendations based on competitor observations**. **Features**: Channel registry; per-channel product representation; **pricing rules with strategy resolution (hold/compete/raise)**; decision engine joining prices, costs, bounds, and competitor observations into gap + recommendation + suggested price; apply flow with audit snapshots; admin API with JWT . **Tech stack**: Python (Django). **Deploy**: Self-hosted (Django app). **Trade-off**: **Early-stage and narrow**—focused on competitive repricing decisions, not full B2B price list management or deal desk. **Best for**: developers wanting a reference implementation for competitive pricing decision logic in Django.

### Additional Strong Open-Source Options

- **PriceBot** — Algorithmic repricing engine (Python, license per repo). Scrapy/Playwright scraping, Airflow orchestration, automatic price adjustment within margin bounds. **Note**: **Architecture documented but implementation pending**—not production-ready . **Best for**: reference only for repricing architecture.
- **@neural-trader/example-dynamic-pricing** — Reinforcement learning dynamic pricing example (npm). Multiple strategies, swarm intelligence, competitive analysis. **Note**: **Example package**, not a production pricing platform . **Best for**: developers exploring RL-based pricing concepts.
- **mcp-pricing** — Enterprise pricing engine with MCP tools (Rust). CEL rules, price waterfall, promotions, quotes/CPQ, audit trail. **Note**: **Agent-oriented pricing engine**, not a traditional B2B price list management platform . **Best for**: developers building AI agents that need pricing capabilities.

**Frameworks for building custom systems**: Combine **Lotus** for usage-based pricing and billing infrastructure with **Spree Commerce** or **Medusa** for B2B price list execution, **Odoo** or **LiteERP** for ERP-integrated pricing rules, and **entirius-django-pricefighter** as a reference for competitive decision logic—creating a B2B pricing stack matched to each organization's commerce model and technical constraints.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- B2B pricing platforms handling contract terms and customer data must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls for negotiated pricing.
- **The "pricing optimization" vs. "pricing execution" vs. "pricing and billing" distinction is critical.** **PROS, Pricefx, Vendavo, Zilliant, Competera, and Omnia Retail** are **optimization platforms**—they use AI and competitive data to recommend prices. **Spree, Medusa, Odoo, and LiteERP** are **execution platforms**—they apply price lists and rules at checkout but do not optimize. **Lotus** is **pricing and billing infrastructure**—it deploys and experiments with pricing models but does not provide elasticity or competitive intelligence. **No open-source project replicates the optimization layer of PROS or Pricefx.**
- **Lotus is the strongest open-source option for SaaS B2B pricing.** It provides usage-based pricing, plan management, and experimentation—areas where most open-source tools are weak . **The trade-off**: it is billing infrastructure, not a price optimization platform. It will not tell you what to charge; it helps you deploy and test what you decide.
- **Spree 5.3's Pricing Engine is the most complete open-source B2B price list implementation** in a commerce platform—customer groups, volume tiers, user-specific pricing, and time-based activation are all native . **Medusa** offers similar capabilities with a more modern, API-first stack. **Choose based on your existing commerce platform or stack preference.**
- **Odoo and LiteERP provide ERP-native pricing rules but are not B2B pricing platforms.** They handle price lists, discounts, and formulas within a broader ERP, but lack deal guidance, margin analytics, and optimization . **Do not confuse ERP pricing rules with B2B pricing management.**
- **Open-source B2B pricing optimization is essentially nonexistent.** No project matches PROS or Pricefx in AI-driven elasticity, competitive intelligence, or margin optimization. **Organizations needing optimization will require SaaS or significant custom development.**
- **Pricing opacity is universal across commercial vendors.** PROS, Pricefx, Vendavo, Zilliant, Competera, Prisync, Omnia Retail, Flintfox, and Shopify Price Lists (for B2B) all require sales contact or plan-based estimation. **Validate with direct vendor conversations against your actual pricing complexity and volume.**
- Self-hosted open-source solutions require proper server setup, backup configuration, and ongoing maintenance. **Pricing data is commercially sensitive**—ensure your hosting meets your organization's security requirements before deploying.

---

**Made for developers, pricing teams, and organizations building transparent B2B pricing solutions.**
Let's make B2B Pricing Management more open, data-driven, and margin-friendly.
