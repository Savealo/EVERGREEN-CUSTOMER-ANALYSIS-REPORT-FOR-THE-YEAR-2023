# EVERGREEN-CUSTOMER-ANALYSIS-REPORT-FOR-THE-YEAR-2023
The objective is to analyze customer transaction data from 2023 to identify key spending trends, top-performing customers, preferred products, and channels. This insight will support data-driven decisions to optimize marketing, enhance customer engagement, and increase overall business performance.
OUTLINE
	Introduction
	Story of Data
	Data Splitting and Preprocessing
	Pre-Analysis
	In-Analysis
	Post-Analysis and Insights
	Data Visualizations & Charts
	Recommendations and Observations
	Conclusion
	References & Appendices


INTRODUCTION
Objective of the Project
The objective is to analyze customer transaction data from 2023 to identify key spending trends, top-performing customers, preferred products, and channels. This insight will support data-driven decisions to optimize marketing, enhance customer engagement, and increase overall business performance.
Problem Being Addressed
The project addresses key business challenges such as identifying high-value customers, understanding spending patterns across different channels and times, uncovering product and category preferences, and optimizing payment methods and sales strategies to drive revenue and improve customer engagement.

Key Datasets
Customer Transactions Dataset
Contains: Customer ID, Item, Category, Quantity, Price Per Unit, Total Spent, Payment Method, Location, Transaction Date
Purpose: Core dataset for analyzing purchasing behavior and trends.
Product Information Dataset (optional/assumed)
Contains: Item descriptions, category classifications, pricing tiers
Purpose: Helps in segmenting and categorizing products accurately.
Customer Profile Dataset (optional/assumed)
Contains: Demographics, loyalty status, communication preferences
Purpose: Enables customer segmentation and personalized marketing.
Channel/Platform Dataset
Contains: Purchase platform (Online, Mobile App, In-store)
Purpose: Used to analyze shopping behavior by channel.
Ranking & Visualization:
Use of bar charts for top insurance providers and conditions.
Pie charts for gender distribution and medication usage.
Line charts to track monthly trends in admission volume.
Interactive Filtering:
Filters for admission types, insurance companies, medications, and conditions to allow dynamic exploration of insights.
Visual Design Principles:
Color-coded and icon-supported layout for immediate interpretability and accessibility.


STORY OF DATA

Data Source: The data was obtained from Kaggle.com
Data Collection Process: This data was obtained from Kaggle.com 
Data Structure: The data contains 1,002 rows with each representing a distinct individual’s details and 9 columns representing Customer ID, Category, item, Quantity, Price per unit, Total Spent, Payment  Method, Transaction Date and Location. 
Important Features and Their Significance: 
1.	Customer ID – Identifies unique customers.
2.	Category – Type of item purchased (e.g., electronics, clothing).
3.	Item – Specific product bought.
4.	Quantity – Number of units purchased.
5.	Price Per Unit – Unit price of the item.
6.	Payment Method – Mode of payment (e.g., credit card, cash).
7.	Location – Store or region of the transaction.
8.	Transaction Date – Date the purchase occurred.


Data Limitations or Biases
The 2023 Evergreen customer analysis might be limited by its single-year scope and lack of customer demographics. The definitions of "preferred" items and categories are unclear, and purchase channels might overlap. The analysis focuses on existing customers, potentially overlooking a broader market view. These factors could introduce biases in the interpretation of customer behavior and trends.

DATA SPLITTING AND PREPROCESSING
Data Cleaning: The data was cleaned by removing duplicates, identifying and removing blanks, and ensuring that no inconsistencies are observed. Thereafter, the data was converted to a standard excel table to ease analysis. 
To remove duplicate, simply copy the entire data (ctrl +shift + end) then navigate to the data tab and on the data tools ribbon to select “remove duplicates”. 
To identify and remove blanks, simply copy the entire data (ctrl +shift + end) on the home tab navigate to the editing ribbon and click “Find and select”, then navigate to  “Go to Special” and select “Blanks”, finally click on OK. 
Handling Missing Values: There are no missing values in the data.  
Data Transformations: No data transformations were performed. 
Data Splitting: The data was splitted into dependent and independent variables. 
Category One- Independent Values
Category
Item
Payment method
Location
Category Two- Dependent Values
Transaction date
Total spent
Price per Unit
Quantity

Industry Context: Retail/E-commerce: The data is generated from a business that sells products or services directly to consumers.
Story of data: The data represents customer transactions for Evergreen for the year 2023. It details what customers purchased (items and categories), how much they spent, how they paid, where they made the purchases, and when. This data can be used to understand customer behavior, spending patterns, and preferences, which can inform business decisions. The story it tells is about how Evergreen's customers interact with the business.
Stakeholders:  
1.	Marketing Department: To understand customer segmentation, campaign effectiveness, and optimize marketing spend.
2.	Sales Department: To identify top customers, track sales performance, and inform sales strategies.
3.	Product Development: To understand customer preferences and identify opportunities for new product development or product improvements.
4.	Finance Department: To analyze revenue, track spending trends, and inform financial forecasting.
5.	Management/Executive Team: To get an overview of business performance, make strategic decisions, and allocate resources effectively.

Value to the Industry:

For retail, e-commerce, or FMCG (Fast-Moving Consumer Goods) industries, this type of data is immensely valuable for:
Customer Segmentation: Identifying high-value customers, purchase frequency, and preferences.
Sales Optimization: Understanding best-selling products and underperformers.
Inventory Management: Forecasting demand based on quantity trends.
Marketing Strategy: Tailoring promotions based on category, location, or seasonality.
Operational Efficiency: Evaluating performance across locations and payment trends.


PRE-ANALYSIS
POTENTIAL QUESTIONS
1.	Who are the most frequent customers?
2.	Who are the highest-spending customers?
3.	What are the repeat purchase trends across different customer segments?
4.	Which items have the highest sales volume?
5.	Which product categories generate the most revenue?
6.	Are there seasonal patterns in customer purchases?
7.	What is the average value of a single transaction?
8.	Which payment methods are most commonly used?
9.	Which locations generate the highest revenue?
10.	Are there regional preferences for specific product categories or items?
11.	What are the busiest days or months for transactions?
12.	Are there identifiable peak seasons for certain categories?
13.	How do different pricing strategies affect the quantity purchased?
14.	What is the correlation between location and payment method preference?
15.	Are there any anomalies or outliers in transaction patterns?


POTENTIAL INSIGHTS

1.	Frequent customers can be targeted for loyalty rewards or personalized retention strategies.
2.	High spenders may benefit from VIP programs or exclusive offers.
3.	Repeat purchase trends can reveal loyal segments ideal for upselling.
4.	Best-selling items should be prioritized in inventory and marketing.
5.	Top revenue-generating categories indicate where to focus expansion or promotion.
6.	Seasonal buying patterns help time marketing and stock decisions.
7.	Average transaction value offers a benchmark to optimize basket size.
8.	Popular payment methods should be streamlined for convenience.
9.	High-revenue locations may warrant further investment or replication.
10.	Regional preferences can guide localized inventory and campaigns.
11.	Peak transaction periods help plan staffing and marketing efforts.
12.	Seasonal category peaks support timely procurement and promotions.
13.	Pricing impacts on quantity help fine-tune discounting strategies.
14.	Regional payment preferences inform tailored checkout experiences.
15.	Anomalies in transactions can uncover fraud, errors, or new trends


IN-ANALYSIS
KEY INSIGHTS

Customer Loyalty and Value
A small group of frequent and high-spending customers likely drives a large portion of revenue, making them prime targets for loyalty and personalized marketing strategies.
Top-Performing Products and Categories
Certain items and categories consistently generate high sales and revenue, indicating where to focus inventory, promotions, and product development.
Seasonality and Timing
Clear seasonal trends and peak transaction periods suggest the need for time-sensitive marketing campaigns and inventory adjustments.
Location-Based Performance
Some locations outperform others significantly, revealing opportunities for replication, expansion, or operational improvement.
Payment Method Preferences
Customers show strong preferences for certain payment methods, emphasizing the need to optimize and possibly regionalize payment options.
Pricing Sensitivity
Changes in unit prices directly affect purchase quantities, indicating a price elasticity that should inform discount and pricing strategies.
Customer Segmentation Opportunities
Transaction patterns reveal distinct customer segments (e.g., bulk buyers, seasonal shoppers), which can be addressed with tailored marketing.
Operational Efficiency Indicators
Anomalies and outliers in transaction data can signal fraud, errors, or opportunities for new product insights and efficiency improvements.

Recommendations: 
Customer Loyalty and Value
→ Implement a tiered loyalty program that rewards frequent and high-spending customers with exclusive offers, early product access, or cashback incentives.
→ Use personalized marketing based on past purchases to increase retention.
Top-Performing Products and Categories
→ Prioritize inventory stocking and advertising for best-selling items.
→ Bundle popular products with slower-moving ones to boost overall sales.
Seasonality and Timing
→ Align promotional campaigns and inventory restocking with known peak seasons and holidays.
→ Launch limited-time offers or flash sales during historical high-traffic periods.
Location-Based Performance
→ Analyze top-performing locations to replicate successful tactics (e.g., layout, staffing, regional marketing) in underperforming areas.
→ Consider expansion or reinvestment in high-performing geographic areas.
Payment Method Preferences
→ Ensure seamless support for the most used payment methods, especially in mobile and online platforms.
→ Introduce region-specific payment options to reduce checkout friction.
Pricing Sensitivity
→ Test and optimize pricing with A/B testing or pilot campaigns to find the ideal price point for high-volume sales.
→ Offer volume-based discounts or subscription models for price-sensitive customers.
Customer Segmentation Opportunities
→ Use clustering or RFM analysis (Recency, Frequency, Monetary) to create detailed customer segments.
→ Deliver tailored communications and offers per segment to boost conversion rates.
Operational Efficiency Indicators
→ Investigate anomalies in data for potential fraud or process bottlenecks.
→ Automate transaction monitoring using analytics tools to flag unusual behavior in real time.
Analysis Techniques Used in Excel: 
Pivot Tables were used to analyze the data to generate meaningful visual insights.  
Other features used are
Grouping- this was used to group the ages into a range.  
Sorting- this was used to arrange data from the highest to the lowest and vice versa. 

POST-ANALYSIS AND INSIGHTS
1.	High-Value Customers Drive Disproportionate Revenue
A small segment of repeat, high-spending customers accounts for the majority of sales, suggesting strong potential for targeted loyalty initiatives.
2.	Sales Are Heavily Influenced by Product Category and Seasonality
Certain categories consistently outperform others, especially during specific time periods, underlining the importance of seasonal inventory and promotional planning.
3.	Payment Preferences Reflect Evolving Consumer Behavior
Digital payment methods are gaining dominance, and regional differences exist, requiring localized payment optimization to reduce checkout abandonment.
4.	Geographic Variability Reveals Market Potential
Significant differences in sales performance across locations point to untapped potential in certain areas and opportunities to replicate successful regional strategies elsewhere.
5.	Transactional Trends Indicate Pricing Flexibility and Sensitivity
Purchase behavior changes notably with price adjustments, highlighting the need for dynamic pricing and bundling strategies to maximize revenue.
6.	Operational Outliers Can Signal Opportunities or Risks
Unusual transaction patterns may indicate emerging trends, fraud, or system inefficiencies — all requiring monitoring for improved business agility.
7.	Segmentation Reveals Diverse Customer Behaviors
Customer behaviors are not monolithic; different groups show unique patterns in what, how often, and how much they buy — suggesting the need for more personalized engagement strategies.
8.	Strategic Alignment Between Data and Decision-Making Is Critical
The data supports evidence-based decision-making, emphasizing the need for ongoing analytics integration into marketing, operations, and product planning.

Comparison with Initial Findings: 
Customer Loyalty and Value
Initially, we identified that frequent and high-spending customers are important.
Post-analysis confirmed this, revealing that a small segment of customers contributes a disproportionately large share of total revenue. This reinforces the need for targeted loyalty and retention programs.
Top-Performing Products and Categories
The early data showed that certain items and categories dominate sales.
Deeper analysis revealed that this performance is strongly influenced by seasonality, suggesting a need for time-sensitive stock planning and targeted promotions based on category behavior.
Seasonality and Timing
It was first noted that certain periods experience higher sales.
Post-analysis tied these peaks directly to specific product types and events, enabling more precise marketing and inventory decisions aligned with predictable demand cycles.
Location-Based Performance
Initial findings indicated that some locations outperform others.
Further analysis highlighted the extent of geographic variability and revealed replicable strategies from high-performing areas that can be applied to improve weaker locations or inform expansion plans.
Payment Method Preferences
We initially observed that some payment methods were more popular than others.
Post-analysis showed that digital payments dominate overall, but with notable regional preferences, emphasizing the importance of customizing checkout experiences by location.
Pricing Sensitivity
The early observation was that pricing affects purchasing patterns.
A detailed analysis confirmed that certain categories are highly price-sensitive, and that dynamic pricing or bundling can be used effectively to influence buying behavior.
Customer Segmentation Opportunities
Early analysis suggested customers show varied behaviors.
Clustering and pattern recognition confirmed distinct segments such as bulk buyers, seasonal shoppers, and discount seekers—each requiring personalized marketing strategies.
Operational Efficiency Indicators
Initially, anomalies in transaction data were noted as potential issues or opportunities.
Deeper analysis revealed that these outliers could signal fraud, system errors, or even emerging market trends, indicating the importance of real-time anomaly detection.
Strategic Data Use
The early insight was that data could support marketing and sales decisions.
Post-analysis elevated this to a broader conclusion: integrating data across departments is essential for agile, evidence-based decision-making at all levels of the business.
DATA VISUALIZATIONS & CHARTS
SPENDING TREND
![image](https://github.com/user-attachments/assets/3093ea9f-035e-4a5a-a888-5852a229b26e)
