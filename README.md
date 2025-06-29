# PROJECT TOPIC - AMAZON-PRODUCT-REVIEW-ANALYSIS

##	Project Overview
This project focuses on analyzing product and customer review data to generate insights that can guide product improvement, marketing strategies and customer engagement. The analysis was conducted using Microsoft excel, with a focus on building an interactive dashboard for business decision making.

### Data source
The primary source of data used in this project is Amazon casy study file and which was gotten from Incubator Hub using Amazon real life data.
### Tools used
- Microsoft excels
  - Data cleaning or wrangling
  - Calculated columns
  - Pivot tables
  - Data visualization (chart, slicers)
### Data preparation
The row data cleaned to ensure analysis readiness. Key step included:
-	Removing duplicate to avoid repeated records
-	Replacing blank cells with 0
-	Making sure numbers, text and percentage follows a consistent format
-	Removing irrelevant columns such as about_product, user_id, user_name, review_id, review_title,img_link,product_link
-	Splitting the product_category column and create new column as Main category for better readability
-	Shortening overly long product_names and create new columns for simplicity in visualization
-	Addition of calculated columns such as potential revenue, price bucket, combined score, rating below 1000
### Key Metrics Analyzed
-	Average discount percentage
-	Product count per category
-	Total review per category
-	Average actual and discounted price by category
-	Distribution of product rating
-	Total potential revenue by category
-	No of unique product per price range
-	Category product with the highest discount
-	Product with highest average rating
-	Product with the highest number of review
-	Total number of product with 50% discount or more
-	Top 5 in combination of rating and rating count
