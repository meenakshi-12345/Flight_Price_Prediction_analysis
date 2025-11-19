✈️ Flight Price Prediction – Machine Learning Project

This project focuses on predicting flight ticket prices based on different flight-related features. It covers the complete workflow of a real machine learning pipeline — from raw data to model evaluation.

📌 Project Overview

Flight ticket prices vary due to several factors like airline, travel route, journey duration, and timing. In this project, I explore these factors and build models that can predict the price of a flight before booking.

The dataset includes columns such as:

Airline

Source & Destination cities

Date of Journey

Departure & Arrival Time

Total Stops

Duration

Price

🛠️ Steps Performed
1. Data Cleaning & Preprocessing

Removed irrelevant characters from the time and duration columns.

Extracted hours and minutes from Arrival, Departure, and Duration fields.

Handled missing values and formatted columns properly.

2. Feature Engineering

Converted textual categories (Airline, Source, Destination) into numeric form using One-Hot Encoding.

Created new columns such as:

Arrival_Hour, Arrival_Minute

Dep_Hour, Dep_Minute

Duration_Hour, Duration_Minute

3. Machine Learning Models

Trained three supervised ML models:

Linear Regression

Decision Tree Regressor

Random Forest Regressor

4. Model Evaluation

Evaluated using:

R² Score

RMSE (Root Mean Squared Error)

Random Forest delivered the most stable and accurate results for this dataset.

📊 Tech Stack

Python

Pandas, NumPy

Scikit-learn

Matplotlib / Seaborn (for visualisation)

🎯 Key Learning Outcomes

How flight characteristics impact pricing

How to engineer features for ML models

Handling categorical variables

Comparing regression models

Building a complete ML workflow

🚀 Future Improvements

Add hyperparameter tuning for better accuracy

Deploy the model using Flask or FastAPI

Integrate real-time airline data

Build a small frontend to test predictions

🤝 Contributions

Suggestions and improvements are welcome!
