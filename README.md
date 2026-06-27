## Task 1: Connect and Inspect Data

### Dataset Loaded

The dataset `dashboard_sales_data.xlsx` was successfully loaded into Tableau. The dataset contains 4,200 records and 20 fields representing retail sales, customers, products, shipping, returns, and marketing information.

### Field Inspection

#### Date Fields

| Field | Data Type |
|-------|-----------|
| Order Date | Date |
| Ship Date | Date |

#### Geographic Fields

| Field | Data Type |
|-------|-----------|
| State | String |
| City | String |

#### Categorical Fields

| Field | Data Type |
|-------|-----------|
| Order Id | String |
| Customer Id | String |
| Customer Segment | String |
| Region | String |
| Category | String |
| Sub Category | String |
| Product Name | String |
| Ship Mode | String |
| Campaign Channel | String |

#### Numerical Measures

| Field | Data Type |
|-------|-----------|
| Sales | Number (Decimal) |
| Quantity | Number (Whole) |
| Discount | Number (Decimal) |
| Profit | Number (Decimal) |
| Delivery Days | Number (Whole) |
| Customer Rating | Number (Decimal) |

#### Binary / Flag Field

| Field | Data Type |
|-------|-----------|
| Return Flag | Number (Whole) |

### Assumptions

- The dataset is assumed to be analysis-ready without additional data cleaning.
- Order Date and Ship Date are correctly recognized as Date fields by Tableau.
- Geographic fields (State and City) are assumed to contain valid location values.
- Return Flag was treated as a binary indicator where values represent returned and non-returned orders.
- All numerical fields were assumed to be suitable for aggregation and business analysis.

# Business Problem Summary

The objective of this project is to build an Executive Sales Performance Dashboard in Tableau that enables business leaders to monitor sales performance, profitability, customer behavior, shipping efficiency, discounts, and product returns. The dashboard supports data-driven decision-making by providing interactive visualizations and business insights across multiple business dimensions.

---

# Dataset Description

The dataset contains **4,200 retail sales records** with **20 fields** covering:

- Sales and Profit
- Orders and Customers
- Product Categories and Sub-Categories
- Regions, States, and Cities
- Shipping Information
- Customer Ratings
- Discounts
- Return Information

The dataset includes both categorical and numerical fields suitable for business analytics and dashboard creation.

---

# Tableau Workbook Description

The Tableau workbook contains multiple worksheets that together form an Executive Sales Performance Dashboard.

### Worksheets Created

- KPI: Total Sales
- KPI: Total Profit
- KPI: Total Orders
- Regional Performance View
- Monthly Sales Trend
- Category Profitability View
- Customer Segment View
- Shipping Performance View
- Discount vs Profit
- Return Analysis View
- Executive Sales Performance Dashboard

The dashboard combines these worksheets into a single interactive executive reporting interface.

---

# Calculated Fields Created

The following calculated fields were created in Tableau:

| Calculated Field | Purpose |
|------------------|---------|
| Return Rate | Calculates percentage of returned orders by category |
| Shipping Delay Bucket | Classifies shipments as On Time or Delayed based on Ship Mode and Delivery Days |
| Average Order Value | Calculates average sales per order |

---

# Dashboard Components

The Executive Dashboard includes:

- KPI Cards (Total Sales, Total Profit, Total Orders)
- Regional Performance Bar Chart
- Monthly Sales Trend Line Chart
- Category Profitability Horizontal Bar Chart
- Customer Segment Bar Chart
- Shipping Performance Stacked Bar Chart
- Discount vs Profit Scatter Plot
- Return Rate by Category Bar Chart

---

# Filters and Interactions Used

### Dashboard Filters

- Region
- Category
- Customer Segment

### Interactive Features

- Selecting a region filters all dashboard visualizations.
- KPI cards update dynamically based on selected filters.
- All charts respond to dashboard filter selections.

---

# Key Business Insights

Major insights obtained from the dashboard include:

- South region generates the highest sales.
- Technology products contribute the highest profits.
- Home Office customers generate the highest sales.
- Monthly sales remain relatively stable across the analysis period.
- Higher discounts are associated with lower profitability.
- Furniture has the highest return rate.
- Standard Class handles the highest shipment volume and also records the highest number of delayed deliveries.
- Technology offers the strongest growth opportunity due to high profitability and relatively low return rates.

---

# Dashboard Story Summary

The dashboard presents a complete business performance story by combining sales, profitability, customer behavior, shipping performance, discounts, and returns into a single executive view.

It highlights strengths such as consistent sales growth, profitable Technology products, and strong regional performance while also identifying improvement opportunities in Furniture returns, shipping delays, and discount management. The dashboard supports leadership in making informed strategic decisions through interactive analysis.

---

# Limitations

- The dashboard analyzes historical data only.
- Customer demographics beyond customer segment are unavailable.
- Reasons for product returns and shipment delays are not captured.
- External business factors such as competitor activity and market trends are not included.
- No predictive or forecasting models are implemented.

---

# Screenshots Included

The project includes the following screenshots inside the `outputs` folder:

- `full_dashboard.png`
- `sales_trend_view.png`
- `regional_performance_view.png`
- `category_profitability_view.png`
- `filter_interaction_view.png`

These screenshots demonstrate the completed dashboard, individual visualizations, and interactive filtering functionality.
