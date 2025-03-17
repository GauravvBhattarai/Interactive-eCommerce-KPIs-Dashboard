# Yorkshire Yard’s Performance Analysis: Interactive Power BI Dashboard

# Introduction
This project analyzes the sales performance of YorkshireYards, an e-commerce platform operating in the UK market. The analysis focuses on identifying key trends, customer behaviors, and product category performance to drive strategic decision-making and optimize business operations. Using Power BI, an interactive dashboard is developed that visualizes critical KPIs and provides actionable insights for stakeholders across the organization.
The UK e-commerce market has experienced significant growth in recent years, with increasing competition and changing consumer preferences. In this dynamic environment, data-driven decision-making has become essential for maintaining competitive advantage and ensuring sustainable business growth. In today’s digital marketplace, e-commerce businesses like Yorkshire Yards need real-time insights to make data-driven decisions. The dataset includes order details, financial metrics, product categories, and payment modes. 

# Project Objective
The primary goal of this project was to develop an interactive dashboard that provides in-depth insights into the Yorkshire Yard’s performance across various dimensions. Specifically, the dashboard aims to:
1.	Monitor key performance indicators (KPIs) including total sales, quantity sold, profit, and average order value
2.	Analyze regional performance across the UK to identify high-potential markets
3.	Evaluate product category and sub-category performance to optimize inventory and marketing strategies
4.	Understand customer purchasing patterns and payment preferences
5.	Track profit trends over time to identify seasonality and growth opportunities
6.	Enable data-driven decision-making through interactive filtering capabilities

# Why This Dashboard is Useful
This dashboard serves as a centralized hub for stakeholders across the organization to access and analyze crucial business metrics. Its value lies in:
1.	Democratizing Data Access: Providing user-friendly visualizations that make complex data understandable to stakeholders with varying levels of analytical expertise
2.	Enabling Real-Time Decision Making: Allowing quick identification of trends, opportunities, and potential issues (including seasonal patterns)
3.	Supporting Strategic Planning: Offering insights that inform inventory management, marketing campaigns, and expansion strategies
4.	Facilitating Performance Tracking: Monitoring progress against targets and identifying areas for improvement
5.	Enhancing Customer Understanding: Revealing customer preferences and behaviors that can drive personalization and improve customer experience (like payment methods and product preferences) 
# Dashboard Overview

The dashboard provides a comprehensive view of the Yorkshire Yard’s business performance with the following key components:
•	KPI Cards: Displaying total sales (£438K), quantity sold (5,615 units), total profit (£37K), and average order value (£121.01K)
•	GMV by Region: Bar chart showing sales performance across UK regions with Worcestershire, Glamorgan, Staffordshire, and Essex as top performers
•	Top Performing Categories: Donut chart illustrating category distribution (Clothing 63%, Electronics 21%, Furniture 17%)
•	Profit by Month: Line chart tracking monthly profit trends throughout the year
•	Top Performing Buyers: Bar chart identifying highest-value customers
•	GMV by Payment Mode: Donut chart showing payment method preferences (COD 44%, PayPal 21%, Debit Card 13%, Credit Card 12%, EMI 10%)
•	Profit by Sub-Category: Bar chart comparing profitability across product sub-categories, with Printers and Bookcases as top performers
# How to Use the Dashboard
The dashboard is designed for intuitive navigation and exploration:
1.	Quarter Selection: Use the quarter tabs (Qtr 1 to Qtr 4) at the top right to filter data by specific quarters
2.	State Filter: Select specific states or regions from the dropdown menu to focus on particular geographic areas
3.	Cross-Filtering: Click on any visual element to filter related visualizations accordingly 
o	For example, clicking on "Clothing" in the category chart will update all other visuals to show data related only to clothing products
4.	Hover Interactions: Hover over any visual element to see detailed information in tooltips
5.	Profit Analysis: Compare monthly profits and identify peak sales periods.
6.	Category Performance: Assess which products contribute the most to revenue and profit.
7.	Reset Filters: Use the "All" option in filters to return to the complete dataset view


# Key Questions (KPIs) Answered
This dashboard was designed to answer critical business questions:
1.	Sales Performance: What is our total revenue, and how does it vary across regions and periods?
2.	Product Analysis: Which product categories and sub-categories are most profitable?
3.	Customer Insights: Who are our top customers, and what are their purchasing patterns?
4.	Payment Preferences: Which payment methods are most popular among our customers?
5.	Seasonal Trends: How does our profit fluctuate throughout the year?
6.	Regional Opportunities: Which geographic regions show the highest sales potential?
7.	Operational Efficiency: What is our average order value, and how can we increase it?

# Process
This project followed a structured approach to data analysis and visualization:
1.	Data Collection: Gathered transactional data from the e-commerce platform, including order details, customer information, product categories, and payment methods.
2.	Data Preparation:
o	Cleaned and transformed raw data to ensure consistency and accuracy
o	Created relationships between different data tables (Orders and Customers)
o	Calculated derived metrics such as Average Order Value (AOV)
o	Aggregated data by appropriate dimensions (month, region, category, etc.)
3.	Dashboard Design:
o	Identified the most relevant metrics based on business objectives
o	Selected appropriate visualization types for each metric
o	Designed an intuitive layout with a logical grouping of related information
o	Implemented interactive features for enhanced user experience (Location and Quarter Filters)
4.	Analysis:
o	Examined trends and patterns across different dimensions
o	Identified correlations between various metrics
o	Uncovered insights to answer key business questions
5.	Documentation:
o	Captured methodology, insights, and recommendations
o	Created a user guide for dashboard navigation and interpretation
# Key Insights and Business Implications in the UK
1. Regional Performance Variations
Findings:
•	Worcestershire significantly outperforms other regions with the highest GMV
•	Glamorgan, Staffordshire, and Essex follow as strong secondary markets
•	Substantial disparity exists between top and bottom-performing regions
Implications:
•	Market penetration varies significantly across UK regions
•	Regional consumer preferences or marketing effectiveness differences may exist
•	Opportunities for targeted expansion in high-performing areas
Dashboard Utility:
•	The regional GMV chart allows stakeholders to quickly identify regional strengths and weaknesses
•	Quarter filters help detect seasonal variations in regional performance
•	Insights inform resource allocation for regional marketing campaigns
2. Product Category Dominance
Findings:
•	Clothing dominates sales with 63% of the category share
•	Electronics (21%) and Furniture (17%) contribute significantly but lag behind Clothing
•	Within sub-categories, Printers and Bookcases generate the highest profit margins
Implications:
•	The business has established a strong positioning in the clothing sector
•	Electronics and furniture categories present growth opportunities
•	High-profit sub-categories should be prioritized in inventory and marketing decisions
Dashboard Utility:
•	Category distribution visualizations highlight portfolio strengths and weaknesses
•	Sub-category profit analysis identifies specific product lines for investment
•	Cross-filtering allows examination of category performance across regions and periods
3. Seasonal Profit Fluctuations
Findings:
•	Profit shows strong performance in Q1 (January-March)
•	Significant dip occurs during summer months (May-June)
•	Negative profit in July and December indicates potential issues
•	Strong recovery in September-November period
Implications:
•	Seasonal buying patterns heavily influence profitability
•	Summer months may require promotional strategies to boost sales
•	Holiday season (December) shows high sales volume but reduced margins
•	Q1 and Q4 (excluding December) present prime opportunities for maximizing profits
Dashboard Utility:
•	Monthly profit tracking enables seasonal planning and forecasting
•	Quarter selection feature allows focused analysis on problematic or high-performing periods
•	Trend visualization facilitates year-over-year comparison and goal setting
4. Payment Method Preferences
Findings:
•	Cash on Delivery (COD) is the preferred payment method (44%)
•	Digital payment options (PayPal 21%, Debit Card 13%, Credit Card 12%) collectively account for 46%
•	Instalment payments (EMI) represent 10% of transactions
Implications:
•	UK customers show a strong preference for traditional payment methods
•	Opportunity exists to incentivize digital payment adoption
•	The EMI option appeals to a significant minority, suggesting price sensitivity for some customers
Dashboard Utility:
•	Payment mode distribution highlights consumer payment preferences
•	Cross-filtering by region reveals geographic variations in payment behaviors
•	Insights inform checkout optimization and payment gateway strategies
5. Customer Concentration
Findings:
•	"Margaret" emerges as the highest-value customer with significantly higher spending than others
•	Top 6 customers represent a substantial portion of overall revenue
•	Clear spending tiers exist among top customers
Implications:
•	Business has high dependency on a small customer base
•	Opportunity to develop loyalty programs for high-value customers
•	Need to expand customer base to reduce concentration risk
Dashboard Utility:
•	Top customer visualization identifies VIP clients for relationship management
•	Customer data can be filtered by product categories to understand preferences
•	Analysis informs personalized marketing strategies for customer retention

# Business Recommendations
Based on the insights derived from the dashboard, the following strategic recommendations are proposed:
1. Regional Expansion Strategy
Recommendation: Develop a targeted expansion plan for Worcestershire and Glamorgan while investigating underperforming regions.
Implementation:
•	Increase marketing budget allocation for high-performing regions by 20%
•	Conduct market research in underperforming regions to identify barriers
•	Test localized marketing messages based on regional preferences
•	Consider physical pop-up stores in Worcestershire to strengthen brand presence
Expected Outcome: 15% increase in GMV from top regions and 25% improvement in underperforming areas within 6 months.
2. Product Portfolio Optimization
Recommendation: Rebalance inventory and marketing focus toward high-margin sub-categories while expanding the clothing category assortment.
Implementation:
•	Increase inventory allocation for Printers and Bookcases by 30%
•	Develop exclusive clothing lines to capitalize on category strength
•	Implement cross-selling strategies between complementary categories
•	Reduce investment in low-margin sub-categories
Expected Outcome: 10% increase in overall profit margin and 20% growth in high-margin sub-categories within 12 months.
3. Seasonal Promotion Calendar
Recommendation: Develop a comprehensive promotional calendar to address seasonal fluctuations and boost performance during low periods.
Implementation:
•	Create targeted summer campaigns (May-June) to counteract seasonal dip
•	Implement margin-protection strategies during the December holiday season
•	Capitalize on strong Q1 performance with new product launches
•	Develop "back to school" promotions for the August/September transition
Expected Outcome: Reduction of negative profit months and 25% increase in summer month sales within the next annual cycle.
4. Payment Optimization Initiative
Recommendation: Incentivize digital payment adoption while optimizing the COD fulfillment process.
Implementation:
•	Offer a 5% discount on first-time digital payment transactions
•	Streamline COD processes to reduce operational costs
•	Expand EMI options to higher-value items across all categories
•	Implement secure and seamless digital payment experiences
Expected Outcome: 15% shift from COD to digital payments and 5% reduction in payment processing costs within 9 months.
5. Customer Relationship Management
Recommendation: Implement a tiered loyalty program while expanding the customer base through referral incentives.
Implementation:
•	Develop a VIP program for the top 10% of customers with exclusive benefits
•	Create referral incentives for existing customers to attract new shoppers
•	Implement a personalized recommendation engine based on purchase history
•	Establish regular communication cadence with high-value customers
Expected Outcome: 20% increase in repeat purchase rate and 15% growth in new customer acquisition within 6 months.

# Next Steps
To build upon the current dashboard and further enhance data-driven decision-making, the following next steps are recommended:
1.	Enhanced Data Collection:
o	Implement tracking for customer browsing behavior and cart abandonment
o	Collect customer demographic data for more targeted segmentation
o	Incorporate social media engagement metrics to correlate with sales performance
2.	Advanced Analytics Integration:
o	Develop predictive models for sales forecasting
o	Implement customer lifetime value calculations
o	Create product affinity analysis to identify complementary items
3.	Dashboard Expansion:
o	Add competitor benchmarking visualization
o	Incorporate marketing campaign performance metrics
o	Develop inventory turnover and stock level monitoring
4.	Automation and Alerts:
o	Set up automated alerts for significant changes in key metrics
o	Schedule regular report distribution to stakeholders
o	Implement anomaly detection for early identification of issues
5.	Mobile Optimization:
o	Develop a mobile-friendly dashboard version for on-the-go access
o	Create an executive summary view for the leadership team
o	Implement role-based access controls for different stakeholder groups
# Conclusion
The Yorkshire Yard’s E-Commerce sales dashboard provides valuable insights into the business performance across multiple dimensions. By visualizing key metrics and enabling interactive exploration, it transforms raw data into actionable intelligence that can drive strategic decision-making.
The analysis reveals that Yorkshire Yard has established a strong market presence in specific regions (particularly Worcestershire) and product categories (especially Clothing). However, it also identifies areas for improvement, including seasonal fluctuations, payment method optimization, and customer diversification.
By implementing the recommended strategies, the business can leverage its strengths while addressing challenges to achieve sustainable growth. The dashboard will continue to serve as a vital tool for monitoring performance, identifying trends, and measuring the impact of strategic initiatives.
This project demonstrates the power of data visualization in transforming business operations and strategy. As the market continues to evolve, the ability to quickly access and interpret data will remain a critical competitive advantage. This dashboard represents not just a reporting tool, but a strategic asset that can drive Yorkshire Yard’s success in the dynamic UK e-commerce landscape.
