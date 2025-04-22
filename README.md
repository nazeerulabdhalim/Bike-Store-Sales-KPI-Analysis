# AdventureWorks-Sales-KPI-Analysis (2020-2022)

### Table of Contents
[Project Background](#project-background) | 
[Data Structure](#data-structure-overview) | 
[Executive Summary](#executive-summary) | 
[Insights](#deep-dive-insights) | 
[Recommendations](#recommendations)]

## **Project Background**
AdventureWorks, a global cycling equipment and accessories manufacturer wanted a way to track _key business metrics, evaluate regional and product performance,_ and _identify valuable customer segments_ to drive growth and operational efficiency. The objective was to transform this raw data (CSV files) into actionable insights through a comprehensive and interactive Power BI dashboard.

## **Data Structure Overview**
![Data Model](/DataModel.jpg)

- **Sales Data:** Contains order details, quantities, prices, dates, and links to customers, products, and territories.<br/>
- **Returns Data:** Includes return dates, quantities, and associated products and regions.<br/>
- **Product Lookup:** Holds product metadata including categories (e.g., Bikes, Accessories) and subcategories (e.g., Tires and Tubes).<br/>
- **Customer Lookup:** Demographics such as income, birth year, occupation, education level, etc.<br/>
- **Calendar Table:** Supports time-based analysis (year, month, quarter).<br/>
- **Territory Lookup:** Breaks down regional data by country and continent.<br/>
- **Measure Table:** Custom DAX KPIs and calculated metrics including adjusted profit, return %, and revenue per customer.<br/>

## **Executive Summary**

This dashboard provides real-time, dynamic insights into AdventureWorks’ global sales performance:<br/>
💰 Total Revenue: $24.9M<br/>
📦 Total Orders: 25.2K<br/>
💸 Profit: $10.5M<br/>
📉 Return Rate: 2.2%<br/>
👥 Unique Customers: 17.4K<br/>
💵 Revenue per Customer: $1,431<br/>

Additional key findings:<br/>
- Accessories were the top-selling category with ~17K orders, followed by Bikes and Clothing.<br/>
- The Sport-100 Helmet series (Red, Blue, Black) showed high return percentages (2.68%–3.33%), hinting at potential product satisfaction or sizing issues.<br/>
- Water Bottle – 30 oz. was the top-selling item by order volume (3,983 units).<br/>

## **Deep Dive Insights**

📈 Revenue & Trends<br/>
- Steady revenue growth observed from Jan 2020 to Jan 2022, with 3.3% MoM increase in latest data.<br/>
- Orders and returns are relatively stable, though a slight uptick in returns occurred last month.<br/>

🌍 Regional Performance<br/>
- Top-performing regions included United States, Australia, and Canada.<br/>
- Europe showed lower return rates but moderate order volumes.<br/>

🎯 Customer Segmentation<br/>
- Most orders came from low-income customers, but high-income customers contributed more revenue per order.<br/>
- Customers with graduate degrees and skilled manual occupations were more likely to be homeowners and frequent buyers.<br/>
- Top customer: Mr. Maurice Shan – 6 orders totaling $12.4K in revenue.<br/>

🔧 Product Analysis<br/>
- Tires and Tubes were the most ordered subcategory (9,084 units).<br/>
- Helmets had relatively higher return percentages, raising potential quality or sizing concerns.<br/>
- Products with adjusted profit spikes (e.g., Water Bottle – 30 oz.) were highlighted for their strong upward trends.<br/>

## **Recommendations**
1. Optimize Inventory for High-Demand Items
    - Focus restocking and promotions on top movers like tires, tubes, and bottle cages.

2. Investigate Helmet Returns
    - High return percentages in helmet products suggest fit or quality issues that should be reviewed.

3. Personalized Marketing for High-Income Customers
    - Launch tailored campaigns to target customers with higher spending potential.

4. Expand in Top Regions
    - Strengthen presence in the U.S., Australia, and Canada where revenue and order volumes are strongest.

5. Seasonal Promotions
    - Leverage monthly and quarterly revenue trends to time promotions and new product launches effectively.
