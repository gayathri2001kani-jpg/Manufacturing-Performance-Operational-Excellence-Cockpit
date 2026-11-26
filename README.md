# 📊 Procurement Analytics Cockpit | Power BI Dashboard

An executive-level **Procurement Intelligence Dashboard** built in **Microsoft Power BI** to monitor end-to-end procurement spend, purchase order (PO) ageing, supplier on-time delivery (OTD), and vendor concentration risk across plants and material categories.

---

## 🖼️ Dashboard Preview

![Procurement Analytics Cockpit Dashboard](./Manufacturing%20Performance%20%26%20Operations%20Excellence%20Cockpit%20Dashboard.png)

---

## 🎯 Executive KPIs & Performance Summary

| KPI Metric | Current Value | Benchmark / Target | Variance / Status | Business Impact |
| :--- | :---: | :---: | :---: | :--- |
| **Total Procurement Spend** | **₹48.75 Cr** | ₹45.06 Cr (Plan) | `+8.2% vs Plan` | Tracks overall budget adherence across categories |
| **Overdue PO %** | **88.0%** | 10.0% (Target) | `+77.6% vs Target` | Highlights critical fulfillment bottlenecks requiring follow-up |
| **Supplier OTD %** | **93.0%** | 95.0% (Target) | `-2.4% vs Target` | Measures vendor delivery reliability against SLA |
| **Top 10 Supplier Spend Share** | **100.0%** | 60.0% (Limit) | `+40.0% vs Limit` | Identifies high vendor concentration and supply risk |
| **High Risk Spend %** | **19.4%** | 5.0% (Threshold) | `+14.4% vs Threshold` | Flags expenditure exposed to high-risk suppliers |
| **Open PO Value** | **₹12.30 Cr** | 900 Open PO Lines | `25.2% of Spend` | Quantifies pending financial commitments |

---

## 📈 Visual Breakdown & Analytical Insights

1. **Multi-Dimensional Slicer Navigation**
   * Interactive top-level slicers allow instant cross-filtering by **Company Code**, **Plant Code**, **Fiscal Year**, **Material Category**, and **Vendor Code**.
2. **Procurement Spend by Category (Donut Chart)**
   * Breaks down total expenditure across four core categories: **Components** (`₹143.9M` | `29.52%`), **Raw Materials** (`₹139.31M` | `28.58%`), **Others** (`₹105.1M` | `21.5%`), and **Services** (`₹99.17M` | `20.34%`).
3. **Top 10 Suppliers by Spend (Pareto Combo Chart)**
   * Combines individual vendor spend bars with a cumulative percentage curve across top vendors (*Global Tech, Techno Works, Raman Industries, ABC Ltd, Star Enterprises, Prime Suppliers, Delta Inc, XYZ Corp, Omega Pvt Ltd, Vision Ltd*).
4. **Open PO Value by Category & Ageing (Stacked Column Chart)**
   * Segments open purchase order commitments into four ageing buckets (**1–30 Days**, **31–60 Days**, **61–90 Days**, and **90+ Days**) to isolate long-pending orders in Components and Raw Materials.
5. **Supplier On-Time Delivery Performance (Trend Line Chart)**
   * Tracks monthly OTD fluctuations from January to December, highlighting seasonal dips (such as September) and recovery trends.
6. **Monthly Spend Comparison (Clustered Column Chart)**
   * Compares **Committed Spend** against **Total Procurement Spend** month-over-month to monitor accrual and budget pacing.
7. **Overdue PO Action Table**
   * Provides granular line-item visibility (`PO_Number`, `Vendor_Name`, `Material_Category`, `Days_Overdue`) so procurement teams can prioritize overdue orders exceeding 200–300+ days.

---

## 🛠️ Technical Architecture & Skills Demonstrated

* **BI & Visualization:** Microsoft Power BI Desktop (Custom KPI cards with dynamic variance indicators, Pareto combo charts, stacked ageing columns, interactive slicers)
* **Data Modeling & DAX:** Time intelligence, cumulative Pareto percentage (`TOPN` / `ALLSELECTED`), dynamic variance calculations (`vs Plan` / `vs Target`), conditional formatting rules, and PO ageing bucket segmentation
* **Data Engineering & ETL:** Power Query data cleaning, schema standardization, and star-schema relationship modeling

---

## 🔗 Project Links & How to Explore

* **GitHub Repository:** [View Full Project](https://github.com/gayathri2001kani-jpg/Manufacturing-Performance-Operational-Excellence-Cockpit)
* **How to Open:** Click on the `.pbix` file in the repository file list above, select **Download raw file**, and open it in **Microsoft Power BI Desktop**.
```[cite: 1, 2, 3]

*(Important: Make sure the file `Manufacturing Performance & Operations Excellence Cockpit Dashboard.png` is uploaded directly into the main folder of your GitHub repository so that `./Manufacturing%20Performance%20%26%20Operations%20Excellence%20Cockpit%20Dashboard.png` loads properly when you commit.)*
