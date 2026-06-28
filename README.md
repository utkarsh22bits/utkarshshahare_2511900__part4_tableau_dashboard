# utkarshshahare_2511900__part4_tableau_dashboard

# Executive Sales Performance Dashboard

## Business Problem Summary

Retail businesses generate large volumes of sales data, making it difficult for decision-makers to quickly identify performance trends, profitable products, high-performing regions, customer behavior, shipping efficiency, and return patterns.

The objective of this project is to develop an interactive Tableau dashboard that consolidates key business metrics into a single view, enabling executives to monitor performance, identify opportunities, and make informed business decisions.

---

# Dataset Description

The dashboard is built using a retail sales dataset containing transactional order information. The dataset includes business dimensions such as:

* Order Date
* Sales
* Profit
* Discount
* Category
* Sub-Category
* Customer Segment
* Region
* Ship Mode
* Delivery Days
* Return Status

These fields were used to analyze business performance across multiple operational and financial perspectives.

---

# Tableau Workbook Description

The Tableau workbook consists of calculated fields, seven analytical worksheets, and one executive dashboard.

### Worksheets Included

1. Sales Performance Over Time
2. Regional Sales & Profit Analysis
3. Product Category Profitability
4. Performance by Customer Segment
5. Shipping Efficiency Analysis
6. Impact of Discount on Profit
7. Product Return Analysis

The workbook also includes KPI cards displaying:

* Total Sales
* Total Profit
* Return Rate

---

# Calculated Fields Created

The following calculated fields were created as part of the assignment:

| Calculated Field      | Formula                                                  |
| --------------------- | -------------------------------------------------------- |
| Profit Margin         | Profit / Sales                                           |
| Cost                  | Sales - Profit                                           |
| Average Order Value   | Sales / Number of Orders                                 |
| Return Rate           | Returned Orders / Total Orders                           |
| Shipping Delay Bucket | Categorizes delivery days into Fast, Medium, and Delayed |

These calculated fields provide additional business metrics that are not directly available in the source dataset.

---

# Dashboard Components

The Executive Sales Performance Dashboard contains:

### KPI Cards

* Total Sales
* Total Profit
* Return Rate

### Visualizations

* Sales Performance Over Time
* Regional Sales & Profit Analysis
* Product Category Profitability
* Performance by Customer Segment
* Shipping Efficiency Analysis
* Impact of Discount on Profit
* Product Return Analysis

The dashboard is organized to present summary metrics first, followed by detailed analytical views.

---

# Filters and Interactions Used

The dashboard includes interactive filters that allow users to explore the data dynamically.

### Filters

* Order Date
* Region
* Category
* Customer Segment
* Ship Mode

### Dashboard Interaction

A dashboard filter action has been implemented so that selecting data in one visualization updates the related charts across the dashboard. This enables users to perform interactive exploration and compare business performance across different dimensions.

---

# Key Business Insights

Analysis of the dashboard highlights several important findings:

* Sales remain relatively stable over time with periodic fluctuations.
* Regional performance varies significantly, indicating opportunities for targeted growth strategies.
* Technology products generate the highest profitability among product categories.
* Customer segments contribute differently to overall sales performance.
* Higher discounts are generally associated with lower profitability.
* Shipping performance varies across shipping modes, affecting delivery efficiency.
* Product returns are concentrated in specific categories and regions.
* Business performance can be improved through better pricing strategies, logistics optimization, and regional expansion.

---

# Dashboard Story Summary

The dashboard provides executives with a consolidated view of business performance by combining financial metrics, operational performance, customer behavior, and product analysis.

Rather than examining individual reports separately, decision-makers can quickly understand overall business health, identify areas requiring attention, and evaluate opportunities for improving profitability, operational efficiency, and customer satisfaction.

The dashboard supports data-driven decision-making by connecting sales performance, regional analysis, customer behavior, shipping efficiency, discount impact, and product returns into one interactive analytical solution.

---

# Assumptions and Limitations

## Assumptions

* A Return Flag value of **1** represents a returned order.
* Profit Margin is calculated as Profit divided by Sales.
* Cost is estimated as Sales minus Profit.
* Average Order Value is calculated using total sales divided by the total number of orders.
* Shipping Delay Bucket categorizes deliveries into Fast, Medium, and Delayed based on delivery days.
* All calculations are based solely on the provided dataset.

## Limitations

* The dashboard analyzes historical data only and does not perform forecasting.
* External factors such as marketing campaigns, economic conditions, and competitor activity are not included.
* Return reasons are not available within the dataset.
* Customer satisfaction metrics are outside the scope of this analysis.
* Profit calculations do not include indirect operating expenses.

---

# Software Used

* Tableau Desktop
* Microsoft Excel (Dataset)

---

# Conclusion

The Executive Sales Performance Dashboard provides an interactive and business-friendly solution for monitoring sales, profitability, customer behavior, shipping performance, and product returns. By combining KPIs, interactive filters, calculated fields, and analytical visualizations, the dashboard enables management to identify trends, evaluate business performance, and support strategic decision-making.
