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

### 1. Top 10 most purchased products based on 'Description'

![image](https://github.com/user-attachments/assets/c0f7b039-42d1-4400-a8f8-1033a5b4f53a)

**Specific Insights:**

- Home Decor: The top three products all have a home decor theme, suggesting a strong demand for decorative items.
- Party Supplies: Products like "PARTY BUNTING" and "PACK OF 72 RETROSPOT CAKE CASES" indicate popularity for festive occasions and celebrations.
- Everyday Essentials: Items like "LUNCH BAG RED RETROSPOT" and "LUNCH BAG BLACK SKULL" highlight the need for practical, everyday products.
- Retro Trend: The presence of "RETROSPOT" in multiple products suggests a current trend or preference for retro-inspired designs.
- Postage: The inclusion of "POSTAGE" as a top-purchased item might indicate a high volume of online orders or a significant portion of the business being rall business performance.

### 2. Top 10 Products by Total Sales

![image](https://github.com/user-attachments/assets/c7e5c1bf-6e67-421a-976c-ae08889d2a7f)

**Specific Insights:**

- Paper Crafts: The top-selling product, "PAPER CRAFT, LITTLE BIRDIE," suggests a strong demand for creative and DIY activities.
- Home Decor: Products like "WHITE HANGING HEART T-LIGHT HOLDER" and "REGENCY CAKESTAND 3 TIER" continue to be popular, indicating a consistent demand for decorative items.
- Everyday Essentials: Items like "MEDIUM CERAMIC TOP STORAGE JAR" and "POSTAGE" highlight the need for practical, everyday products.
- Novelty Items: Products like "RABBIT NIGHT LIGHT" show a demand for unique and whimsical items.
- Seasonal Trends: While not explicitly shown in the chart, it's possible that some products have seasonal variations in sales (e.g., party bunting ferall business performance.

### 3. Top 5 Countries by Total Sales Value

![image](https://github.com/user-attachments/assets/8b46665d-d6b6-4fda-affa-6052994b5821)

**Specific Insights:**

- Market Dominance: The United Kingdom clearly dominates the market, accounting for 88.1% of total sales.
- Smaller Markets: The remaining four countries (Netherlands, EIRE(Republic of Ireland), Germany, and France) collectively represent 11.9% of total sales, indicating a more concentrated market.
- Domestic Market: The significant share of the United Kingdom suggests a strong domestic market or a successful export strategy targeting UK consumers.
- European Markets: The presence of neighboring European countries (Netherlands, EIRE, Germany, and France) indicates potential for cross-border sales and expansion.
- Market Penetration: The relatively small market shares of the other countries suggest opportunities for increased market penetration and growth in those regions.

### 4. Which hour of the day, day of the week is when most transactions happen?

![image](https://github.com/user-attachments/assets/87b3ca0a-5948-4d7d-83bc-545a61947a29)

**Specific Insights:**

- The transaction on the website starts to increase around 7 in the morning and peaks at noon. Then the trend slowly decreases and ends at 6 PM.
- People tend to purchase more from Monday to Thursday. Surprisingly, there are no transactions that took place on Saturdays for the given period in the data.

### 5. The trend of transactions for the given period?

![image](https://github.com/user-attachments/assets/6dbecf5c-17d7-417c-abfb-c5873a57de45)

**Specific Insights**

- The monthly trend reveals that the number of people using the platform is showing an increasing trend. Further, the rate of increase stayed flat till August 2011 and rapidly increasing from September 2011.
- Seasonality: The chart suggests some seasonality in transactions, with potential peaks and troughs at certain times of the year.
- Growth Period: The period from 2010-12 to 2011-11 experienced steady growth in transactions, indicating a positive trend in business activity.
- Sharp Decline: The sudden drop in transactions in 2011-12 is a significant outlier and may warrant further investigation to understand the underlying causes.

### 6. Distribution of customers by total revenue and number of orders

![image](https://github.com/user-attachments/assets/387447aa-1ae3-47ef-9755-c0543065a8ee)

**Insights from the Scatter Plot**

- Positive Correlation: You might observe a positive correlation where customers who purchase more (higher total quantity) also tend to generate higher total revenue.
- Outliers: A few data points, particularly on the higher end of both axes, seem to be outliers, indicating that some customers purchase significantly larger quantities or spend significantly more than the general trend.
- Customer Segmentation: The scatter plot might reveal different customer segments based on their purchasing behavior. For example, customers who consistently purchase larger quantities and spend more could be identified as high-value customers.
- Outlier Analysis: Analyzing the outliers could provide insights into factors that influence exceptional spending behavior. These could include specific product categories, promotions, or customer characteristics, such as customer satisfaction.
- Correlation: The analysis indicates a correlation between total revenue and the number of orders per customer.
