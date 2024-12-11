# A5_1_CustomorCoupon
This repository contains a data analysis project exploring customer behavior regarding driving coupons. The dataset is analyzed and visualized to identify differences between customers who accepted or rejected coupons under various conditions. The results include actionable insights for marketing.

# link to the jupyter notebook
https://github.com/Sara-Oberg/A5_1_CustomerCoupon/blob/main/prompt_mywork_09Dec2024_v2.ipynb

# Data Description
The dataset contains the following information:
Customer Demographics: Age, gender, marital status, income, education level, etc.
Driving Context: Destination, weather, passenger type, time of day, etc.

# Coupon Details 
Bars
Coffee Houses
Restaurants (less than $20)
Restaurants ($20–$50)
Carryout and takeaway
Response to Coupons:
Y = 1: Accepted the coupon.
Y = 0: Did not accept the coupon.

# Objectives
In this task, the characteristics of customers who accept coupons have been identified.

# Findings
The dataset has 6 columns with missing data: car, Bar, CoffeeHouse, CarryAway, RestaurantLessThan20 and Restaurant20To50, where the column 'car' has the most missing data 99.1%

Frequent bar-goers (>3 visits/month) are more likely to accept bar coupons on an individual basis (higher acceptance rate within their group). However, the majority of total coupon acceptances come from less frequent bar-goers (<=3 visits/month), likely due to their larger representation in the population.

Older and more frequent bar-goers (Group 1) are more likely to accept bar-related coupons compared to the younger and less frequent visitors (Group 2).

The drivers with lower incomes (< $50K) has higher acceptance rate. It might be they accepted coupons as an opportunity for cost savings, potentially making them more receptive to bar coupons.

The drivers without children have a higher tendency to accept coupons.
This can help the targeted coupon strategies, to offer coupons for those without children

#Visualizations
The analysis includes several visualizations using pie, bar and histogram.
