# Global Sales Performance & Insights – Mysellar Operations
A data-driven overview of profitability, sales trends, and regional performance.

## Introduction
This project looks at global sales data from **Mysellar**, a retail company with a presence in different regions and product categories. The aim was to gain insights into sales performance, shipping times, and overall profitability. I also brought in GDP data to better understand market potential in Sub-Saharan Africa. Working on this helped me improve my Power BI skills, especially in DAX, data visualization, and presenting business insights clearly.

## Project Overview
This project involved analyzing historical sales data for **Mysellar**, a global retail company. The analysis aimed to uncover insights into sales performance, profitability, shipping efficiency, and potential market opportunities using Power BI.

## Objectives
- Compare yearly profits trends across sales channels (online vs offline)
- Examine monthly revenue and profit trends for seasonality or performance dips
- Identify top and bottom-performing countries by order volume
- Analyze category-level sales trends over time to spot rising or declining product demand
- Analyze shipping efficiency across regions based on average delivering time
- Assess correlation between GDP and sales in Sub-Saharan Africa to inform market strategy
- Highlight top revenue contributor by product category using donut chart
- Demonstrate dashboard design best practices: clean visuals, filters, and user-focused insights
- Support data-driven recommendations on which markets or products to prioritize

## Tools & Technologies
- **Power BI Desktop**: For interactive dashboard design and data visualization
- **DAX**: For custom calculations and measures
- **Microsoft Excel**: For data cleanup and review
- **Wikipedia**: For GDP data on Sub-Saharan African countries

## Techniques & Skills Applied
- Data cleaning and transformation in Power BI
- DAX-based measures and calculated columns (e.g., Profit, Shipping Days, Order Volume)
- Time-series and KPI trend analysis
- Bookmarks
- Country-level ranking using `RANKX`
- External data enrichment and correlation analysis
- Data Visualisation and dashboard UX design

## 🌐 Data Sources
- **Primary Dataset**: Mysellar Global Sales (Excel)
- **Supplementary Dataset**:
<a href = "https://en.wikipedia.org/wiki/List_of_African_countries_by_GDP_(nominal)"> GDP data from Wikipedia for Sub-Saharan Africa </a>

## Data Model
- Single-table model using the `Orders` sheet
- Added custom columns:
  - `Profit`
  - `Order Year`
  - `Shipping Days`
  - `Order Volume`
- Merged GDP dataset by country for correlation analysis

## Dashboard Insights
- Online vs. offline channels contributed nearly equally to total profits
- Baby Food and Cosmetics were top-performing product categories
- Regions with the highest revenue also showed the most efficient shipping times
- Top 5 and bottom 5 countries identified by strict order volume ranking
- A moderate correlation observed between GDP and sales in Sub-Saharan Africa

## GDP & Sales Analysis
Using external GDP data, a scatter plot was created to examine correlation with sales figures in Sub-Saharan countries. Key insights included:
- Nigeria: High GDP but underperforming in sales (potential market gap)
- Burundi: Consistently low sales aligned with economic data
- Positive correlation suggests sales potential may align with national GDP

## ✅ Recommendations
- Focus on high-order volume regions for continued investment
- Explore expansion into countries with strong GDP but low sales
- Improve shipping logistics in underperforming regions
- Monitor product category performance to optimize inventory and marketing

> 🔗 For full dashboard visuals and insights, visit: [Insert Portfolio Link or Power BI Public Link]

