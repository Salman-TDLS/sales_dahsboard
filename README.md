# Superstore Sales Analysis using Power BI

---

This project transforms the classic **Global Superstore** dataset into a *clean, interactive Power BI dashboard*.
The report surfaces sales, profit, and customer behavior across regions and product segments.

---

## Steps Involved

### 1. Data Preparation

* Connected the raw `Superstore.csv` file via Power Query.
* Removed duplicate `Order ID` rows to guarantee transaction uniqueness.
* Fixed nulls in critical fields (`Sales`, `Profit`, `Ship Mode`).
* Enforced correct data types and split the `Order Date` into *year*, *quarter*, and *month* columns.

### 2. Data Modeling

* Built a **star schema** with *Date*, *Customer*, *Product*, and *Region* dimension tables.
* Added calculated measures: `Total Profit`, `Profit Margin`, and `YoY Sales Growth`.

### 3. Report Build

* Designed KPI cards, clustered bar charts, and line graphs for time‑series trends.
* Implemented slicers (Year, Segment, Region) for one‑click drill‑downs.
* Added drill‑through pages for *Top 10 customers* and *Product profitability*.

### 4. Insights

#### Regional Performance

* **West** leads with **\$725 K** in total sales but lags in profit margin compared to **Central**.

#### Segment Breakdown

* **Technology** drives **35 %** of revenue, edging out Furniture and Office Supplies.

#### Profit Outlier

* The *MX‑1000 Laser Mouse* contributes **\$22 K** profit, marking it as a star SKU.

#### Shipping Impact

* Orders shipped via **Same Day** show the lowest return rate (< 1 %), highlighting the value of expedited logistics.
