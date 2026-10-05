# Awesome-Supply-Chain-Management-SCM

# Top Supply Chain Management (SCM) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Inventory Optimization, Demand Planning & Open-Source Logistics Platforms*  
**Last updated: October 2026**

This repository tracks notable **commercial SCM platforms** and **open-source projects** that manage the flow of goods, information, and finances from procurement through delivery. These tools range from enterprise suites handling global networks to lightweight inventory managers for small businesses and specialized healthcare logistics systems.

**Examples** include Microsoft Dynamics 365 Supply Chain Management, SAP SCM, Oracle SCM Cloud, Blue Yonder, Manhattan Associates, Infor Supply Chain, Kinaxis RapidResponse, Coupa Supply Chain, E2open, and Descartes Systems (the category leaders).

**Open-source emphasis**: The open-source SCM ecosystem is anchored by **OpenBoxes** (healthcare logistics used in 12 countries), **Apache OFBiz** (full ERP with manufacturing and inventory), and **Tryton** (modular ERP with supply chain modules). **supplycm** provides 397 pure-Python algorithms for education and prototyping, while **frePPLe** and **Fleetbase** offer production-grade planning and fleet management. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Microsoft Dynamics 365 Supply Chain Management](https://dynamics.microsoft.com/en-us/supply-chain-management/)**  
  Enterprise SCM suite covering procurement, inventory, warehouse, transportation, and manufacturing with AI-powered demand forecasting and Azure IoT integration.

- **[SAP SCM](https://www.sap.com/products/scm.html)**  
  SAP's comprehensive supply chain suite including Integrated Business Planning, Extended Warehouse Management, and Transportation Management. The enterprise standard for large organizations.

- **[Oracle SCM Cloud](https://www.oracle.com/scm/)**  
  Cloud-native SCM suite with inventory, order management, manufacturing, and logistics. Strong AI/ML capabilities and integration with Oracle ERP.

- **[Blue Yonder](https://blueyonder.com/)**  
  AI-driven supply chain platform with demand planning, inventory optimization, and warehouse execution. Known for Luminate platform with cognitive solutions.

- **[Manhattan Associates](https://www.manh.com/)**  
  Unified commerce and supply chain solutions with WMS, TMS, and order management. Strong for retail and omnichannel fulfillment.

- **[Infor Supply Chain](https://www.infor.com/solutions/supply-chain)**  
  Industry-specific SCM solutions with CloudSuite platform. Strong in manufacturing, distribution, and healthcare verticals.

- **[Kinaxis RapidResponse](https://www.kinaxis.com/)**  
  Concurrent planning platform enabling real-time supply chain orchestration and what-if scenario analysis. Strong for complex, global networks.

- **[Coupa Supply Chain](https://www.coupa.com/)**  
  Business spend management and supply chain design. Focus on procurement, supplier risk, and cost optimization.

- **[E2open](https://www.e2open.com/)**  
  End-to-end supply chain platform connecting demand, supply, logistics, and global trade. Strong for multi-enterprise collaboration.

- **[Descartes Systems](https://www.descartes.com/)**  
  Logistics and supply chain technology with routing, fleet management, and trade compliance. Strong in transportation and last-mile delivery.

## Open-Source GitHub Projects

- **[OpenBoxes](https://github.com/openboxes/openboxes)**  
  **The leading open-source supply chain management system for healthcare and humanitarian logistics**, EPL-2.0 licensed with 887+ GitHub stars . Born in 2010 from Partners In Health's response to the Haiti earthquake, now used by NGOs and governments in **12 countries** to manage inventory across facilities . Features **multi-facility stock management** with lot tracking, expiry alerts, and real-time visibility; **FEFO picking** and reorder point calculations to reduce waste from stockouts and expiry; and **REST API integration** with DHIS2, ERP systems, and custom tools . **Teams typically go live within 2–4 weeks** — replacing spreadsheets without a six-month implementation project . Available as self-hosted or fully managed via **OpenBoxes Lift** . **The de facto open-source SCM for public health systems** — over 3 million beneficiaries since launch .

- **[Apache OFBiz](https://github.com/apache/ofbiz-framework)**  
  **Mature open-source ERP with integrated supply chain capabilities**, Apache-2.0 licensed . Covers product catalogs, order and inventory management, supply chain management, warehouse management, and manufacturing control . Features a **workflow engine** for process automation, **Material Requirements Planning (MRP)** for production planning, and **manufacturing module** with routing tasks, capacity planning, and BOM explosion . Java-based, deployable on AWS via marketplace or Ubuntu local install . **The most comprehensive open-source ERP/SCM foundation** for organizations wanting a full business platform rather than standalone inventory tools .

- **[Tryton](https://github.com/tryton/tryton)**  
  **Modular open-source ERP with supply chain and inventory modules**, GPL-3.0-or-later licensed . Three-tier architecture (Python client/server + PostgreSQL) with official modules covering **inventory and stock, supply chain, purchasing, sales, manufacturing resource planning, and shipping** . Features **automatic database migration** without manual intervention, **XML-RPC and JSON-RPC** communication, **model and record-level access control**, and **history tracking** for audit trails . Supported by the Tryton Foundation (Belgium, non-profit) with 17 companies from 11 countries . Available in 25 languages . **The best choice for organizations wanting a modular, well-governed ERP foundation with supply chain coverage** .

- **[supplycm](https://pypi.org/project/supplycm/)**  
  **Pure-Python library of 397 supply chain management algorithms** with **zero external dependencies** (no NumPy, pandas, or third-party libraries) . MIT licensed. Modules cover **forecasting** (50 algorithms including moving averages, exponential smoothing, Croston, AR/MA), **inventory** (60 algorithms including EOQ/EPQ, newsvendor, lot-sizing, ABC/XYZ analysis), **routing** (30 algorithms including TSP, VRP, assignment problem), **network** (30 algorithms including shortest paths, MST, max-flow), **scheduling** (40 algorithms including Johnson's rule, NEH, CPM/PERT), **MRP** (30 algorithms including BOM explosion, MPS, kanban, DBR), and **optimization** (30 algorithms including simplex, GA, SA, PSO, ACO) . **The most comprehensive open-source SCM algorithm collection** — ideal for education, prototyping, and embedded use cases where minimal dependencies matter .

- **[frePPLe](https://github.com/frePPLe/frepple)**  
  **Open-source supply chain planning** with 727+ GitHub stars, actively maintained . Covers demand planning, production planning, procurement, and inventory optimization. **Odoo addon available** for integration with the Odoo ERP ecosystem . **Best for organizations wanting production-grade supply chain planning** within a modular open-source stack .

- **[Fleetbase](https://github.com/fleetbase/fleetbase)**  
  **Modular logistics operating system** with 1,816+ GitHub stars, MIT licensed . Integrates **routing, driver management, order tracking, and analytics** into a unified API-first platform . Architecture emphasizes **extensibility through plugins and API hooks**, enabling integration with existing enterprise systems without wholesale replacement . **Best for fleet management and last-mile logistics** within a broader SCM stack .

- **[ModernWMS](https://github.com/fjykTec/ModernWMS)**  
  **Simple, complete, open-source warehouse management system** derived from years of ERP implementation experience, MIT licensed . Designed for **small and medium-sized enterprises** with limited IT budgets who need real warehouse management capabilities . Cross-platform (Linux and Windows), Docker deployment available . **Best for SMBs wanting essential WMS functionality without enterprise complexity** .

- **[Open Inventory Manager](https://pkg.go.dev/github.com/SumukhaS291299/Open-Inventory-Manager)**  
  **Lightweight, high-performance inventory management backend** built in Go, MIT licensed . Uses **BadgerDB** (embedded key-value database) with **async persistence** and **in-memory collection with mutex protection** for thread-safe, high-throughput operations . Features add/update/delete/filter inventory items, supplier metadata support, and JSON API via Gin . **Runs in Docker with minimal CPU & memory usage** . **Best for developers needing a fast, embeddable inventory API** without database overhead .

### Additional Strong Open-Source Options

- **myWMS** — Open-source warehouse management framework from Fraunhofer IML for customizable WMS/MFC implementations .
- **Bizuno** — WordPress-based ERP/Accounting/CRM with inventory, purchasing, and shipping management. Trusted evolution of PhreeBooks since 2007 .
- **django-qms** — Quantity Management System for warehouse-level stock management with CSV import and signal-driven propagation .
- **OpenEC** — AI-powered ecommerce & retail analytics platform with inventory forecasting and stock movement tracking .
- **AMAPj** — Open-source supply chain management for small-scale/organic producers in France, Belgium, and Luxembourg .
- **Pyomo** — Python optimization library with solved SCM models including transportation and network design .
- **OR-Tools** — Google's optimization solver (13,327 stars, Apache-2.0) for routing, scheduling, and supply chain optimization .
- **GraphHopper** — Open-source routing engine (6,400 stars, Apache-2.0) for logistics and fleet routing .

**Frameworks for building custom SCM solutions**: Choose based on scope. **OpenBoxes** for healthcare and humanitarian logistics with multi-facility inventory and expiry tracking . **Apache OFBiz** for a full ERP/SCM platform with manufacturing and workflow automation . **Tryton** for a modular, well-governed ERP foundation with supply chain modules . **supplycm** for algorithm prototyping and embedded SCM calculations without dependencies . **frePPLe** for production planning within an Odoo ecosystem . **Fleetbase** for fleet and last-mile logistics . Note that true enterprise SCM with global network optimization, AI-powered demand sensing, and multi-enterprise collaboration remains primarily commercial territory; open-source stacks provide strong inventory management, production planning, and logistics foundations that require integration for complete supply chain visibility.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- SCM platforms handle sensitive operational data including inventory levels, supplier terms, and demand forecasts. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations.
- **Open-source SCM requires significant operational responsibility** — server management, database maintenance, and integration with existing ERP/WMS systems. OpenBoxes notes that "free software doesn't mean zero cost" — teams typically go live in 2–4 weeks, but ongoing operations require resources .
- **Algorithm libraries (supplycm) are educational/prototyping tools** — production deployment requires validation against your specific data and constraints .
- The open-source ecosystem provides strong inventory management, production planning, and logistics foundations, but **global network optimization, AI-powered demand sensing, and multi-enterprise collaboration** remain primarily commercial offerings.

---

**Made for supply chain managers, logistics engineers, and operations professionals.**
Let's make supply chain management more open, transparent, and resilient.
