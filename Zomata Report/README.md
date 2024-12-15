# Power BI Project: Zomato Sales Analysis

![zomato_banner](https://github.com/user-attachments/assets/e785f64d-1721-4e01-bfae-7c884445e1fd)

## Business Problem Statement

The goal of this project is to explore the **Zomato** Restaurants dataset to gain meaningful insights into the dynamics of the food delivery industry. Specifically, we aim to identify the key factors that contribute to a restaurant's success, including elements like customer ratings, review counts, and cuisine styles. Through an analysis of customer sentiments reflected in reviews, we aim to understand the appeal of different types of restaurants, focusing on both order volume and the sentiment polarity of feedback. Ultimately, this project seeks to provide restaurant owners and managers with actionable recommendations for enhancing their establishment's performance and elevating customer satisfaction.

## Overview of Dataset:

1. **Food Item Categorization:** Analyze food and veg/non-veg status.
2. **Cuisine Variety:** Explore menu cuisine diversity.
3. **Sales Trends:** Investigate order patterns over time.
4. **Restaurant Distribution:** Assess restaurant presence globally.
5. **Demographic Analysis:** Explore user age, gender, marital status.
6. **Cuisine Popularity:** Identify trending cuisines across regions.
7. **Revenue Metrics:** Track sales performance indicators.
8. **Customer Satisfaction:** Analyze reviews and ratings.
9. **Geographic Insights:** Visualize sales distribution across regions.
10. **User Engagement:** Measure user interaction frequency.
11. **Competitive Benchmarking:** Compare against industry rivals.
12. **Growth Recommendations:** Offer actionable growth strategies.

## Key Measures

The following measures were created to drive insights in the dashboard:

- ActiveUsers
- CurrentYear
- CurrentYrSale
- Dynamic_Title
- GainCustomers
- LostCustomers
- Order_count
- PreviousYear
- PreviousYrSale
- Rating_Count
- Sales
- Subheading
- Top_N_Sales
- UserCount

## Data Transformation in Power Query

Data transformations were performed to clean and prepare the data before visualization. These included:

- Merging datasets for comprehensive insights.
- Creating calculated columns for better categorization.
- Filtering irrelevant data to enhance performance.

## Dashboard Overview

The dashboard contains the following visual pages:

> **Overview Page**

- Displays total quantity, sales, ratings, and order count.
- Breakdown of food items by category: Veg, Non-Veg, and Other.
- Visualizes top-performing cities by sales and a trendline of yearly sales growth.

> **User Performance Page**

- Overview of total users, active users, and orders placed.
- Insights into gained and lost customers with gender distribution.
- User distribution by age group.

> **City Analysis Page**

- Detailed city-wise analysis of sales, orders, gained and lost customers.
- Comparison of cities based on ratings and active users.

Check out the [Dashboard](https://app.powerbi.com/groups/me/reports/e840bbc7-0c90-447e-905d-47a2d15620ee/4803e64546390c546c50?experience=power-bi) 📊

## Key Insights

I processed the data and removed the NULL values from the sentiment column and removed the incorrect values in the Category column and NULL from the Rating column.

1. Zomato serves in 150,281 locations and collaborates with 77,929 restaurants, handling 150,281 orders.
2. Food data includes unique IDs, item names, and vegetarian/non-vegetarian indications.
3. Menu data comprises IDs, restaurant links, cuisine types, and item prices.
4. Orders detail dates, quantities, sales amounts, currencies, and user and restaurant IDs.
5. Restaurant information encompasses IDs, names, locations, ratings, cuisine types, and addresses.
6. User data contains IDs, names, ages, genders, marital statuses, and occupations.
