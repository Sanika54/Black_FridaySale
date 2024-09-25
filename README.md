# Black_FridaySale
Overview
This project focuses on predicting Black Friday sales using various regression machine learning
algorithms. The goal is to assist retail stores and eCommerce businesses in determining optimal
product prices based on historical sales data to maximize profits.
Dataset Description
• Source: Sourced from an Analytics Vidhya hackathon.
• Features: Includes age, gender, marital status, product categories, city demographics, and
purchase amounts.
• Records: Over 537,000 entries.
Exploratory Data Analysis (EDA)
• Demographics: Approximately 75% of purchases were made by male consumers, with single
men spending the most.
• Age Insights: Consumers aged 25-40 had the highest spending.
• City Insights: City B contributed the most to overall sales, while City C had higher purchases
of the analyzed product.
Data Preparation
• Encoding: Categorical columns (Age, Gender, City Category) were encoded using Label
Encoder.
• Missing Values: Missing entries in Product_Category_2 and Product_Category_3 were filled.
Modeling Phase
• Data Split: The dataset was divided into training (80%) and test (20%) sets.
• Models Implemented:
• Linear Regressor
• Decision Tree Regressor
• Random Forest Regressor
• XGBoost Regressor
Evaluation Metric
• Metric Used: Root Mean Square Error (RMSE).
• Best Performance: XGBoost Regressor achieved the best results with an RMSE score of 2879.
Conclusion
The XGBoost Regressor outperformed all other models, providing the most accurate
predictions for Black Friday sales, demonstrating its effectiveness in retail price optimization.
