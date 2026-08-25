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
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Amdocs BSS](https://www.amdocs.com/)**  
  Market-leading end-to-end BSS suite for Tier-1 operators, covering billing, customer management, product catalog, order management, and AI-enhanced revenue operations.

- **[Netcracker Digital BSS](https://www.netcracker.com/)**  
  Cloud-native digital BSS platform widely used by large carriers for convergent charging, catalog, order, and customer experience transformation.

- **[CSG Ascendon](https://www.csgi.com/)**  
  Digital BSS and revenue management platform popular with North American and global operators, especially strong in MVNO and high-velocity billing scenarios.

- **[Optiva BSS](https://www.optiva.com/)**  
  Cloud-native charging and BSS platform favored by digital telcos and operators needing flexible, real-time monetization capabilities.

- **[Oracle Communications Billing](https://www.oracle.com/industries/communications/)**  
  Enterprise Billing and Revenue Management (BRM) solutions supporting complex rating, policy, charging, and multi-play offerings.

- **[Ericsson Charging](https://www.ericsson.com/)**  
  Converged charging and monetization portfolio tightly integrated with Ericsson’s network and core offerings, strong in 5G and IoT scenarios.

- **[Huawei CBS](https://www.huawei.com/)**  
  Convergent Billing System used by many operators globally for prepaid/postpaid charging, rating, and customer management.

- **[Matrixx Software](https://www.matrixx.com/)**  
  Real-time convergent charging platform focused on digital services, 5G monetization, and flexible pricing models (note ongoing market consolidation).

- **[Enghouse Networks](https://www.enghouse.com/)**  
  Network and service management solutions that include BSS-related billing and operational support capabilities.

- **[Openet](https://www.openet.com/)**  
  Specialist in policy, charging, and real-time monetization components frequently deployed in 4G/5G and digital service environments.

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
