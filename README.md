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
