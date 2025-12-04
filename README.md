✈️ Flight Ticket Price Prediction – Machine Learning Project

This project analyzes a Flight Booking Dataset and builds a predictive model to estimate the ticket price based on travel details such as airline, journey duration, number of stops, etc.

By performing data cleaning, feature preprocessing, exploratory data analysis, and regression modeling, this project helps identify key factors influencing flight pricing.

🎯 Objective

To build a model that accurately predicts flight ticket prices and extract meaningful insights that can assist travelers, booking platforms, and airline businesses in identifying price patterns.

📂 Project Workflow
Step	Description
1️⃣ Problem Understanding	Define business goal (price prediction)
2️⃣ Data Loading	Imported dataset from CSV
3️⃣ Data Cleaning	Handling missing values & removing unwanted columns
4️⃣ EDA	Visualization of categorical & numerical variables
5️⃣ Feature Engineering	Transformed features for modeling
6️⃣ Model Building	Regression-based ML models
7️⃣ Evaluation	Model accuracy using regression metrics
8️⃣ Insights	Interpretation of pricing factors
📊 Dataset Description
Attribute Type	Examples
Airlines	IndiGo, Air India, Jet Airways
Route Information	Source → Destination paths
Stops	Non-stop, 1-stop, 2-stop etc.
Journey Time	Duration of flight, departure & arrival timings
Target	Price (numeric output)

Data Source: Flight booking dataset obtained via online flight booking platform

🔍 Exploratory Data Analysis (EDA)

Key observations from visual analysis:

✔ More stops → Higher price
✔ Premium airlines show significantly higher fares
✔ Flight duration strongly correlates with price
✔ Certain travel months/days impact pricing

(Data visuals include bar plots, distribution charts & comparison graphs)

🧠 Machine Learning Model

A regression model was applied to predict ticket prices.
Models explored commonly include:

Linear Regression

Random Forest Regressor

Decison Tree Regressor


Evaluation metrics used:
✔ MAE
✔ RMSE
✔ R² Score



🛠 Tech Stack
Tool	Purpose
Python	ML development
Pandas & NumPy	Data preprocessing
Matplotlib & Seaborn	Visualizations
Scikit-Learn	Regression modeling
Jupyter Notebook	Project execution
