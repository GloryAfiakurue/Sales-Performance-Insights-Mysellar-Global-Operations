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

## Data Sources
- **Primary Dataset**: Mysellar Global Sales (Excel)
- **Supplementary Dataset**:
<a href = "https://en.wikipedia.org/wiki/List_of_African_countries_by_GDP_(nominal)"> GDP data from Wikipedia for Sub-Saharan Africa </a>

## Data Model
The data was first normalised in Excel before being transformed in Power Query. Profit was calculated as the difference between Total Revenue and Total Cost for each sales transaction, Shipping Days as Delivery Date - Order Date
Order Volume, Top 5/Bottom 5 Country Ranking, Sales Correlation with GDP using calculated column in Power BI with DAX.
Merged GDP dataset by country for correlation analysis

![Data Model](https://github.com/GloryAfiakurue/Sales-Performance-Insights-Mysellar-Global-Operations/blob/main/Images/Final%20Model%20View.png)

## Dashboard Insights
- Online vs. offline channels contributed nearly equally to total profits
- Baby Food and Cosmetics were top-performing product categories
- Regions with the highest revenue also showed the most efficient shipping times

### Overview
Mysellar’s global sales performance from 2019 to 2021, highlighting key business metrics:
-Total Revenue: $1.32 billion
-Total Profit: $389 million
-Total Orders: 1,000

The Top 5 countries by order volume with (Vanuatu: 13 orders) and Bottom 5 (Cambodia, Cape Verde: 1 order each).

The dashboard shows a notable trend as countries with high GDP like Nigeria had low sales, while low-GDP countries like Eritrea and Burundi showed stronger sales, suggesting untapped potential and growth opportunities.

![Dashboard](https://github.com/GloryAfiakurue/Sales-Performance-Insights-Mysellar-Global-Operations/blob/main/Images/Final%20Dashboard.png)

## GDP & Sales Analysis
Using external GDP data, a scatter plot was created to examine correlation with sales figures in Sub-Saharan countries.

- Nigeria: High GDP but underperforming in sales (potential market gap)

- Burundi: Consistently low sales aligned with economic data

- While economic size (GDP) typically influences purchasing power, there is no strong positive correlation between GDP and Mysellar’s sales revenue in Sub-Sahara Africa.

![Gdp Vs Mysella Sales Performance](https://github.com/GloryAfiakurue/Sales-Performance-Insights-Mysellar-Global-Operations/blob/main/Images/Final%20Gdp%20Vs%20Mysellar%20Sales%20Performance%20by%20Countries%20-%20Sub-Sahara%20Africa.png)

## Recommendations

- Focus on high-order volume regions for continued investment

- Explore expansion into countries with strong GDP but low sales

- Improve shipping logistics in underperforming regions

- Monitor product category performance to optimize inventory and marketing
  
Mysellar should look into boosting sales in high-GDP countries like Nigeria and South Africa where performance is still low. There’s room to grow if the right strategies are used. Also, working on reducing shipping time in some regions could improve customer experience. It’s key to keep tracking sales trends across regions and categories to guide better decisions.

> 🔗 For full dashboard visuals and insights, visit: [Insert Portfolio Link or Power BI Public Link]

