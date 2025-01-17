# Customer Lifetime Value (CLV) 

## 1. Introduction:
The business world has seen a major shift, with companies placing an increasing emphasis on their customers. In today’s competitive market, a customer-focused strategy has become the norm, driven by the abundance of choices available to consumers when choosing products or services.

As businesses compete by better meeting customer needs and expanding their market
presence, the value of growing and retaining their customer base becomes crucial.

However, like attracting new customers, keeping existing ones also involves significant expenses (such as discounts, personalized offers, etc.).

This leads to an important question: should businesses aim to retain every customer? Not necessarily. In every business, certain customers offer more value through their long-term loyalty, while others may only make a single purchase. Recognizing these different customer groups and concentrating on the high-value ones is critical for sustaining a position in today’s highly competitive environment.

The real challenge, however, is identifying which customers are the most valuable.

**What is Customer Value?**

Customer Value, often called Customer Lifetime Value (CLV), represents the total financial worth of all transactions a customer makes with your business during their entire relationship. "Lifetime" refers to the period a customer continues to purchase from your business before moving to a competitor.

## 2. Project Details

This project focuses on estimating Customer Lifetime Value (CLV) using a dataset of online retail transactions. The dataset includes information on customer demographics, transaction history, and product details. The goal is to gain a deep understanding of customer behavior, identify high-value customers, and develop strategies to maximize CLV.
Furthermore, this project is divided into three parts:

1. Exploratory Data Analysis (EDA)
2. Methodologies that are used to calculate and predict Customer Lifetime Value (CLV)
   - Aggregate model
   - Cohort model
   - BG/NBD Model (Beta Geometric/Negative Binomial Distribution)
   - Gamma-Gamma Model for predicting CLV.
3. Machine Learning Regression models for prediction
   - Linear Regression
   - Lasso Regression
   - Ridge Regression
   - K-Neighbors Regressor
   - Decision Tree Regressor
   - Random Forest Regressor
   - XGBRegressor
   - CatBoosting Regressor
   - AdaBoost Regressor
  
## 3. Key Insights:

#### 1. Top 10 most purchased products based on 'Description'

![image](https://github.com/user-attachments/assets/c0f7b039-42d1-4400-a8f8-1033a5b4f53a)

**Specific Insights:**

- Home Decor: The top three products all have a home decor theme, suggesting a strong demand for decorative items.
- Party Supplies: Products like "PARTY BUNTING" and "PACK OF 72 RETROSPOT CAKE CASES" indicate popularity for festive occasions and celebrations.
- Everyday Essentials: Items like "LUNCH BAG RED RETROSPOT" and "LUNCH BAG BLACK SKULL" highlight the need for practical, everyday products.
- Retro Trend: The presence of "RETROSPOT" in multiple products suggests a current trend or preference for retro-inspired designs.
- Postage: The inclusion of "POSTAGE" as a top-purchased item might indicate a high volume of online orders or a significant portion of the business being rall business performance.

#### 2. Top 10 Products by Total Sales

![image](https://github.com/user-attachments/assets/c7e5c1bf-6e67-421a-976c-ae08889d2a7f)

**Specific Insights:**

- Paper Crafts: The top-selling product, "PAPER CRAFT, LITTLE BIRDIE," suggests a strong demand for creative and DIY activities.
- Home Decor: Products like "WHITE HANGING HEART T-LIGHT HOLDER" and "REGENCY CAKESTAND 3 TIER" continue to be popular, indicating a consistent demand for decorative items.
- Everyday Essentials: Items like "MEDIUM CERAMIC TOP STORAGE JAR" and "POSTAGE" highlight the need for practical, everyday products.
- Novelty Items: Products like "RABBIT NIGHT LIGHT" show a demand for unique and whimsical items.
- Seasonal Trends: While not explicitly shown in the chart, it's possible that some products have seasonal variations in sales (e.g., party bunting ferall business performance.

#### 3. Top 5 Countries by Total Sales Value

![image](https://github.com/user-attachments/assets/8b46665d-d6b6-4fda-affa-6052994b5821)

**Specific Insights:**

- Market Dominance: The United Kingdom clearly dominates the market, accounting for 88.1% of total sales.
- Smaller Markets: The remaining four countries (Netherlands, EIRE(Republic of Ireland), Germany, and France) collectively represent 11.9% of total sales, indicating a more concentrated market.
- Domestic Market: The significant share of the United Kingdom suggests a strong domestic market or a successful export strategy targeting UK consumers.
- European Markets: The presence of neighboring European countries (Netherlands, EIRE, Germany, and France) indicates potential for cross-border sales and expansion.
- Market Penetration: The relatively small market shares of the other countries suggest opportunities for increased market penetration and growth in those regions.

#### 4. Which hour of the day, day of the week is when most transactions happen?

![image](https://github.com/user-attachments/assets/87b3ca0a-5948-4d7d-83bc-545a61947a29)

**Specific Insights:**

- The transaction on the website starts to increase around 7 in the morning and peaks at noon. Then the trend slowly decreases and ends at 6 PM.
- People tend to purchase more from Monday to Thursday. Surprisingly, there are no transactions that took place on Saturdays for the given period in the data.

#### 5. The trend of transactions for the given period?

![image](https://github.com/user-attachments/assets/6dbecf5c-17d7-417c-abfb-c5873a57de45)

**Specific Insights**

- The monthly trend reveals that the number of people using the platform is showing an increasing trend. Further, the rate of increase stayed flat till August 2011 and rapidly increasing from September 2011.
- Seasonality: The chart suggests some seasonality in transactions, with potential peaks and troughs at certain times of the year.
- Growth Period: The period from 2010-12 to 2011-11 experienced steady growth in transactions, indicating a positive trend in business activity.
- Sharp Decline: The sudden drop in transactions in 2011-12 is a significant outlier and may warrant further investigation to understand the underlying causes.

#### 6. Distribution of customers by total revenue and number of orders

![image](https://github.com/user-attachments/assets/387447aa-1ae3-47ef-9755-c0543065a8ee)

**Insights from the Scatter Plot**

- Positive Correlation: You might observe a positive correlation where customers who purchase more (higher total quantity) also tend to generate higher total revenue.
- Outliers: A few data points, particularly on the higher end of both axes, seem to be outliers, indicating that some customers purchase significantly larger quantities or spend significantly more than the general trend.
- Customer Segmentation: The scatter plot might reveal different customer segments based on their purchasing behavior. For example, customers who consistently purchase larger quantities and spend more could be identified as high-value customers.
- Outlier Analysis: Analyzing the outliers could provide insights into factors that influence exceptional spending behavior. These could include specific product categories, promotions, or customer characteristics, such as customer satisfaction.
- Correlation: The analysis indicates a correlation between total revenue and the number of orders per customer.

#### 7. Revenue contribution by different customer segments (e.g., high-value vs. low-value customers)

![image](https://github.com/user-attachments/assets/bb015b06-eb8d-48bf-ae37-7f431563f0a7)

**Insights:**

- High-Value Customers: The "Very High Value" segment has the highest median total sales, indicating that customers in this segment generally spend more than those in other segments. The presence of outliers further highlights the existence of extremely high-spending customers within this segment.
- Outlier Analysis: The outliers in the "Very High Value" segment highlight the potential for significant revenue contributions from a small number of high-spending customers.

![image](https://github.com/user-attachments/assets/569f31e2-1a68-44cb-a325-3185398e0fb9)

**Insights:**

- Increasing Average Sales: As customer segments move from "Low Value" to "Very High Value," the average total sales increase significantly.
- Large Difference: The difference in average sales between the "Very High Value" and "Low Value" segments is substantial, indicating a wide range of spending patterns.
- High-Value Customers: The "Very High Value" segment has the highest average total sales, confirming their superior spending power.
- Low-Value Customers: The "Low Value" segment has the lowest average total sales, suggesting a need to focus on increasing their spending.
- Segmentation Effectiveness: The clear differences in average sales across segments demonstrate the effectiveness of customer segmentation in identifying high-value customers.

#### 8. Are there any seasonal patterns in sales or customer activity?

![image](https://github.com/user-attachments/assets/265027db-048d-480b-a68d-3b4c6ab1ccc2)

**Insights:**

- Seasonal Patterns: The heatmap reveals distinct seasonal patterns in sales, with certain months and days of the week consistently showing higher or lower sales volumes.
- Day of the Week Variations: There are clear differences in sales performance across different days of the week, indicating that certain days are more or less conducive to sales.
- Peak Months: Identify the months with the highest overall sales volumes, suggesting that these periods might be ideal for promotions or increased marketing efforts.
- Peak Days: Determine the days of the week with the highest sales, providing insights into when customers are most likely to make purchases.
- Seasonal Trends: Analyze the seasonal patterns to understand how external factors like holidays, weather, or events might influence sales.
- Day-to-Day Fluctuations: Examine the variations in sales across different days of the week to identify potential trends or anomalies.

## 4. Methodologies that are used to calculate and predict Customer Lifetime Value (CLV)

#### 1). Aggregate Model:

The simplest and oldest method for calculating CLV is the Aggregate or Average method. This approach assumes that all customers have a constant average spend and churn rate. It doesn't distinguish between individual customers, producing a single CLV value at an overall level. However, this can result in unrealistic estimates, especially if some customers make high-value or high-volume transactions, which can skew the average CLV.

The Customer Lifetime Value (CLV) for each customer is: $471044.11

Our initial model calculated a CLV of $471K per customer, which is unrealistic. This result is heavily skewed due to a few customers with extremely high sales, inflating the overall figure. Additionally, it's important to note that not all customers behave the same way.

#### 2). Cohort Model

Rather than treating all customers as a single group, we can divide them into multiple groups and calculate CLV for each one. This approach addresses the key limitation of the simple Aggregate model, which assumes all customers are the same. This method is known as the Cohort model.

The key assumption here is that customers within the same cohort have similar spending habits or overall behavior.
A common approach to grouping customers into cohorts is by their start date, usually on a monthly basis. The ideal grouping method depends on factors like the customer acquisition rate, business seasonality, and available customer data.
In this case, I am organizing customers into cohorts based on their start month, resulting in 12 customer cohorts (January to December).

![image](https://github.com/user-attachments/assets/adf26dae-072c-42ae-b9c9-519e2c3b8167)

Upon examining the results, we observe 12 distinct CLV values corresponding to each month from January to December. It is evident that customers acquired in different months have varying CLV values. This variation can be attributed to differences in acquisition campaigns and other factors that may influence customer behavior.

Specifically, the CLV values for January and December are notably high. The data pertains to an online retailer that sells gifts to wholesalers and companies, and both Christmas and New Year occur during these months. This seasonal context explains the elevated CLV for customers who started their transactions in January and December.

#### 3). BG/NBD Model (with Gamma-Gamma extension)

BG/NBD refers to the Beta Geometric/Negative Binomial Distribution.
This model is one of the most widely used probabilistic methods for predicting Customer Lifetime Value (CLV). The BG/NBD aims to forecast the future transactions of individual customers.

This approach is then integrated with the Gamma-Gamma model, which incorporates the monetary value of customer transactions, ultimately allowing us to calculate the Customer Lifetime Value (CLV).
The model essentially fits the distribution to historical data, learning the distribution parameters, which are then used to predict future customer transactions.

#### 4). Gamma-Gamma Model

The Gamma-Gamma model is employed in Customer Lifetime Value (CLV) prediction to estimate the monetary value of customer transactions over time. It operates under several important assumptions that simplify the modeling process, though these assumptions must be understood clearly.

- The value of a customer’s transaction fluctuates randomly around their average transaction value.
- While average transaction values differ between customers, they remain consistent over time for any individual customer.
- The distribution of average transaction values across customers is independent of their transaction frequency.

#### 5). Regression Models:

After performing feature engineering, scaling, and encoding, several machine-learning regression algorithms were applied. 

1. Linear Regression
2. Lasso Regression
3. Ridge Regression
4. K-Neighbors Regressor
5. Decision Tree Regressor
6. Random Forest Regressor
7. XGBRegressor 
8. CatBoosting Regressor
9. AdaBoost Regressor

Out of which top 3 models were selected:
1. Decision Tree Regressor
2. Random Forest Regressor
3. CatBoosting Regressor

Decision Tree Regressor and Random Forest Regressor were the top-performing models.

## 5. Recommendations

* **Stock Management:** Prioritize stocking the top-selling products to avoid stockouts and maximize sales.
* **Product Development:** Consider expanding the range of home decor and party supplies to capitalize on their popularity.
* **Marketing:** Focus marketing efforts on the top-selling products and explore opportunities to promote the "RETROSPOT" trend.
* **Customer Analysis:** Analyze customer demographics and preferences associated with the top-selling products to tailor future offerings.

* **International Expansion:** If the goal is to increase revenue, consider expanding into the smaller markets to capture a larger share.
* **Market Research:** Conduct in-depth market research in the smaller countries to identify specific customer needs and preferences.
* **Localization:** Adapt products or marketing strategies to cater to local cultural preferences and regulations.
* **Partnerships:** Explore partnerships with local distributors or retailers to enhance market presence.

* **Investigate Decline:** It's crucial to understand the reasons behind the significant drop in transactions in 2011-12. This could involve analyzing external factors (e.g., economic conditions, competition) or internal issues (e.g., product issues, marketing campaigns).
* **Seasonal Planning:** If there's a discernible seasonal pattern, the business can plan accordingly to optimize resources and promotions during peak periods.

* **Targeted Marketing:** Identify high-value customers and tailor marketing campaigns and promotions to their preferences to encourage repeat purchases.
* **Product Bundling:** Explore opportunities to bundle products to increase average order value and encourage customers to buy more.
* **Customer Loyalty Programs:** Implement loyalty programs to reward repeat customers and encourage them to spend more.
* **Inventory Management:** Use the correlation between quantity and sales to optimize inventory levels and avoid stockouts or excess inventory.

* **Customer Segmentation:** Implement strategies to identify and target customers within each segment based on their spending patterns.

* **Product Recommendations:** Use customer data to personalize product recommendations and offer tailored promotions.
* **Outlier Analysis:** Analyze the characteristics of outliers to understand factors that influence exceptional spending behavior and identify potential upselling opportunities.
* **Upselling and Cross-Selling:** Explore opportunities to upsell and cross-sell products to customers in the lower-value segments to increase their average spending.
    
**Additional Questions:**
* **Customer Feedback:** What do customers say about these products?
* **Competitive Analysis:** How do these products compare to competitors' offerings?
* **Pricing Strategy:** Is there an opportunity to adjust pricing for certain products to optimize sales?

* **Customer Demographics:** What are the demographics of customers in each country?
* **Competitive Landscape:** What is the competitive landscape in each country?
* **Economic Factors:** How do economic factors (e.g., GDP, consumer spending) influence sales in each country?

* **External Factors:** Were there any significant external events (e.g., economic crises, industry disruptions) that could have impacted transactions?
* **Marketing Campaigns:** Were there any changes in marketing strategies or campaigns during this period?
* **Customer Feedback:** Was there any feedback from customers indicating dissatisfaction or issues that might have led to decreased transactions?

* **Customer Demographics:** Are there any demographic differences between customers who purchase larger quantities or spend more?
* **Product Categories:** Are there specific product categories that drive higher sales or larger quantities?
* **Customer Lifetime Value:** How does the relationship between quantity and sales impact customer lifetime value?

By carefully analyzing these insights and considering additional factors, businesses can make informed decisions to optimize their marketing strategies, customer loyalty programs, and product offerings to maximize revenue from different customer segments.
