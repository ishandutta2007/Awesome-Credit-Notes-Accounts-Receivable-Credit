# Awesome-Credit-Notes-Accounts-Receivable-Credit

## Top Credit Notes & Accounts Receivable Credit Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Credit Memo Issuance, AR Automation & B2B Credit Risk Management*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Credit Notes & Accounts Receivable Credit**. These tools help finance teams issue credit memos, adjust invoices, automate collections, and assess customer creditworthiness—covering everything from subscription billing credit notes to enterprise-grade credit-to-cash platforms and B2B credit risk bureaus.

**Examples** include Chargebee, HighRadius, Versapay, YayPay (Quadient), D&B, Experian, Creditsafe, and open-source alternatives like BillKu and webERP (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted billing with credit notes, open-source AR follow-up workspaces, and community-driven ERP credit management—ideal for SMEs and finance teams seeking data sovereignty and predictable costs over per-invoice or per-seat SaaS pricing. Note that purpose-built open-source credit risk scoring is genuinely absent; the practical path is composing billing platforms with credit note support and lightweight AR trackers.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Chargebee](https://www.chargebee.com/)** | Subscription billing platform with native **credit note support**: refundable credits, adjustment credits, and promotional credits blended with accounting compliance. Handles proration, standalone credits, line-item credits, and service-period configuration for revenue recognition. Includes A/R leakage and aging reports to track stuck receivables . | Flow: $0 + 0.80% of monthly invoicing; or $99/month + 0.65% | **No free tier**; Flow PAYG charges from first dollar |
| **[HighRadius Credit Cloud](https://www.highradius.com/)** | AI-powered credit management within the broader AR automation suite. Aggregates credit bureau data, financial statements, payment history, and ERP exposure for real-time scoring. Configurable credit policies, automated approvals for low-risk accounts, and continuous monitoring for deteriorating financial health. Native SAP, Oracle, Dynamics, and NetSuite integrations . | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[Versapay](https://www.versapay.com/)** | Unified invoice-to-cash AR automation platform. Automates invoice delivery, collections, cash application, and reconciliation. Customers self-serve through a branded portal. Claimed outcomes: 50% less time managing receivables, 25% faster payments, 30% fewer past-due invoices . | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[YayPay (Quadient)](https://www.cuadient.com/)** | Automated AR platform for B2B. AI predicts payor behavior, automates invoicing and collection communications, and determines customer credit. Secure statement portal for customers; integrates with ERP, CRM, and accounting systems. Users highlight auto-dunning and custom email templates as efficiency gains . | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[Dun & Bradstreet](https://www.dnb.com/)** | Business credit bureau providing D-U-N-S numbers, credit scores, and risk data used for trade credit decisions and supplier onboarding. | Quote-only (per-report or subscription) | No free tier; trial via sales |
| **[Experian Business](https://www.experian.com/)** | Commercial credit reporting with business credit scores, risk indicators, and monitoring alerts. Used by finance teams to set credit limits and assess counterparty risk. | Quote-only (subscription or per-report) | No free tier; trial via sales |
| **[Creditsafe](https://www.creditsafe.com/)** | Global business credit risk platform with company credit reports, monitoring, and compliance data. Positioned as more accessible than D&B for SMEs. | Quote-only (subscription tiers) | Free trial available |
| **[Cortera](https://www.cortera.com/)** | B2B credit risk data and analytics. Uses trade payment data to score private companies and predict payment behavior. | Quote-only (enterprise contract) | No free tier; demo via sales |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[BillKu](https://github.com/ribato22/BillKu)** | [![Stars](https://img.shields.io/github/stars/ribato22/BillKu?style=social&color=white)](https://github.com/ribato22/BillKu/stargazers) | **The most complete open-source billing platform with credit note support in this list.** Self-hosted, offline-ready (PWA) billing and business management for SMEs. MIT licensed. Features full invoice lifecycle, **credit notes**, delivery notes, recurring invoices, receivables aging report, multi-currency, and PDF export. Includes CRM, POS, HR/payroll, inventory, and WhatsApp integration for sending invoices and payment reminders. Docker-ready with NestJS/Next.js stack . |
| **[Orvaket](https://github.com/Akam1123/orvaket)** | [![Stars](https://img.shields.io/github/stars/Akam1123/orvaket?style=social&color=white)](https://github.com/Akam1123/orvaket/stargazers) | **Local-first accounts receivable follow-up workspace** for small B2B service firms. Imports QuickBooks/Xero AR CSV exports; helps one person track which invoice needs attention, why it's unpaid, who owns the next step, and what the customer promised. Prepares email drafts for human review. No account, no cloud sync, no server-side backup—AES-256-GCM optional local encryption. Free and local-first . |
| **[webERP](https://github.com/webERP/webERP)** | [![Stars](https://img.shields.io/github/stars/webERP/webERP?style=social&color=white)](https://github.com/webERP/webERP/stargazers) | Mature open-source ERP with **full Accounts Receivable module** including overdue inquiry, customer account drill-down, and **credit note** linkage to source invoices. PHP-based, runs on any web server. Flexible taxation for multiple jurisdictions. Role-based user access. Free and fully customizable . |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[BrassLedger](https://github.com/rhamenator/BrassLedger)** | [![Stars](https://img.shields.io/github/stars/rhamenator/BrassLedger?style=social&color=white)](https://github.com/rhamenator/BrassLedger/stargazers) | Open-source cross-platform accounting and business management (.NET). **Receivables support** for customer invoices, statements, balances, and cash application. GPL-3.0. Prerelease v0.1.0-pre.6—early stage, but actively developed with installers for Windows, macOS, and Linux . |

**Frameworks for building custom systems**: Combine **BillKu** for full billing with credit notes and receivables aging, **Orvaket** for lightweight AR follow-up tracking from CSV exports, and **webERP** for mature double-entry accounting with credit note linkage—all deployable locally or on a private server without per-invoice SaaS fees. For credit risk assessment, the open-source path requires integrating external bureau APIs; no self-hosted credit scoring engine exists as a mature category.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Credit note issuance and AR credit decisions have direct accounting and legal implications; ensure compliance with revenue recognition standards (ASC 606/IFRS 15) and jurisdictional tax requirements. Credit bureau data (D&B, Experian, Creditsafe) is subject to fair credit reporting regulations.
- **Pricing is opaque for enterprise platforms.** HighRadius, Versapay, YayPay, D&B, Experian, Cortera, and Creditsafe are all quote-only with no public list rates. Chargebee publishes transparent percentage-based pricing but charges from the first dollar. Open-source alternatives like **BillKu** (MIT) and **webERP** provide genuine credit note and AR functionality, but lack the AI-driven credit scoring and bureau integrations that commercial platforms offer. **Orvaket** is a local-first prototype, not a production AR system—use it for follow-up tracking, not as a system of record.

---

**Made for AR analysts, finance controllers, billing administrators, and developers building credit-to-cash infrastructure.**  
Let's make credit notes and AR credit management more open, auditable, and cash-flow-positive.
