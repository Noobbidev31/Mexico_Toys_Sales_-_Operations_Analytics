# Mexico_Toys_Sales_-_Operations_Analytics
Executive Power BI analytics suite featuring a dynamic DAX field parameters, interactive tooltips, Row-Level Security (RLS), and sub-second performance optimization across 50 retail stores.
# 🧸 Mexico Toys — Executive Store & Sales Performance Analytics Suite

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Data Governance](https://img.shields.io/badge/Security-RLS_Configured-green?style=for-the-badge)
![Performance](https://img.shields.io/badge/Render_Time-%3C500ms-brightgreen?style=for-the-badge)

## 📌 Executive Summary
An enterprise-grade, interactive **Power BI Desktop Business Intelligence suite** built for executive stakeholders to analyze retail store performance, product profitability, and sales patterns across 50 stores and 29 cities in Mexico. 

Designed with a sleek, custom dark UI/UX theme (`#0B132B`), advanced DAX measures, dynamic Field Parameters, customized report-page tooltips, Row-Level Security (RLS), and verified sub-second visual performance optimization.

---

## 🛠️ Key Technical Features & Highlights

* **🎨 Custom Dark Theme UI/UX (`#0B132B`):** Clean 0px edge-to-edge padding visual design with high-contrast accent colors for visual clarity and modern executive presentation.
* **⚡ Dynamic Field Parameters:** Seamless single-visual metric toggles allowing users to seamlessly switch between Total Sales, Total Profit, and Order Volume across regional breakdowns.
* **🔍 Custom Report-Page Tooltips:** 
  * **Product Breakdown Tooltip:** Color-matched top-product distribution with suppressed zero-value handling (e.g., precise fractional regional representation).
  * **Monthly Trend Tooltip:** Dynamic category-matched color hierarchy with active legend context.
* **🔐 Row-Level Security (RLS):** Implemented static role-based data governance (e.g., `Airport Manager`, `Commercial Manager`) filtering underlying star-schema dimension tables while maintaining adaptive page-level slicers.
* **🚀 Performance Tuning:** Optimized VertiPaq engine model compression and audited visual performance via **Performance Analyzer**, achieving sub-second rendering averages across all interactions (**45 ms to ~529 ms**).
* **🔘 Interactive UX Polish:** Single-click clear-filter bookmarks, dynamic selection indicators, and customized drill-through workflows.

---

## 📊 Data Model & Architecture
* **Schema Structure:** Clean Star Schema centered around transactional sales facts connected to normalized dimension tables (`stores`, `products`, `calendar`, `inventory`).
* **DAX Engineering:** Calculated key performance indicators (KPIs), dynamic title cards, time-intelligence calculations, and logic handling non-blank dynamic breakdowns via `CALCULATE`, `REMOVEFILTERS`, and `DIVIDE`.

---

## 📂 Repository Structure

```text
├── Mexico_Toys_Store_Analytics.pbix   # Full Power BI Desktop Project File
├── README.md                          # Project Documentation
└── assets/                            # Dashboard Screenshots & Tooltip Previews
    ├── executive_summary.png
    ├── product_performance.png
    ├── store_analytics.png
    └── rls_demo.gif
