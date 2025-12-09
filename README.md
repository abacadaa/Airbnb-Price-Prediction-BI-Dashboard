# Airbnb Price Prediction \& BI Dashboard



A full Machine Learning + Business Intelligence project using the New\_York\_Airbnb\_Enhanced\_Unclean dataset.

This project builds an XGBoost regression model to predict listing prices and provides a Power BI dashboard to explore market behavior and generate price suggestions.





## ⭐Project Highlights



* Built multiple ML models (SVR, Linear Regression, Random Forest, Decision Tree, XGBoost)
* Achieved a final R² ≈ 0.79 using XGBoost
* Extensive data cleaning, feature engineering, and log-transformations
* Generated predicted prices, recommended pricing, and difference analysis
* Designed a clean two-page Power BI dashboard:

    ** Market Overview

    ** Price Recommendation Tool

* Delivered as a downloadable PBIX + screenshots







## 📊Machine Learning Pipeline

1\. Data Cleaning

* Removed extreme outliers
* Converted boolean columns to numeric
* Handled missing values
* Normalized text-based features (amenities, host listings, etc.)



3\. Feature Engineering

* price\_log
* reviews\_log
* nights\_log
* Amenities count
* Encoded categorical features



4\. Model Testing

* Tested:
* Linear Regression
* SVR
* Random Forest
* Decision Tree
* XGBoost Regressor (Final Model)



5\. Final Results

* Random Forest: 0.7978
* Linear Regression: 0.7783
* SVR: 0.7633
* Decision Tree: 0.6623
* XGBoost selected as final model.



6\. Model Output Files

Airbnb\_PowerBI\_Final\_Dataset.csv

→ Full dataset with predicted price \& price difference

price\_suggestion\_grid.csv

→ Dynamic grid for Power BI slider logic





## 📈Dashboard Overview (Power BI)

#### Page 1 — Market Overview

* Total Reviews
* Average Listing Price
* Total Amenities Count
* Room Type Distribution
* Price by Borough
* Map showing listing locations
* Actual vs Predicted price by room type



#### Page 2 — Price Recommendation Tool

* Recommended price (model prediction)
* Average market price
* Pricing gap
* Underpricing/overpricing table

Filters:

* Room type
* Neighbourhood group
* Minimum nights
* Amenities count

Interactive pricing insight visuals





## 🛠️Tech Stack

* Machine Learning
* Python
* Pandas, NumPy
* scikit-learn
* XGBoost
* Joblib
* BI / Visualization
* Power BI Desktop
* DAX
* Data modeling





## ⭐Acknowledgements

Dataset: Inside Airbnb – NYC 2019



Tools: Python, Power BI, XGBoost

Project Goal: ML-driven pricing recommendations for Airbnb hosts

