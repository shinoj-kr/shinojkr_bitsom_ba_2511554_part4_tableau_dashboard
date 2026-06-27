## Task 2: Calculated Fields

The following calculated fields were created in Tableau to support business analysis and dashboard development.

| Calculated Field | Formula / Logic | Business Purpose |
|------------------|-----------------|------------------|
| Profit Margin | Profit ÷ Sales | Measures the profitability generated from each unit of sales. |
| Cost | Sales − Profit | Estimates the cost incurred for each sale. |
| Average Order Value | Total Sales ÷ Total Orders | Measures the average revenue generated per customer order. |
| Return Rate | Returned Orders ÷ Total Orders | Measures the percentage of orders that are returned. |
| **Shipping Delay Bucket** | Evaluates each order against the expected delivery time based on its **Ship Mode**. Orders delivered within the expected service level are classified as **On Time**, while orders exceeding the expected delivery time are classified as **Delayed**. Service levels used are: **Same Day = 0 days**, **First Class ≤ 1 day**, **Second Class ≤ 3 days**, and **Standard Class ≤ 5 days**. | Measures shipping performance by comparing actual delivery time with the expected service level (SLA) for each shipping mode, helping identify delayed deliveries and evaluate logistics efficiency. |

These calculated fields are used throughout the Tableau dashboard to create KPIs, support business analysis, and improve decision-making.
