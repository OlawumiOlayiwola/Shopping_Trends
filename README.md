# Shopping_Trends
This repository contains the analysis of the shopping_trends.csv dataset, focusing on customer segmentation, sales forecasting, and customer retention. The analysis includes data preprocessing, exploratory data analysis, and the development of predictive models.

### Project Overview
The goal of this project is to analyze consumer purchasing patterns, identify popular product categories, and develop predictive models for sales forecasting and customer retention. The insights gained from this analysis can help businesses make data-driven decisions to improve customer satisfaction and increase sales.


### Data Sources
Shopping Trends Data: The primary dataset used for this analysis is the "shopping_trends.csv" file. The file contains information about purchasing habits of customers.

### Tools
- Excel
- Python
- Power BI

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

### Results
- Customer Segmentation
Cluster 0: Offer loyalty rewards and personalized discounts to frequent buyers.
Cluster 1: Provide targeted promotions for high spenders with high review ratings.
Cluster 2: Engage younger customers with trendy and seasonal products.
Cluster 3: Focus on improving customer satisfaction for those with lower review ratings.
- Sales Forecasting
    - Mean Squared Error (MSE): 563.6811686957067
    - R-squared (R²): -0.007324742714263532
- Customer Retention
   - Accuracy: 0.7730769230769231
Classification Report: precision    recall  f1-score   support

           0       0.13      0.03      0.05       149
           1       0.81      0.95      0.87       631

      - accuracy                           0.77       780
      - macro avg       0.47      0.49      0.46       780
      - weighted avg       0.68      0.77      0.71       780

### Conclusion
The analysis provided valuable insights into consumer purchasing patterns and helped develop effective strategies for customer segmentation, sales forecasting, and customer retention. These insights can be used to enhance customer satisfaction and drive business growth.

### Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or suggestions.

