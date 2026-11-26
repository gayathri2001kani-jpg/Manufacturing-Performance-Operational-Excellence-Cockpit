# 📊 Procurement Analytics Cockpit (Power BI)

An interactive executive dashboard designed to monitor procurement spend, supplier performance, purchase order (PO) ageing, and vendor concentration risk. Built in **Microsoft Power BI**, this cockpit enables supply chain and procurement teams to track budget adherence, identify bottlenecks in open POs, and evaluate vendor reliability across plants and material categories.

![Dashboard Preview]()

---

## 🎯 Key Performance Indicators (KPIs)
* **Total Procurement Spend:** Tracks overall expenditure (`₹48.75 Cr`) against planned budget (`₹45.06 Cr`, `+8.2% vs Plan`).
* **Overdue PO %:** Monitors delayed purchase orders (`88%` vs `10.0%` target threshold).
* **Supplier On-Time Delivery (OTD %):** Measures vendor delivery reliability (`93%` vs `95.0%` target).
* **Top 10 Supplier Spend Share:** Highlights vendor concentration risk (`100%` vs `60.0%` limit).
* **High Risk Spend %:** Flags high-risk procurement exposure (`19.4%` vs `5.0%` threshold).
* **Open PO Value:** Tracks pending purchase commitments (`₹12.30 Cr` across `900` open PO lines, representing `25.2%` of total spend).

---

## 📈 Dashboard Visuals & Insights
1. **Interactive Slicer Bar:** Filter metrics dynamically by **Company Code**, **Plant Code**, **Fiscal Year**, **Material Category**, and **Vendor Code**.
2. **Procurement Spend by Category (Donut Chart):** Breaks down total expenditure across *Components (29.52%)*, *Raw Materials (28.58%)*, *Others (21.5%)*, and *Services (20.34%)*.
3. **Top 10 Suppliers by Spend (Pareto Combo Chart):** Displays individual vendor spend alongside the cumulative spend percentage curve for top suppliers (*Global Tech, Techno Works, Raman Industries, ABC Ltd, Star Enterprises, Prime Suppliers, Delta Inc, XYZ Corp, Omega Pvt Ltd, Vision Ltd*).
4. **Open PO Value by Category & Ageing (Stacked Column Chart):** Categorizes pending PO values into ageing buckets (`1–30 Days`, `31–60 Days`, `61–90 Days`, and `90+ Days`) to pinpoint long-pending orders.
5. **Supplier OTD Performance (Line Chart):** Tracks monthly fluctuations in on-time delivery rates from January to December.
6. **Monthly Spend Comparison (Clustered Column Chart):** Compares **Committed Spend** vs. **Total Procurement Spend** month-over-month.
7. **Overdue PO Granular Table:** Provides line-item visibility into `PO_Number`, `Vendor_Name`, `Material_Category`, and exact `Days_Overdue` for immediate operational follow-up.

---

## 🛠️ Tools & Technical Stack
* **Business Intelligence:** Microsoft Power BI Desktop
* **Data Modeling & Calculations:** DAX (Variance vs. Plan/Target, Cumulative Pareto %, Ageing Buckets, Risk Thresholds, Dynamic Conditional Formatting)
* **Data Transformation:** Power Query

---

## 🚀 How to Use
1. Clone or download this repository.
2. Open the `.pbix` file in **Microsoft Power BI Desktop**.
3. Use the top navigation slicers to filter by company, plant, fiscal year, material category, or vendor.
4. Select any data point on a visual (such as a specific ageing bucket or supplier) to cross-filter the entire cockpit.
```[cite: 1]

*(Note: If you named your uploaded image file `dashboard-preview.jpg` or something else instead of `dashboard-preview.jpeg`, update `./dashboard-preview.jpeg` on line 7 to match your exact filename before clicking **Commit changes**.)*
