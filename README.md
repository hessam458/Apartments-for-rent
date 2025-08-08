# 📦 Apartment for Rent — Data Analysis & Prediction
## Overview
This project focuses on analyzing rental apartment listings and predicting apartment prices using machine learning techniques. It includes data cleaning, exploratory data analysis (EDA), visualizations, and predictive modeling — all implemented in Python and presented through a Power BI dashboard.

# 🗂️ Project Structure

pre > ```apartment-for-rent/
├── Input/
│   └── apartments.csv
├── Code
│   ├── apartment_for_rent.ipynb       # Data Cleaning & EDA
│   └── ML_Price_Predict.ipynb         # Machine Learning Prediction
├── dashboard/
│   └── Apartments_for_rent.pbix       # Power BI Report
├── README.md
├── requirements.txt ```< /pre


# 📊 Dataset Description
## The dataset includes various attributes of apartment listings, such as:

. Location (latitude, longitude)

. Price

. Number of bedrooms and bathrooms

. Area (square footage)

. Type of listing (e.g., Studio, 1BR, 2BR)

## Initial data preprocessing steps included:

. Converting non-standard "null" values to Python-readable NaN

. Removing or filling missing values as appropriate

# 🔍 Exploratory Data Analysis (Python)
## Key insights extracted through Python include:

. Distribution of apartment prices by geographic location

. Price trends by number of rooms and area

. Outlier detection and handling

. Correlation between numeric features

# 📈 Power BI Dashboard
A Power BI dashboard was developed to provide interactive and visual insights from the apartment rental dataset.

## Key dashboard elements:

. Map View: Displays geographic distribution of rental listings by price and location

. Bar & Column Charts: Show rental trends by number of bedrooms, bathrooms, and apartment types

. Filters: Allow users to slice data by price ranges, locations, and room counts

. KPI Cards: Summarize key metrics such as average price, total listings, and most common apartment types

This dashboard enables users to visually and interactively explore patterns in the rental market.

# 🤖 Machine Learning — Price Prediction
## The project includes a machine learning pipeline to predict rental prices based on various features such as:

. Number of rooms and bathrooms

. Square footage

. Location coordinates

## Key steps:

. Outlier Removal: The Top 1% of high-price outliers were removed to reduce skewness and improve model performance.

. Feature Selection & Preprocessing: Only relevant columns were used to build the prediction model. Categorical variables were encoded, and missing values were handled appropriately.

. Modeling: Regression algorithms were used to predict apartment prices. The performance was evaluated using appropriate metrics (e.g., MAE, RMSE, R²).

# 🛠️ Tools & Technologies
. Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)

. Jupyter Notebook

. Power BI

. Git & GitHub

# 📌 Author
## Hessam Abedinpour
Data enthusiast with a focus on business analysis, data visualization, and predictive modeling.
