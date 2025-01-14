# Shopping_Trends
This repository contains the analysis of the shopping_trends.csv dataset, focusing on customer segmentation, sales forecasting, and customer retention. The analysis includes data preprocessing, exploratory data analysis, and the development of predictive models.

## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning/Preparation](data-cleaning-preparation)
- [Data Analysis](#data-analysis)
- [Insights](#insights)
- [Results](#results)
- [Limitations](#limitations)
- [Conclusion](#conclusion)
- [Contributions](#contributions)


### Project Overview
This project aims to analyze consumer purchasing patterns, identify popular product categories, and develop predictive models for sales forecasting and customer retention. The insights gained from this analysis can help businesses make data-driven decisions to improve customer satisfaction and increase sales.


### Data Sources
Shopping Trends Data: The primary dataset used for this analysis is the "shopping_trends.csv" file. The file contains information about customers' purchasing habits.

### Tools
- Excel
- Python

### Data Cleaning/Preparation
In the preparation stage, I performed the following tasks:
1. Data inspection.
2. Handling missing values.
3. Data formatting.

### Data Analysis
- Customer Segmentation was performed using KMeans clustering. The optimal number of clusters was determined using the elbow method. The clusters were analyzed to understand the characteristics of each segment, and personalization strategies were developed based on the cluster analysis.
- Sales Forecasting:
A linear regression model was developed to predict the purchase amount based on features such as age, previous purchases, review rating, and frequency of purchases. The model was evaluated using Mean Squared Error (MSE) and R-squared (R²) metrics.
- Customer Retention:
A random forest classifier model was developed to predict customer retention based on features such as age, review rating, purchase amount, and frequency of purchases. Retention was defined as having more than 10 previous purchases. The model was evaluated using accuracy and classification report metrics.

### Insights
- Sales Forecasting: The forecasted values suggest that the total purchase amount will fluctuate over the next 12 months, with some months showing higher spending than others.
- Customer Retention: The Random Forest Classifier achieved an accuracy of 57%. The model's precision and recall indicate that it performs better at identifying customers who are not retained (rating < 4) compared to those who are retained (rating >= 4).


### Results
    
Predictive Analysis
- Sales Forecasting: Exponential Smoothing method forecasts the total purchase amount for the next 12 months.
- Customer Retention: A random forest classifier predicts customer retention based on review ratings.
- Customer Segmentation and Personalization Strategies
    - Customer Segmentation: KMeans clustering segments customers based on age, purchase amount, review rating, and previous purchases.
    - Personalization Strategies:
         - Cluster 0: Offer loyalty rewards and personalized discounts to retain high-value customers.
         - Cluster 1: Provide targeted promotions and incentives to encourage more frequent purchases.
         - Cluster 2: Improve product quality and customer service to enhance satisfaction.
         - Cluster 3: Engage with customers through personalized recommendations and exclusive offers.

### Limitations

The dataset does not include actual purchase dates. For analysis purposes, random purchase dates were generated. This limits the ability to perform accurate time series analysis and understand trends over specific periods.

### Conclusion
The analysis provided valuable insights into consumer purchasing patterns and helped develop effective strategies for customer segmentation, sales forecasting, and customer retention. These insights can be used to enhance customer satisfaction and drive business growth.

### Contributions
Contributions are welcome! Please open an issue or submit a pull request for improvements or suggestions.

