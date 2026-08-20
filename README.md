# Global-Superstore Analysis
A retail company needed a way for senior management to monitor sales performance, profitability, customer behavior, and regional performance without relying on manual reporting. 

![Dashboard Preview](superstore.jpg)

This project delivers an interactive Power BI dashboard that turns raw transactional data into actionable insight, answering seven core business questions:
- What is the overall sales performance of the company?
- Which regions generate the highest sales and profit?
- Which customer segments contribute the most revenue?
- Which product categories perform best?
- Which products are the most profitable?
- What trends can be observed over time?
- What should management implement to improve performance?

# Dataset
Global Superstore Dataset from Kaggle.

# Key Insights
- Sales grew 90% from 2011 to 2014 ($2.26M → $4.30M); profit grew even faster (+103%)
- The Central region and APAC market are the strongest performers by sales and profit
- Technology is the most profitable category (14% margin) vs. Furniture's 6.9%
- Sales show strong Q4 seasonality — more than double Q1 volume every year
- The Tables sub-category is unprofitable overall due to heavy discounting

# Tools & Skills Used
- Microsoft Power BI — Power Query (data cleaning & transformation), DAX (measures), interactive dashboard design
- Data cleaning — missing value checks, duplicate removal, data type correction
- Business analysis — KPI definition, trend analysis, segment/category/regional profitability analysis
- Communication — translating analytical findings into business insights and recommendations for a non-technical executive audience

For the full write up, see the Executive Summary Report.

### Week 3 Update — Advanced Analysis & BI Dashboard

Week 3 builds directly on the analysis above, adding deeper KPIs, DAX-driven measures, formal business problem investigations, and a fully interactive multi-page dashboard.

The dashboard now spans five pages:

# Page	Contents
- Executive Overview	(6 core KPIs + Year/Segment/Market filters)
- Sales & Profit Analysis	(Annual/quarterly/monthly trends, category breakdown)
- Product Performance	(Top/bottom products, category & sub-category profit)
- Geographical Performance	(Region and market breakdown)
- Customer & Segment Analysis	(High-value customers, contribution to sales, segment split)

![Dashboard Preview]()


# Business Problems Investigated
- High sales, low profit — Furniture category, driven almost entirely by the Tables sub-category
- Loss-making products — Tables, Fasteners, Labels, and Supplies post negative total profit
- Regional imbalance — Central leads on sales but converts less efficiently to profit than North; Canada and Africa remain marginal markets


# Additional Insights & Recommendations
Building on the original Key Insights above, five further evidence-based insights were developed:

- Furniture under-converts sales into profit (~7% margin vs. ~14% for Technology and Office Supplies) — targeted pricing review needed on Tables specifically, not the category as a whole
- Four sub-categories (Tables, Fasteners, Labels, Supplies) are actively losing money, not just underperforming — recommend a minimum-margin rule + monthly monitoring via the Loss-Making Orders measure
- Central's profit doesn't scale with its sales the way North's does — recommend confirming the product-mix driver before further regional investment
- Canada and Africa remain marginal markets after four years — needs a market-condition review to decide invest vs. deprioritize, rather than blanket assumptions
- The customer base is broad and not concentrated in a few accounts (top 5 customers = 1.45% of total sales combined) — a structural strength; growth efforts are better aimed at average order value than key-account retention.
