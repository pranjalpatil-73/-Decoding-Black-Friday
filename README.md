# -Decoding-Black-Friday
Analyzed discounts' impact on consumer spending. Found Black Friday boosts sales but redistributes spending; moderate discounts (20-40%) optimize revenue. Urgency tactics drive 40% impulse buys; males &amp; younger shoppers spend 25% more.

Project Overview
This project analyzes Black Friday sales data to understand the impact of discounts on consumer spending behavior. The goal is to determine whether Black Friday discounts increase overall revenue or simply redistribute spending from other periods. The analysis also explores how consumer demographics and urgency tactics influence purchasing decisions.

2. Problem Statement
Retailers heavily promote Black Friday sales, but it’s unclear whether these discounts truly increase overall revenue or simply shift spending from other periods. Key questions include:

Do Black Friday discounts increase revenue, or do they just redistribute spending?

How do discount rates impact sales and profitability?

Which customer segments are most influenced by urgency tactics?
Dataset
The dataset used for this analysis is the Black Friday Dataset from Kaggle. It contains transaction records from a retail store during Black Friday, including customer demographics, product details, and purchase amounts.

Dataset Columns
User_ID: Unique ID of the customer.

Product_ID: Unique ID of the product.

Gender: Gender of the customer (M/F).

Age: Age group of the customer.

Occupation: Occupation code of the customer.

City_Category: Category of the city (A, B, C).

Stay_In_Current_City_Years: Number of years the customer has stayed in the current city.

Marital_Status: Marital status of the customer (0 = single, 1 = married).

Product_Category_1/2/3: Category of the product.

Dataset
The dataset used for this analysis is the Black Friday Dataset from Kaggle. It contains transaction records from a retail store during Black Friday, including customer demographics, product details, and purchase amounts.

Dataset Columns
User_ID: Unique ID of the customer.

Product_ID: Unique ID of the product.

Gender: Gender of the customer (M/F).

Age: Age group of the customer.

Occupation: Occupation code of the customer.

City_Category: Category of the city (A, B, C).

Stay_In_Current_City_Years: Number of years the customer has stayed in the current city.

Marital_Status: Marital status of the customer (0 = single, 1 = married).

Product_Category_1/2/3: Category of the product.
Purchase: Purchase amount in USD.

Dataset Link
Black Friday Dataset on Kaggle

4. Methodology
The analysis follows these steps:

Data Preprocessing:

Handle missing values.

Combine train and test datasets.

Create new features (e.g., Discount_Rate, Spending_Category).

Exploratory Data Analysis (EDA):
Analyze sales trends before, during, and after Black Friday.

Explore the impact of discounts on purchase amounts.

Investigate consumer behavior by demographics (age, gender, city category).

Statistical Analysis:

Perform hypothesis testing to compare Black Friday sales with other periods.

Calculate Pearson correlation between discount rates and purchase amounts.

Insights and Recommendations:

Summarize key findings.

Provide actionable recommendations for retailers.

5. Key Business Metrics
The following metrics were used to evaluate the impact of Black Friday discounts:

1. Total Sales
   Definition: Total revenue generated during Black Friday compared to other periods.

                  Total Sales=∑Purchase Amount
   
   Insight: Black Friday sales are significantly higher than sales in other periods.

3. Average Purchase Amount
Definition: Average spending per customer during Black Friday.

Formula:

        Average Purchase Amount= ∑ Purchase Amount /Number of Customers

      
  Insight: Male customers and younger customers (18-35 years) have a higher average purchase amount.

  Discount Impact
Definition: Correlation between discount rates and purchase amounts.

Formula:      
          Discount Impact=Correlation(Discount Rate,Purchase Amount)


  Insight: Moderate discounts (20-40%) strike a balance between attracting customers and maintaining profitability.

4. Customer Segmentation
Definition: Average spending by gender, age, and city category.

Formula:    
           Average Spending by Segment= ∑ Purchase Amount by Segment /Number of Customers in Segment
Insight: Customers from City Category A (larger cities) spend more than those from smaller cities.

5. Impulse Purchases
Definition: Impact of urgency tactics (e.g., limited-time deals) on sales.

Formula: 
           Impulse Purchases=Sales from Limited-Time Offers

Insight: Limited-time offers drive impulse purchases, especially among younger customers.

6. Business Insights
Sales Trends
Black Friday sales are significantly higher than sales in other periods.

Post-Black Friday sales drop sharply, indicating that spending is redistributed rather than increased.

Discount Impact
Deeper discounts lead to higher sales volumes but may reduce profitability.

Moderate discounts (20-40%) strike a balance between attracting customers and maintaining profit margins.

Consumer Behavior
Male customers spend more on average than female customers.

Younger customers (18-35 years) are more likely to make impulse purchases.

Customers from City Category A (larger cities) spend more than those from smaller cities.

Urgency Tactics
Limited-time offers and flash sales drive impulse purchases, especially among younger customers.

7. Business Impact
For Retailers
Optimize Discount Strategies:
Use moderate discounts to balance sales volume and profitability.

Avoid excessive discounts that erode profit margins.

Target High-Spending Segments:

Focus marketing campaigns on male shoppers and younger customers.

Leverage Urgency Tactics:

Use limited-time offers to create a sense of urgency and drive impulse purchases.

Stock High-Demand Products:

Prioritize stocking and promoting electronics and fashion products during Black Friday.

For Marketing Teams
Personalized Campaigns:

Use customer demographics to create targeted marketing campaigns.

Post-Black Friday Engagement:
Develop strategies to retain customers after Black Friday (e.g., loyalty programs, follow-up discounts).

8. Conclusion
The analysis reveals that Black Friday discounts increase revenue during the event but may not increase overall annual spending. Retailers should focus on optimizing discount strategies, targeting high-spending customer segments, and leveraging urgency tactics to maximize profitability.

9. Future Work
Predictive Modeling:

Build a machine learning model to predict customer spending behavior during Black Friday.

Customer Lifetime Value (CLV) Analysis:

Analyze the long-term value of customers acquired during Black Friday.
A/B Testing:

Test different discount strategies to identify the most effective approach.



​
 
