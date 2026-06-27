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


# Task 8: Business Insights

## Insight 1: Sales Trend

**Observation:**  
Monthly sales remain relatively stable across 2024–2025, with a few noticeable peaks and dips.

**Data Evidence:**  
Monthly sales fluctuate approximately between ₹6.3M and ₹10.9M, with higher sales observed during several months in 2025.

**Business Interpretation:**  
The business maintains consistent revenue throughout the period, but seasonal demand appears to influence monthly performance.

**Recommended Action:**  
Analyze the factors behind high-performing months and replicate successful campaigns during lower-sales periods.

---

## Insight 2: Regional Performance

**Observation:**  
The South region generates the highest sales among all regions.

**Data Evidence:**  
- South: ₹64.69M
- North: ₹54.56M
- West: ₹48.91M
- East: ₹48.86M

**Business Interpretation:**  
South is the strongest revenue contributor, while West and East have comparatively lower sales.

**Recommended Action:**  
Study the success factors in the South region and apply similar sales and marketing strategies in lower-performing regions.

---

## Insight 3: Category and Sub-Category Profitability

**Observation:**  
Technology products generate significantly higher profits than Furniture and Office Supplies.

**Data Evidence:**  
Top profitable sub-categories include:
- Copiers: ₹7.31M
- Accessories: ₹7.19M
- Phones: ₹7.10M
- Machines: ₹6.45M

Several Furniture and Office Supplies sub-categories generate profits below ₹1.1M.

**Business Interpretation:**  
Technology products are the primary drivers of overall profitability.

**Recommended Action:**  
Increase focus on high-performing Technology products while reviewing pricing and product mix for low-profit categories.

---

## Insight 4: Customer Segment Performance

**Observation:**  
Home Office customers contribute the highest sales.

**Data Evidence:**  
- Home Office: ₹74.50M
- Consumer: ₹71.89M
- Corporate: ₹70.63M

**Business Interpretation:**  
Although all customer segments contribute significantly, Home Office customers generate the highest revenue.

**Recommended Action:**  
Strengthen customer retention programs and targeted promotions for the Home Office segment while identifying opportunities to grow Consumer and Corporate sales.

---

## Insight 5: Discount Impact

**Observation:**  
Higher discount levels are associated with lower profit values and more negative-profit transactions.

**Data Evidence:**  
The scatter plot shows that transactions with discounts between 25% and 35% contain more low-profit and loss-making orders than transactions with lower discounts.

**Business Interpretation:**  
Aggressive discounting reduces profitability and increases the likelihood of losses.

**Recommended Action:**  
Review discount policies and limit high discounts to products or campaigns that deliver measurable business value.

---

## Insight 6: Shipping Performance

**Observation:**  
Standard Class handles the largest number of shipments and also records the highest number of delayed deliveries.

**Data Evidence:**  
Standard Class:
- On Time: 1,781 orders
- Delayed: 654 orders

Other shipping modes process substantially fewer orders and delays.

**Business Interpretation:**  
The higher number of delays is influenced by the significantly larger shipment volume handled by Standard Class.

**Recommended Action:**  
Investigate operational bottlenecks in Standard Class deliveries and identify opportunities to improve delivery efficiency.

---

## Insight 7: Return Pattern

**Observation:**  
Furniture has the highest return rate among all product categories.

**Data Evidence:**  
- Furniture: 7.67%
- Office Supplies: 3.65%
- Technology: 3.03%

**Business Interpretation:**  
Furniture products are returned more than twice as often as Technology products, indicating potential quality, shipping, or customer expectation issues.

**Recommended Action:**  
Analyze the reasons for Furniture returns and implement improvements in product quality, packaging, and product descriptions.

---

## Insight 8: Business Risk and Opportunity

**Observation:**  
Technology products generate the highest profits while also maintaining the lowest return rate.

**Data Evidence:**  
Technology includes the four highest-profit sub-categories and records only a 3.03% return rate.

**Business Interpretation:**  
Technology represents the strongest opportunity for sustainable business growth due to its combination of high profitability and relatively low returns.

**Recommended Action:**  
Increase investment in Technology products through inventory expansion, targeted marketing campaigns, and cross-selling opportunities while continuing to monitor profitability across all categories.
