# Car Price Prediction using Python
# ![images](https://github.com/user-attachments/assets/db256efe-f6ee-41cb-82eb-f93722214ba1)

# Project Description :-
 This project focuses on developing a machine learning model to predict car prices accurately and reliably. The model will leverage a dataset containing key features such as the car's name, manufacturer, year of manufacture, kilometers driven, and fuel type. By preprocessing the data, selecting appropriate features, and applying advanced machine learning algorithms, the project aims to deliver a tool that can generate precise price predictions. The outcomes will assist individuals and businesses in the car resale market by providing data-driven insights for valuation and informed decision-making processes.
 
# Problem Statement :-
The aim of the project is to create an effective and reliable machine learning model that can predict car prices using key features such as the car's name, manufacturer, year of manufacture, kilometers driven, and fuel type. This model will provide accurate price estimates to assist in car valuation and decision-making processes.

#Data Cleaning Process
The dataset was cleaned to ensure consistency and suitability for predicting car prices. Key steps include:

'name' Column: Extracted the first three words from car names to standardize the format.
'year' Column: Converted to integers after filtering out non-numeric values.
'Price' Column: Removed 'Ask For Price' entries, cleaned commas, and converted to integers.
'kms_driven' Column: Extracted numeric values, removed non-numeric entries, and converted to integers.
'fuel_type' Column: Dropped rows with missing values.
The final dataset has 730 entries with no missing or incorrect data, ready for modeling. The cleaned data was exported as cleaned_data.csv.

# Key Findings:
Linear Regression provided the highest R-squared score (0.56), indicating the best fit for the data among the models tested.
Ridge Regression and Lasso Regression had lower R-squared scores, suggesting that they did not perform as well on this dataset.
Thus, based on the Linear Regression model's superior R-squared score, we concluded that it provides the most accurate predictions for the car price dataset and is the most suitable model for our analysis.

