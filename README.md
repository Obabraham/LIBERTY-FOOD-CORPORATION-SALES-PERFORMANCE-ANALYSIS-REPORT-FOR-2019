![Lyberty Food Corp  Analysis](https://github.com/user-attachments/assets/e0994697-c670-46f7-95e1-de9926a991f1)
# LIBERTY-FOOD-CORPORATION-SALES-PERFORMANCE-ANALYSIS-REPORT-FOR-2019
The purpose of this analysis is to analyze the sales performance of Liberty Food Corp. for the year 2019. The analysis provides insights into key performance indicators such as sales by region, category, and representative, identifying top performing products, customers, and shipping locations.
2.2 Objective of the Project 
The primary objectives of this analysis are:
a.	To evaluate the overall revenue performance of Liberty Food Corp. in 2019.
b.	To identify top-performing sales representatives, companies, and shipping locations.
c.	To assess sales trends over the year and determine the best-performing months.
d.	To categorize revenue by sales category, transaction amount, and geographical region.
e.	To derive actionable insights that can inform business strategies and improve future performance.

2.3 Problem Being Addressed 
Liberty Food Corp. seeks to understand its sales dynamics by identifying factors contributing to revenue generation. The company requires a structured analysis to determine:
a.	Which products and categories drive the highest sales?
b.	Who are the most successful sales representatives and top customers?
c.	What regions and cities generate the highest revenue?
d.	What seasonal patterns impact sales trends?
e.	How transaction sizes affect revenue distribution?
By addressing these problems, the company can make informed decisions on sales strategies, resource allocation, and potential areas for expansion.

2.4 Key Dataset and Methodologies

2.4.1 Key Dataset 
The dataset used for this analysis includes sales data from Liberty Food Corporation for the year 2019 downloaded from Kaggle.com. Key data points include:
•	Total revenue for the year: $436,066.16
•	Sales distribution by sales representatives
•	Revenue by product category
•	Performance by top customers and regions
•	Monthly sales trends
•	Transaction distribution by amount
•	Sales distribution by shipping city and country

2.4.2 Methodologies 
The following methodologies were employed in analyzing the data:
a.	Data Collection and Aggregation: Sales data was compiled from different sources and consolidated to create a structured dataset.
b.	Descriptive Analytics: Key performance indicators were calculated, including revenue figures, top performers, and sales trends.
c.	Visualization Techniques: Graphs, charts, and pie diagrams were used to represent trends, categorical distributions, and regional sales.
d.	Comparative Analysis: The performance of different categories, sales representatives, and locations was compared to identify top contributors.
e.	Trend Analysis: Monthly revenue patterns were studied to determine peak sales periods and seasonal effects.

3.0 STORY OF THE DATA
3.1 Data Source
The dataset was downloaded from Kaggle.com, a popular platform for open datasets. 

3.2 Data Collection Process
The dataset consists of transactional sales data collected from Liberty Food Corporation’s internal systems, including: Sales invoices and receipts, Customer records, Shipping and logistics reports, Product categorization and pricing details.

3.3 Data Structure
The dataset is structured into multiple attributes representing key business metrics, including:
a.	Sales Representatives: Performance metrics for individual salespeople.
b.	Revenue & Trends: Monthly revenue and sales distribution.
c.	Product Categories: Sales volume per product type.
d.	Customers & Regions: Top customers and high-revenue shipping locations.
e.	Transactions: Order value distribution based on transaction amounts.

3.4 Important Features and Their Significance
a.	Revenue by Year & Month: Identifies peak business periods and seasonal trends.
b.	Sales by Representative: Evaluates the contribution of individual salespersons to overall revenue.
c.	Top Cities & Regions by Revenue: Highlights high-performing locations for targeted marketing strategies.
d.	Product Category Sales: Determines best-selling product lines for inventory management.
e.	Top 10 Customers: Helps in customer retention and personalized marketing efforts.
f.	Transaction Amounts: Reveals spending patterns and order value distribution.

3.5 Data Limitations & Biases
a.	Geographical Bias: The data focus more on specific regions, missing insights from underrepresented areas.
b.	Timeframe Limitation: Only covers the year 2019, lacking long-term trend analysis.
c.	Customer Segmentation: Limited insights on customer demographics or purchasing behavior beyond revenue figures.
d.	Possible Data Gaps: Missing or incomplete transaction records could impact accuracy.

4 DATA SPLITTING AND PREPROCESSING 
4.0 Purpose
Data splitting and preprocessing are critical steps in preparing data for analysis and modeling. The goal is to ensure data quality, remove inconsistencies, and structure the dataset in a way that enables meaningful insights. This process ensures that sales data can be used for reporting, predictive analytics, and decision-making within the food distribution industry.

4.1 Data Cleaning
This dataset a cleaned as downloaded from Kaggle.com. However steps were taken to ensure it’s properly cleaned, these includes
a.	Removing Duplicates: A test to ensure there’s no repeated sales transactions that could distort revenue calculations.
b.	Standardizing Formats: Ensuring consistent formatting for headings such as dates, currency, and categorical labels (e.g., city names, product categories).
c.	Correcting Inconsistencies: Resolving data discrepancies, such as different spellings for the same city or missing product names.
d.	Standard Excel Table: Ensuring the dataset is on standard excel table

4.2 Handling Missing Values
None identified – dataset was complete.
4.3 Data Transformations
•	Aggregated revenue by city, region, and customer
•	Grouped sales into transaction amount bands (e.g., $0–$1000)

4.4 Data Splitting
a.	Dependent data points: Values that can stand alone and influences other points and still make complete meaning. Such as shown above
b.	Independent data points: Values that cannot stand alone, influences other points and make complete meaning. Such as shown above
Category 1: Independent data points – Customers name, Sales person, Region, Ship name, Ship country, Category, Payment type, Product name, Ship City
Category 2: Dependent data - Unit price, Quantity, Revenue, Shipping fee
4.5 Industry Context
This dataset belongs to the food distribution and sales industry, where companies manage product categories, customer relationships, and sales representatives to drive revenue. Understanding sales performance is crucial for: Inventory management, Demand forecasting, Regional sales strategy, Customer retention and segmentation.

4.6 Stakeholders
The key stakeholders who benefit from this analysis include:
a.	Sales Managers: Optimize sales force allocation and performance monitoring.
b.	Supply Chain & Logistics Teams: Improve shipping and regional distribution efficiency.
c.	Finance Departments: Monitor revenue trends and financial performance.
d.	Marketing Teams: Identify high-value customers and target profitable product categories.
e.	Executive Leadership: Make data-driven decisions for business growth.

4.7 Value to the Industry
Preprocessed and well-structured data unlocks significant value for the food industry:
a.	Better decision-making by identifying sales trends and revenue-driving factors.
b.	Improved forecasting by enabling predictive models for demand planning.
c.	Enhanced customer insights by helping in targeting key customers and improving retention.
d.	Operational efficiency by streamlining logistics and inventory management.
e.	Competitive advantage by providing a data-driven approach to outperform competitors.

5. PRE-ANALYSIS
Key Trends Identified
5.1 Sales by Representative
a.	Top Performer: Nancy Freehafer is the highest-grossing salesperson, generating $104,242.34 in revenue.
b.	Second and Third Best: Andrew Cencini follows with $93,848.33, while Laura Giussani generated $42,370.88.
c.	Disparity in Sales: The lowest-performing representative, Robert Zare, recorded only $16,350.50, showing a wide gap in performance.
Insight: Training or sales strategy adjustments could improve the performance of lower-tier sales reps.

5.2 Sales by Category
a.	Top-Selling Category: Beverages led with $110,577.11, significantly higher than other categories.
b.	Other Strong Categories: 
o	Sauces: $69,000.00
o	Jams & Preserves: $51,541.00
o	Dairy Products: $33,129.60
c.	Least Selling Category: Canned Meat recorded the lowest sales at $25,465.60.
Insight: Beverages are the dominant product, potentially due to higher demand or higher profit margins. Canned Meat sales might need strategic intervention such as promotions or bundling.

5.3 Sales by Region
a.	Highest Revenue Region: The North generated $141,660.34, significantly outperforming other regions.
b.	Other Regions: 
o	East: $108,257.91
o	South: $93,848.33
o	West: $91,251.98
Insight: The North region is a key revenue driver. Further analysis could determine if population density, customer preferences, or logistics play a role.

5.4 Top Ship Cities by Revenue
a.	Highest-Grossing City: New York recorded $67,180.50 in revenue, followed by Portland $50,198.35.
b.	Other Major Cities: Miami, Memphis, and Chicago all generated over $40,000 in sales.
Insight: Targeted marketing or supply chain optimizations could improve performance in lower-performing cities.

5.5 Top Customers by Revenue
a.	Highest-Grossing Customer: Company D, with $67,180.50 in purchases.
b.	Other Key Customers: Company BB $50,198.35, Company A $36,839.99, Company J $29,133.01.
Insight: The company relies on a few major customers. Retaining them and expanding the customer base should be a priority.

5.6 Monthly Sales Trends
a.	Best-Performing Month: December ($66,642.78) saw the highest revenue, likely due to holiday demand.
b.	Lowest Sales Months: February ($19,955.50) and April ($20,771.79) had the lowest revenue.
Insight: Seasonal demand plays a role in revenue fluctuations. Promotional strategies could boost sales in off-peak months.

5. POTENTIAL CORRELATIONS IDENTIFIED
5.1.1 Sales Representative vs. Revenue Contribution
•	Higher revenue appears linked to individual sales rep performance, with top sellers significantly outperforming others.
Potential Action: Performance-based incentives or training programs for lower-performing reps.

5.1.2 Product Category vs. Regional Demand
a.	Beverages led across all regions, indicating consistent demand.
b.	Some lower-selling categories (e.g., Canned Meat) might have untapped regional potential.
c.	Potential Action: Focused regional marketing to boost underperforming product categories.

5.1.3 Customer Type vs. Sales Contribution
a.	Large customers (e.g., Company D, BB) contribute the bulk of revenue.
b.	Over-reliance on a few customers could be risky if any of them leave.
c.	Potential Action: Diversify customer base by acquiring mid-sized buyers.

5.1.4 Seasonal Impact on Sales
a.	December is the peak sales month, while February and April are slow months.
b.	Potential Action: Introduce targeted promotions in off-peak months.

5.2.1 INITIAL INSIGHTS
1.	Boost Sales Rep Performance: Address the gap between top and low-performing sales representatives through training and incentives.
2.	Expand Product Focus: Beverages dominate, but lower-performing categories (Canned Meat, Dried Fruits & Nuts) may need better marketing or bundling strategies.
3.	Strengthen Regional Sales: The Northern region is the strongest, but strategies should be explored to boost weaker regions.
4.	Diversify Customer Portfolio: Dependence on a few top customers is a risk—expanding the customer base is crucial.
5.	Seasonal Promotions: Implement marketing strategies in low-sales months (e.g., February, April) to smooth out revenue fluctuations.

6 IN-ANALYSIS
6.0 UNCONFIRMED INSIGHTS & AREAS REQUIRING FURTHER VALIDATION
6.1 Sales Performance by Representative
Observation:
a.	Nancy Freehafer is the top-performing sales rep ($104,242.34), followed by Andrew Cencini ($93,848.33).
b.	The remaining three sales reps have significantly lower sales, creating a major performance gap.
Unconfirmed Insight:
a.	Are the lower-performing sales reps serving different customer segments or regions that affect their sales performance?
b.	Is there a seasonal variation in individual sales performance that needs validation?

6.2 Product Category Performance
Observation:
	Beverages dominate sales at $110,577.11, while canned meat has the lowest sales ($25,465.60).
Unconfirmed Insight:
a.	Is the demand for beverages consistent throughout the year, or is it seasonal?
b.	Does a specific region or customer group contribute disproportionately to the success of beverages?

6.3 Sales Trends & Seasonality
Observation:
a.	December has the highest sales ($66,642.78), while February and April have the lowest.
b.	Mid-year months like June and October show moderate peaks.
Unconfirmed Insight:
a.	Are these trends driven by promotional campaigns, seasonal demand, or external factors like supply chain issues?
b.	Do specific products show different seasonal patterns?

6.4 Customer Distribution & Revenue Impact
Observation:
	Company D contributes the highest revenue ($67,180.50), followed by Company BB and Company A.
Unconfirmed Insight:
a.	How dependent is the business on these top customers?
b.	If one of these top customers stops purchasing, how much impact will it have on overall revenue?


7. POST-ANALYSIS AND INSIGHTS

7.1 KEY FINDINGS AND COMPARISON WITH INITIAL FINDINGS

7.2 Sales Performance by Representative
Comparison with Initial Findings:
a.	The disparity among sales reps remains unchanged, reinforcing the need for training or incentive-based performance models.
b.	The top two reps alone generate ~45% of total sales, highlighting dependency on a few individuals.

7.3 Sales by Product Category
Comparison with Initial Findings:
a.	Beverages maintain dominance and remain a key revenue driver.
b.	Canned Meat is consistently underperforming, meaning promotional campaigns or new distribution strategies are needed.
c.	Jams & Preserves perform better than expected, suggesting seasonal demand might influence sales.

7.4 Sales by Region
Comparison with Initial Findings:
a.	The North remains the most critical market, meaning expansion efforts should be concentrated there.
b.	The West continues to lag, confirming the need for improved logistics, advertising, or partnerships.

7.5 Sales Trends (Monthly Analysis)
Comparison with Initial Findings:
a.	Seasonal trends are evident, supporting the need for promotional efforts in weak months (Q1 & Q2).
b.	December sales confirm the importance of holiday promotions.
c.	June & October show mid-year peaks, suggesting successful marketing efforts during these periods.

7.6 Customer Segmentation
Comparison with Initial Findings:
a.	Top customers contribute a major portion of sales, making customer retention crucial.
b.	Expanding to smaller clients can reduce risk and improve long-term stability.

7.7 Ship Cities and Regional Demand
Comparison with Initial Findings:
a.	New York remains the top shipping hub, reinforcing its importance in logistics planning.
b.	Portland & Miami show potential for expansion.
c.	Cities with lower sales (Chicago, Memphis) need targeted marketing efforts.

9. Recommendations and Observations
OBSERVATION
The following observations were made in course of the analysis:
1.	Nancy Freehafer is the top-performing sales rep, generating $104,242.34, followed by Andrew Cencini ($93,848.33). 
2.	The performance gap between the top two and the remaining three sales reps is significant. 
3.	Robert Zare has the lowest sales performance at $16,350.50, which is less than 20% of Nancy's sales.
4.	Beverages lead sales ($110,577.11), contributing the highest revenue, followed by Sauces ($69,000.00) and Jams & Preserves ($51,541.00). 
5.	Canned Meat ($25,465.60) has the lowest sales, followed by Dried Fruit & Nuts ($27,999.50).
6.	December had the highest sales ($66,642.78), while February ($19,955.50) and April ($20,771.79) had the lowest sales. 
7.	A sharp increase in sales was observed in May ($34,307.05) and June ($55,601.61). 
8.	The July-August period saw a decline after the mid-year peak.
9.	The North region contributed the highest sales ($141,663.34), followed by the South ($108,275.91). 
10.	The East ($93,848.33) and West ($91,251.98) lag behind in revenue.
11.	New York is the top-performing city ($67,180.50), followed by Portland ($50,198.35) and Miami ($50,145.33). 
12.	Other key cities, including Memphis, Chicago, and Milwaukee, contribute between $41,000 - $43,000.
13.	Company D is the top customer, generating $67,180.50 in revenue. 
14.	The top 5 customers contribute over $200,000, meaning a high reliance on a few large clients.
15.	Most transactions fall within the 0-1000 range, with fewer high-value transactions.

RECOMMENDATION
1.	Investigate why some sales reps are underperforming (e.g., customer segment, product type, or region limitations). 
2.	Implement sales training programs for lower-performing reps. 
3.	Introduce performance-based incentives to encourage better sales results
4.	Increase marketing and promotions for low-performing categories to boost demand. 
5.	Conduct a regional demand analysis to identify which areas have lower adoption of canned meat and dried fruits. 
6.	Introduce bundling strategies (e.g., pairing canned meat with best-selling items like sauces)
7.	Investigate seasonal factors (holidays, promotions, external market trends) affecting December’s strong performance.
8.	Launch sales campaigns in February and April to increase revenue during slow months.
9.	Utilize historical data for forecasting and stock optimization before peak sales months (e.g., December).
10.	Conduct regional preference analysis to understand why some areas underperform.
11.	Increase salesforce allocation in the East & West regions to drive more engagement.
12.	Target localized marketing campaigns to boost brand penetration.
13.	Analyze New York’s success factors and replicate them in lower-performing cities. 
14.	Introduce region-specific promotions and discounts in Chicago, Milwaukee, and Memphis to boost engagement. 
15.	Conduct customer feedback surveys in cities with lower revenue to identify potential improvements.
16.	Reduce dependency on top clients by expanding the customer base with new business acquisitions. 
17.	Introduce customer loyalty programs to retain high-value clients. 
18.	Conduct churn risk analysis to track purchasing behavior changes in major clients.
19.	Offer bulk discounts or incentives to encourage larger transactions. 
20.	Introduce tiered pricing models to upsell higher-value packages. 
21.	Improve customer segmentation strategies to identify buyers who may be interested in larger purchases.

10 CONCLUSION
The 2019 Performance Analysis for Liberty Food Corp. highlights significant strengths in sales performance while also identifying key areas that require improvement. The data-driven insights from the dashboard emphasize the company's top-performing sales representatives, best-selling products, high-revenue regions, and seasonal sales trends. However, certain challenges such as underperforming product categories, regional disparities, and reliance on a few key customers indicate opportunities for growth.
Key Learning:
1.	Top Performers Drive Revenue
	Nancy Freehafer and Andrew Cencini collectively account for a major portion of sales.
	New York leads in revenue among all cities, followed by Portland and Miami.
2.	Product Sales Insights
	Beverages are the strongest category, generating over $110,577.11 in revenue.
	Canned meat and dried fruits underperform, indicating a need for better marketing or product positioning.
3.	Sales Trends and Seasonal Fluctuations
	December had the highest sales ($66,642.78), while February and April were the weakest months.
	The company experiences mid-year fluctuations, suggesting the need for a balanced sales strategy throughout the year.
4.	Regional Performance Disparities
	The Northern region dominates sales ($141,663.34), while the East and West lag behind.
	Strategic regional expansion and localized promotions are required to boost sales in weaker regions.
5.	Customer Dependency Risk
	A high concentration of revenue comes from a few top clients (e.g., Company D, Company BB).
	Expanding the customer base and diversifying revenue sources is essential to minimize risk.
6.	Transaction Size and Growth Opportunities
	A large number of low-value transactions (0-1000 range) indicate potential for upselling and bulk purchase incentives.
	Encouraging larger transactions through pricing strategies and loyalty programs can boost revenue.
Future Research:
•	Enhance Sales Performance by setting performance-based incentives and providing training to underperforming sales representatives.
•	Revitalize Low-Performing Products by bundling them with high-demand items or offering discounts.
•	Develop a Year-Round Sales Strategy to balance sales across months and prevent seasonal slowdowns.
•	Expand into Underperforming Regions with targeted marketing and additional sales support.
•	Diversify the Customer Base to reduce dependency on a few key clients and sustain long-term revenue growth.
•	Encourage Higher Transaction Values by introducing bulk discounts and premium product packages.

11. REFERENCES & APPENDICES
	References
	Internal Sales Database 
	Microsoft Excel Documentation
	Kaggle.com
APPENDICES
	Full Dashboard Screenshots
	Pivot Table Configurations
	Formula List (e.g., SUMIFS, VLOOKUP examples)
