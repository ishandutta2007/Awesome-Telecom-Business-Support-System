# Awesome-Telecom-Business-Support-System

## Top Telecom Business Support Systems (BSS) Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Billing, Charging (OCS), Customer Management, Product Catalog, Order Management & Revenue Operations for CSPs, MVNOs & Digital Telcos*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Telecom Business Support Systems (BSS)**. These systems handle the commercial side of telecom operations — including real-time charging, rating, invoicing, customer care, product catalog, order management, and revenue assurance — enabling CSPs and MVNOs to monetize services across prepaid, postpaid, and hybrid models.

**Examples** include Amdocs BSS, Netcracker Digital BSS, CSG Ascendon, Optiva BSS, Oracle Communications Billing, Ericsson Charging, Huawei CBS, Matrixx Software, Enghouse Networks, and Openet (the category leaders).

**Open-source emphasis**: Telecom BSS has one of the stronger open-source ecosystems in the industry. **CGRateS**, **BillRun**, **Kill Bill**, **Lago**, and related OCS/billing projects provide production-capable alternatives for charging and subscription management. This section is heavily expanded with these and supporting tools.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product / Platform | Primary Focus & Description | Starting Pricing | Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- |
| **[Totogi BSS & Charging](https://totogi.com/)** | Cloud-native multi-tenant SaaS OCS and BSS built natively on AWS for digital telcos and MVNOs. | $0.05 / 10,000 transactions (Pay-as-you-go above free tier) | **Free forever** up to 500 million transactions/mo (Charging) & 500 million API calls/mo (BSS) for ≤250,000 subscribers |
| **[Cerillion Skyline](https://www.cerillion.com/)** | Cloud-native SaaS subscription billing, rating, and customer lifecycle management system. | $140 / month (Skyline Essential starting tier) | 7-day free trial with access to billing configuration engine, sample catalogs, and API endpoints |
| **[Lago Cloud](https://www.getlago.com/)** | Real-time usage-based billing, metering, and invoicing engine for digital telcos and API services. | $250 / month (Pro Cloud tier) | **Free forever** open-source self-hosted edition (unlimited events) or 14-day free trial on Cloud Pro |
| **[Kill Bill (AWS Cloud)](https://killbill.io/)** | Enterprise subscription billing and payment management architecture running on cloud infrastructure. | $40 / month (Base AMI software subscription fee) | **Free forever** open-core self-hosted edition or 14-day free trial via AWS Marketplace listing |
| **[LogiSense](https://www.logisense.com/)** | Agile subscription, telecom usage rating, and mediation platform for VoIP, IoT, and enterprise CSPs. | $1,000 / month (Starter deployment tier) | 30-day free trial with 24/7 sandbox access, rating simulation templates, and onboarding orientation |
| **[Enghouse Networks BSS](https://www.enghouse.com/)** | Cloud billing, interconnect billing, customer care, and revenue assurance for regional CSPs and ISPs. | $5,000 / month (Cloud billing starting tier) | 30-day evaluation trial including guided demo tenant and sample CDR rating batch testing |
| **[Oracle Communications Billing (BRM)](https://www.oracle.com/industries/communications/)** | Cloud-deployed Billing and Revenue Management suite for complex rating, policy, and multi-play CSPs. | $2,500 / month (OCI base managed entry tier + $0.05/active subscriber) | 30-day free trial with $300 Oracle Cloud Infrastructure (OCI) credits to test and run BRM instances |
| **[Optiva BSS](https://www.optiva.com/)** | Cloud-native charging and BSS suite deployed as SaaS on Google Cloud for digital telcos and MVNO Hubs. | $10,000 / month (MVNO Hubs base platform tier) | 30-day guided pilot & proof-of-concept sandbox for MVNO and digital telco architecture evaluation |
| **[PortaOne (PortaSwitch / PortaBilling)](https://portaone.com/)** | Multi-tenant cloud-hosted convergent BSS/OCS for Class 4/5 SIP routing, MVNOs, and fixed-line telcos. | $12,500 / month ($150,000/yr starting base tier deployment) | 30-day free trial for Add-on Mart extension modules with full integration sandbox on test instances |
| **[CSG Ascendon](https://www.csgi.com/)** | Digital BSS and high-velocity revenue management platform for multi-brand telcos and MVNOs on AWS/Azure. | $15,000 / month (Base SaaS platform tier) | 30-day enterprise sandbox and proof-of-concept testing environment for verified telco operators |
| **[Openet (Amdocs)](https://www.openet.com/)** | Real-time policy, charging (CHF), and data monetization SaaS suite for 4G/5G standalone networks. | $18,000 / month (Cloud-native policy/charging gateway starting tier) | 30-day sandbox pilot access for Diameter and 5G HTTP/2 Service-Based Architecture (SBA) validation |
| **[Matrixx Software](https://www.matrixx.com/)** | Real-time 5G convergent charging and digital commerce platform for cloud-native network monetization. | $20,000 / month (Core cloud charging entry tier) | 30-day lab sandbox access with up to 10,000 simulated subscribers for performance evaluation |
| **[Amdocs BSS / connectX](https://www.amdocs.com/)** | Market-leading end-to-end cloud BSS suite for Tier-1 CSPs and MVNOs (charging, catalog, care, billing). | $25,000 / month (connectX / SaaS entry-level subscription tier) | 30-day structured PoC sandbox trial via AWS Marketplace / telco partner program |
| **[Netcracker Digital BSS](https://www.netcracker.com/)** | Full-stack digital BSS platform for convergent charging, partner ecosystem, and digital customer journeys. | $30,000 / month (Entry managed SaaS subscription tier) | 60-day structured Proof-of-Concept (PoC) evaluation in a dedicated cloud carrier sandbox |
| **[Ericsson Charging](https://www.ericsson.com/)** | 3GPP-compliant converged charging system (CCS) and monetization portfolio for 5G, IoT, and hybrid CSPs. | $35,000 / month (Managed cloud BSS entry base tier) | 30-day partner lab environment sandbox access for 5G charging API and rating scenario validation |

## Open-Source GitHub Projects
- **[CGRateS](https://github.com/cgrates/cgrates)**  
  High-performance, real-time Online/Offline Charging System (OCS) for telecom and ISP environments. Supports account balances, session/event charging, rating, CDR handling, LCR, fraud detection, and cloud-ready microservices. AGPL-3.0 licensed.

- **[BillRun](https://github.com/BillRun/system)**  
  Open-source enterprise billing and BSS platform for telecom operators and usage-based businesses. Includes mediation, real-time charging (OCS), rating, invoicing, CRM modules, and customer portal capabilities.

- **[Kill Bill](https://github.com/killbill/killbill)**  
  Leading open-source subscription billing and payments platform with extensive plugin architecture, suitable for digital services and hybrid telecom/subscription models. Apache 2.0 licensed.

- **[Lago](https://github.com/getlago/lago)**  
  Open-source usage-based billing and metering platform that can serve as a modern alternative for digital telco and MVNO monetization stacks.

- **[SigScale OCS](https://github.com/sigscale/ocs)**  
  3GPP-aligned Online Charging System implementing prepaid authorization and charging with Diameter interfaces and TM Forum Open API support.

- **[Ostelco](https://github.com/ostelco/ostelco-core)**  
  Cloud-native telco BSS/OCS experiments with Diameter-to-gRPC gateways, rule engines, and analytics pipelines oriented toward packet-data services.

- **[FOSSBilling](https://github.com/FOSSBilling)**  
  Free, open-source billing and client management system adaptable for hosting, software licensing, and lighter subscription/telecom use cases.

- **[A2Billing / ASTPP and VoIP billing stacks](https://github.com/)**  
  Long-standing open-source billing systems for voice and calling-card services that remain relevant for certain Class 4/5 and reseller scenarios.

- **[Mediation and CDR processing pipelines](https://github.com/)**  
  Open tools for collecting, normalizing, and preparing usage records before rating and charging.

- **[TM Forum Open API inspired open implementations](https://github.com/)**  
  Community projects and reference code aligned with TM Forum standards for product catalog, customer, and billing APIs.

### Additional Strong Open-Source Options
- Integration of CGRateS or BillRun with open CRM/ERP systems (Odoo, ERPNext) for end-to-end customer and billing flows.
- Kafka / Flink pipelines for high-volume CDR mediation and real-time event processing.
- Prometheus + Grafana for monitoring charging system health and performance KPIs.
- Containerized and Kubernetes-native deployment patterns for the above OCS/BSS components.
- Open customer portals and self-care frameworks that sit on top of open charging engines.

**Frameworks for building custom systems**: Deploy **CGRateS** or **BillRun** as the core real-time charging and rating engine, feed it mediated CDRs or Diameter events, manage balances and tariffs in the open platform, and generate invoices via open or integrated tools. Pair with an open CRM or customer portal for account management and product catalog. This stack delivers high performance, full transparency, and zero licensing cost for the charging core — ideal for MVNOs, ISPs, private networks, and operators willing to invest in integration and operations. Large Tier-1 convergent BSS transformations still typically rely on commercial suites for scale, multi-play complexity, regulatory features, and vendor support.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Telecom BSS systems handle financial transactions, customer data, and regulatory obligations. Open-source solutions provide excellent control and cost advantages but require rigorous testing, auditability, tax/compliance handling, and operational maturity before production use. Always validate rating accuracy and financial controls thoroughly.
- Charging and billing logic must comply with local telecom regulations, consumer protection rules, and accounting standards.

---
**Made for billing architects, MVNO/ISP operators, and telecom engineers building flexible monetization platforms.**
Let's make real-time charging and convergent BSS more open, performant, and operator-controlled.
