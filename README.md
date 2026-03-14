# Microbell Dashboard — Business Intelligence & KPI Reporting

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](https://python.org)
[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com)
[![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat&logo=chartdotjs&logoColor=white)](https://www.chartjs.org)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)](https://pandas.pydata.org)

Executive dashboard for **Microbell S.A.** — a wholesale import and distribution company — providing real-time KPI tracking across sales, inventory, and operations. Built and maintained internally as part of the IT & Operations management role.

> **Real production system.** This dashboard is actively used for strategic decision-making at Microbell S.A. Data shown in the repository is anonymized for public display.

---

## Overview

Microbell S.A. operates as a wholesale importer and distributor. This dashboard consolidates operational data from multiple internal sources into a single executive view, enabling management to monitor business performance at a glance and respond to changes in real time.

The system replaces manual spreadsheet-based reporting with an automated, always-current view of the business.

---

## Key metrics tracked

### Sales & billing
- Monthly and cumulative revenue vs. target
- Sales by product line, channel, and region
- Invoice volume and average ticket evolution
- Year-over-year and month-over-month comparisons

### Inventory & stock
- Current stock levels by SKU and category
- Stock rotation and turnover rates
- Low-stock and out-of-stock alerts
- Inventory valuation

### Operations & logistics
- Order fulfillment rates and delivery timelines
- Operational efficiency indicators
- Distribution performance by zone

---

## Tech stack

| Layer | Technology | Role |
|---|---|---|
| Data processing | Python · Pandas · NumPy | ETL, aggregation, KPI calculation |
| Visualization | Power BI (embedded) | Executive charts and drill-down reports |
| Charts | Chart.js | Custom inline visualizations |
| Frontend | HTML5 · CSS3 · JavaScript | Dashboard layout and interactivity |
| Data source | Flexxus ERP · SQL | Live operational data feed |
| Reporting | Power BI · Python matplotlib | Automated management reports |

---

## Architecture

```
Flexxus ERP / SQL Database
        │
        ▼
Python (Pandas) — data extraction, cleaning, KPI calculation
        │
        ├──► Power BI — embedded executive reports
        │
        └──► Chart.js / HTML dashboard — live web view
```

Data is extracted periodically from the Flexxus ERP system, processed with Python/Pandas, and surfaced through both an embedded Power BI report and a custom HTML/JS dashboard layer.

---

## Business context

Microbell S.A. is a wholesale import and distribution company operating in Buenos Aires, Argentina. This dashboard was designed and built by the IT & Operations Manager to:

- Replace manual monthly reporting with automated, real-time visibility
- Give management a single source of truth across departments
- Enable faster operational decisions based on current data
- Track KPIs aligned with business objectives on a continuous basis

The system has been in active use since its deployment and is updated as business reporting requirements evolve.

---

## Repository notes

This repository contains the **frontend layer** of the dashboard (`index.html`) with anonymized/demo data for public display. The live production version connects to internal Flexxus ERP and SQL data sources not included here for confidentiality reasons.

---

## Related skills demonstrated

- **Business Intelligence** — KPI design, metric selection, executive reporting
- **Python data processing** — Pandas pipelines for ERP data extraction and transformation
- **Power BI** — report building, embedding, and automated refresh
- **Full stack** — end-to-end ownership from data source to web presentation
- **ERP integration** — Flexxus ERP parametrization and data extraction (17+ years)

---

## Author

**Eduardo Moreno** — IT Manager, HR & Operations · Microbell S.A. (2008–present)

Senior Software Developer specialized in Blockchain/Web3, Backend Python, and enterprise systems.

- GitHub: [@edumor](https://github.com/edumor)
- LinkedIn: [linkedin.com/in/eduardomoreno-15813b19b](https://linkedin.com/in/eduardomoreno-15813b19b)
- Email: [eduardomoreno2503@gmail.com](mailto:eduardomoreno2503@gmail.com)

*Buenos Aires, Argentina · February 2026*
