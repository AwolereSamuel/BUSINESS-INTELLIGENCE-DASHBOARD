# BUSINESS-INTELLIGENCE-DASHBOARD
PROJECT DESCRIPTION: 

The Business Performance Intelligence Dashboard is an interactive Microsoft Power BI solution designed to evaluate retail business performance across revenue, profitability, products, customer segments, regions, and sales personnel. The project converts structured business data into interactive management information that can support performance monitoring, commercial investigation, and evidence-based decision-making.

The dashboard is organised into four report pages:

1 Executive Overview

2 Sales & Profit Analysis

3 Management Analysis

4 Product Tooltip


# PROJECT OVERVIEW
The dashboard was developed to answer the following management question:

How is the business performing, what is driving performance, and where should management focus?

The report combines headline performance indicators with detailed analysis of products, categories, regions, customer segments, employees, and time-based performance.

The solution is intended to help management:

- Monitor overall sales and profitability.

- Identify high-performing products and categories.

- Compare customer-segment performance.

- Evaluate regional and salesperson performance.

- Identify potential profitability concerns.

- Prioritise areas requiring further investigation.

- Translate analytical findings into practical management actions.

# OBJECTIVES
 The objectives of the project were to:

1 Analyse total sales, quantity, cost, and profit.

2 Monitor sales growth and year-over-year performance.

3 Evaluate product and category contribution to revenue.

4 Analyse customer segments and regional performance.

5 Assess salesperson sales and profit contributions.

6 Identify high-revenue but potentially low-profit products.

7 Develop an interactive and user-friendly Power BI dashboard.

8 Apply data modelling, Power Query, and DAX techniques.

9 Provide management-oriented insights and recommendations.

10 Demonstrate the ability to convert raw business data into actionable intelligence.

# TOOLS & TECHNOLOGIES
- Microsoft Power BI: Dashboard development, reporting, and visualisation.

- Power Query: Data cleaning and transformation.

- DAX (Data Analysis Expressions): Measures and business calculations.

- Dimensional Data Modelling: Relationships between fact and dimension tables.

- Microsoft Excel: Data handling and preparation.

# DATASET
The dataset was provided as an Excel workbook containing several related tables.

**Fact_Sales**

The main transactional table containing individual sales records.

Key fields included information such as:
- Order ID

- Order Date

- Product ID

- Customer ID

- Employee/Salesperson information

- Quantity

- Unit Price

- Discount

- Payment Method

- Sales Channel

- Order Status

**Dim_Products**
Contained product-related information including:

- Product ID

- Product Name

- Category

- Brand

- Unit Cost

- Unit Price

**Dim_Customers**
Contained customer information including:

- Customer ID

- Customer Type/Segment

- Region

- State

- City

**Dim_Employees**
- Employer ID

- Employee Name

- Department

- Job Level

- Region

**Dim_Date**
A dedicated date dimension used for time-based analysis such as:

- Year

- Quarter

- Month

- Month Number

- Month Name

The dataset covers sales activity across 2024–2026.


# MODELLING APPROACH
The model follows a dimensional modelling approach in which transactional fact tables are connected to descriptive dimension tables.

The model supports analysis by:

- Date and reporting period.

- Product and category.

- Customer and customer segment.

- Employee and salesperson.

- Region.

- Inventory and expense information.

- Business targets.

The Dim_Date table is intended to support time-intelligence calculations such as previous-month sales, previous-year sales, sales growth, and year-over-year growth.

# DASHBOARD & KEY FEATURES 
1. **Data Preparation**

- Reviewed and prepared business data for analysis.

- Organised data into fact and dimension tables.

- Worked with sales, customer, product, employee, inventory, expense, and target data.

- Prepared the data model for reporting and analysis.


2. **KPI Analysis:** The dashboard includes performance indicators such as:

- Total Sales

- Total Quantity

- Total Cost

- Total Profit

- Profit Margin

- Total Orders

- Average Order Value

- Previous Month Sales

- Sales Growth

- Previous Year Sales


3. **Dashboard Pages**

(I) Executive Overview: The Executive Overview page provides a high-level summary of business performance.

Key elements include:

- Total Sales.

- Total Orders.

- Total Profit.

- Total Quantity.

- Total Cost.

- Net Profit.

- Sales Growth.

- Year-over-Year Growth.

- Regional sales.

- Monthly sales trend.

- Sales by customer segment.

- Sales by brand.

- Sales by product.

- Sales by category.

- Profit by category.


(II) Sales & Profit Analysis: he Sales & Profit Analysis page provides more detailed performance analysis across commercial dimensions.

The page includes analysis of:

- Product-level sales.

- Product-level profit.

- Product profit margins.

- Regional net sales.

- Employee or salesperson net sales.

- Employee or salesperson profit.

- Customer-segment sales.

- Category-level profitability.

- Comparative sales and profit performance.

(III) Management Analysis: Supports the identification of business opportunities, underperforming areas, products requiring attention, and potential management actions. The page addresses:

- Biggest opportunity by category.

- Regional performance.

- Product-level sales and profitability.

- Salesperson performance.

- Customer-segment sales and profit.

- Customer-segment profit margin.

- Potential actions for improving commercial performance.

**The current management narrative highlights the following investigation areas:**

Investigate Mini PC profitability.

- Review pricing, product cost, and discount levels.

- Review Projector performance and identify drivers of its reported profit margin.

- Investigate regional performance, including the region referenced in the report narrative as North East.

- Review salesperson performance by comparing sales and profit.

- Investigate the Computers category because of its strong revenue contribution.

(IV) Product Tooltip: The Product Tooltip page provides contextual KPI information when users hover over product-related visuals.

The tooltip layout contains:

- Total Sales.

- Total Profit.

- Total Cost.

- Total Quantity.

- Total Orders.

This improves usability by allowing users to inspect product-level performance without leaving the main report page.


4. **Interactivity**

- Report-page navigation

- Interactive visual filtering

- Page navigation buttons

- Product-level report tooltips

- Comparative business analysis

# KPI INDICATORS AND PERFORMANCE INTERPRETATION

The dashboard reports total sales of approximately $183.09 billion, providing an overview of the organisation's reported revenue performance during the analysed period.

The business recorded approximately 30,000 orders, representing the total number of transactions processed. The total quantity sold was approximately 227,000 units, indicating the overall volume of products recorded in the sales data.

The reported total cost is $154.84 million, while total profit is approximately $182.93 billion and net profit is $181.67 billion. These figures require further validation because the profit values are almost equal to total sales, while the cost is presented at a different scale.

The dashboard indicates a sales growth rate of 2.89%, reflecting a positive change based on the comparison period used. The reported year-over-year growth of 49.37% suggests substantial growth compared with the corresponding previous-year period, subject to verification of the underlying calculations.

The average quantity per order is 7.57 units, meaning that each order contains approximately seven to eight units on average.

Overall, these KPI indicators provide management with an overview of revenue, transaction volume, product quantity, cost, profitability, and business growth. However, the financial measures should be reconciled to ensure accurate calculations, consistent units, and reliable business interpretation. 

# RESULTS

The dashboard provides an interactive reporting environment for evaluating business performance across multiple dimensions. The analysis is designed to help management:

- Monitor sales and profitability.

- Compare product and category performance.

- Identify strong and weak business segments.

- Evaluate sales performance across regions and employees.

- Investigate products with high sales but comparatively weak profitability.

- Support evidence-based business recommendations.

# KEY BUSINESS INSIGHTS
- Insight 1: Computers Is a Major Revenue Contributor

The Computers category generates approximately $47.05bn, representing approximately 25.76% of total sales in the displayed category visual.

This indicates that Computers is a major contributor to the reported revenue base.

Management implication: Management should investigate the category's sales volume, product mix, pricing, cost structure, and profit contribution to determine whether its performance can be sustained or expanded.

- Insight 2: Storage Is Another Significant Revenue Contributor

The Storage category generates approximately $40.78bn, representing approximately 22.28% of total sales in the displayed category visual.

Storage therefore represents another substantial part of the business's reported sales composition.

Management implication: Storage should be monitored alongside Computers, especially in relation to demand, margins, inventory availability, and product-level profitability.

- Insight 3: Retail Is the Largest Customer Segment by Sales

The Retail customer segment generates approximately $74bn in sales in the displayed segment visual. It is ahead of the Corporate and SME segments.

Management implication: Management should assess the factors supporting Retail's performance, including customer demand, product mix, order volume, and sales strategy, and determine whether lessons can be applied to other customer segments.

- Insight 4: Flash Drive Appears to Be the Leading Product by Sales

The product-level sales visual places Flash Drive among the highest-selling products, followed by products such as Laptop and Mini PC.

Management implication: High sales alone should not be treated as evidence of high profitability. The leading products should be assessed using sales, cost, profit, profit margin, quantity, and order volume together.

- Insight 5: Mini PC Requires Profitability Investigation

The Management Analysis page specifically identifies Mini PC for investigation in relation to profitability, pricing, product cost, and discount levels.

Management implication: Management should review the Mini PC cost structure, pricing policy, discounts, returns, and product-level margin before deciding whether corrective action is necessary.

- Insight 6: Salesperson Performance Should Be Evaluated Using Both Sales and Profit

The report contains employee-level sales and profit visuals and recommends reviewing the gap between sales and profit.

Management implication: Salesperson performance should not be evaluated using revenue alone. A salesperson with high sales but comparatively low profit may require investigation into discounts, product mix, pricing, or transaction quality.

- Insight 7: Regional Performance Is Uneven

The regional visuals show differences in sales and net sales across regions. The Management Analysis page also identifies regional performance as an investigation area.

Management implication: Management should compare regional revenue, profit, margin, customer volume, and product mix before allocating additional resources or setting regional targets.

# MANAGEMENT RECOMMENDATION
1:- Review Category-Level Growth Opportunities, Conduct a deeper analysis of the Computers and Storage categories by examining:

- Product-level sales.

- Profit contribution.

- Profit margin.

- Unit volume.

- Discount rates.

- Inventory availability.

- Customer-segment demand.

This will help determine whether high revenue is supported by healthy profitability and sustainable demand.

2:- Investigate Mini PC Profitability, Perform a product-level profitability review of Mini PC, including:

- Unit acquisition or production cost.

- Selling price.

- Discount percentage.

- Returns and refunds.

- Sales volume.

- Contribution margin.

- Performance by region and customer segment.

Management should apply corrective measures only after the underlying figures have been validated.

3:- Strengthen Salesperson and Regional Performance Monitoring, Introduce a performance review framework that compares:

- Sales revenue.

- Gross or net profit.

- Profit margin.

- Number of orders.

- Average order value.

- Product mix.

- Discount levels.

- Regional customer composition.

This will help distinguish high-revenue performance from genuinely profitable performance.

# SKILLS DEMONSTRATED
1 Data Analysis.

2 Data Cleaning and Transformation.

3 Power BI Dashboard Design.

4 Power Query.

5 DAX Measures.

6 Data Modelling.

7 KPI Development.

8 Business Performance Analysis.

9 Data Visualization.

10 Analytical Problem-Solving.


