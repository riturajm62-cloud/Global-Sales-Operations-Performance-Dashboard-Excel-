📊 Global Sales & Profitability Intelligence Dashboard (Excel)




📌 Project Overview
This project involves the end to end development of a dynaminc Business Intelligence (BI) dashboard using a global retail dataset of 51,000+ Transactions.
The primary objective was to move beyond "vanity" metrics" (total sales) and identify deep-seated operational inefficiencies,
such as regional profit leaks and logistics bottlenecks.


📁 Dataset
**Source**:Kaggle
Global sales dataset (~51,000+ rows, 24 columns)


🛠 Tools & Techniques Used
1. Microsoft Excel
2. Pivot Tables & Pivot Charts
3. Slicers (Region, Category, Year)
4. Data Cleaning & Validation
5. GETPIVOTDATA, MATCH, ISNUMBER functions
6. KPI Card Design


🔹 Key Performance Indicators (KPIs)
1. Total Revenue
2. Total Profit
3. Average Shipping Days
4. Net Return Rate


🔹 Interactive Filters(Slicers)
1. Region
2. Product Category
3. Year


 🔹 Visual Analysis
1. Monthly Revenue Trend

2. Revenue by Region

3. Regional Sales vs Profitability

4. Top Product Sub-Categories




🛠️ Analytical Workflow (The "Engine")
The project was built using a "Modular Calculation Architecture" to ensure the dashboard remains lightweight yet responsive in Excel .

1.  **Data Extraction & Cleaning**: Processed a global dataset of 51,000+ rows. Performed rigorous data cleaning to handle null/blank values in the "Returned Status" column to ensure calculation accuracy.
2.  **Relational Modeling**: Established a "Unified Data View" by connecting the `Orders` and `Returns` tables using a custom Boolean logic pipeline (`ISNUMBER` + `MATCH`).
3.  **Engineered Calculations**: Developed a back-end "Calculation Engine" using "Pivot Table Aggregations" and "Named Ranges" to drive real-time KPI updates.
4.  **Dynamic Visualization**: Integrated Temporal (Year), Regional, and Product Category Slicers to allow for 360-degree data exploration across 4 KPI cards and 4 interactive charts.
5.  **UI/UX Optimization**: Engineered a professional-grade interface by removing standard Excel gridlines, implementing a "Z-pattern" layout for optimal readability, and locking visual elements for a seamless software-like experience.



## 📊 Key Business Insights
1. **The Profitability Crisis:** Identified that **Southeast Asia**, despite being a top-tier revenue generator (₹3.13L), is the only region operating at a **Net Loss (-₹7,269)**.
2. **Global Benchmarking:** Established a global **Net Return Rate of 5.95%** and a **Net Profit Margin of 6.98%**.
3. **Logistics Leader:** Discovered that **Canada** leads the world in shipping efficiency with an average of **3.52 days**, compared to the global average of **3.99 days**.
4. **Regional Powerhouse:** The **Central Region** is the most successful market, leading with **₹8.60L in sales** and maintaining the highest total profit.
5. **Core Verticals:** Validated that **Chairs** and **Bookcases** are the primary revenue engines, contributing significantly to the total **₹2.86 Lakhs Net Profit**.



## 🚀 Strategic Recommendations
1.  **Regional Margin Audit:** Conduct an immediate "Cost-to-Serve" audit for Southeast Asia to identify if losses are driven by aggressive discounting or logistics overhead.
2.  **Logistics Standardization:** Implement the "Canada Logistics Model" in Africa and Oceania (currently >4.0 days) to reduce shipping lag and lower potential return rates.
3.  **Inventory Pivot:** Prioritize high-margin Furniture stock in the **Central Region** to maximize Q4 seasonal peaks.
4.  **Return Reduction:** Analyze "Returned" orders specifically for the **Technology** category to identify if defects or mis-shipping are driving the 5.95% rate.

---

## 🧮 Data Dictionary & Metrics
| Metric | Calculation | Value Found |
| :--- | :--- | :--- |
| **Global Sales** | $\sum$ (Individual Order Totals) | ₹ 41,10,874.19 |
| **Net Profit** | $\sum$ (Profit) | ₹ 2,86,782.25 |
| **Global Profit Margin** | (Net Profit / Global Sales) | 6.98% |
| **Net Return Rate** | (Returned 'Yes' / Grand Total Orders) | 5.95% |
| **Avg Shipping Time**| Average(Days to Ship) | 3.99 Days |


🚀 Key Learnings

1. Built a complete end-to-end analytics workflow using Excel
2. Strengthened ability to derive insights from business data
3. Improved dashboard design and storytelling skills



**How to Use**
1. Open the file in **Microsoft Excel 2019** or newer.
2. Use the **Slicers** on the left to filter by Year, Region, or Category.
3. Observe real-time updates across all KPIs and Charts.

👤 About the Author
**Ritu Raj**
* **Education:** BS in Data Science, **IIT Madras**
* **Specialization:** Data Visualization, MIS Reporting, Financial Modeling
* **LinkedIn:** [https://www.linkedin.com/in/ritu-raj-ba0bb7383/]



