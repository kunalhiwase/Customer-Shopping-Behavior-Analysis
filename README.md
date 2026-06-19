# Customer Shopping Behavior Analysis

## Overview

This project analyzes retail customer transaction data to understand purchasing patterns, customer segments, product performance, and factors affecting customer retention.

The analysis converts raw customer data into business insights that can support decisions related to marketing strategy, customer engagement, and product planning.

## Tech Stack

- Excel Power Query - Data cleaning and transformation
- MySQL - Data analysis and querying
- Power BI - Dashboard development and visualization

## Dataset

The dataset contains 3,900 customer purchase records with 18 attributes covering:

- Customer demographics
- Purchase details
- Product categories
- Subscription information
- Discounts and promotions
- Customer reviews
- Purchase frequency

## Workflow

Raw Data  
↓  
Excel Power Query (Data Preparation)  
↓  
MySQL (Business Analysis)  
↓  
Power BI (Dashboard & Insights)


## Data Preparation

The dataset was cleaned and transformed using Excel Power Query before analysis.

Major steps included:

- Data quality validation
- Missing value treatment
- Data type corrections
- Column standardization
- Feature creation for analysis

Additional features created:

- Age Group
- Purchase Frequency Days
- Customer Segment


## SQL Analysis

MySQL was used to answer key business questions:

1. Revenue comparison between male and female customers

2. Identification of high-value customers using discounts

3. Top products based on customer review ratings

4. Purchase behavior comparison across shipping methods

5. Impact of subscription status on spending

6. Products with higher discount dependency

7. Customer segmentation based on purchase history

8. Top-performing products within each category

9. Relationship between repeat purchases and subscriptions

10. Revenue contribution across age groups


## Dashboard

A Power BI dashboard was created to present the analysis results.

The dashboard tracks:

- Total Customers
- Average Purchase Amount
- Average Review Rating
- Revenue by Category
- Customer Segments
- Subscription Distribution
- Sales Trends


## Key Insights

- Customer segments showed different spending behaviors and revenue contributions.
- Certain products had stronger dependency on discounts.
- Purchase history helped identify loyal and repeat customers.
- Product ratings and category performance provided opportunities for targeted promotions.
- Customer demographics helped identify valuable customer groups.


## Repository Structure

```
Customer-Shopping-Behavior-Analysis

├── Dataset
├── Excel Files
├── SQL Queries
├── Power BI Dashboard
├── Reports
└── README.md
```

## Conclusion

The project demonstrates an end-to-end analytics process from data preparation to business reporting. The final dashboard and analysis provide insights that can help improve customer targeting, promotional strategies, and customer retention.
