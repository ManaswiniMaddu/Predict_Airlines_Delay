## Predict_Airlines_Delay
Utilized Regression, Linear Discriminant Analysis, and Decision Tree Classifier models to predict flight delays based on factors like travel day and airline. Achieved an accuracy of ~82.5% with Logistic Regression and 63% with the Decision Tree model.

# Project Overview
Airline delays have a significant impact on both passengers and the airline industry, often resulting in crowded airports, wasted time for travelers, and additional operational costs. This project uses machine learning classification algorithms to predict flight delays based on various factors, such as departure and arrival locations, day of travel, and flight time.
The goal is to identify if a flight will be delayed, with "1" indicating a delay and "0" indicating no delay. This prediction can help airlines manage scheduling more effectively, optimize passenger experience, and improve overall efficiency.

# Dataset
The dataset, sourced from Kaggle, includes:
- Rows: 539,383
- Columns: 8 features — including airline, departure airport, destination airport, day of the week, flight time, and delay status.
Each row represents a unique flight record, with categorical and numerical variables processed for analysis.

# Features
- Airline: The airline carrier code.
- Flight Number: The specific flight identifier.
- Airport From/To: Departure and arrival airport codes.
- Day of the Week: Day the flight departs.
- Time: Time of the flight.
- Length: Duration of the flight.
- Delay: Binary outcome (1 for delay, 0 for no delay).

# Libraries Used
- Pandas: Data manipulation and analysis.
- NumPy: Numerical operations.
- Scikit-learn: For various machine learning functionalities, including classification models, data preprocessing, and cross-validation.

# Methodology
1. Data Preprocessing: The data is preprocessed to handle categorical values, drop nulls, and standardize formats. The dataset is split into training (80%) and testing (20%) subsets to build and evaluate model performance.
2. Classification Models:
    - Logistic Regression: Used for binary classification to predict delay status. Accuracy achieved: 82.5%.
    - Decision Tree Classifier: Uses hierarchical decision rules based on feature values to predict outcomes. Accuracy achieved: 63%.
    - Linear Discriminant Analysis (LDA): Reduces the number of features to improve model efficiency in classification tasks.
3. Model Evaluation: Metrics include accuracy and the area under the ROC curve, which illustrates the true positive rate vs. false positive rate for each model.

# Visualization
Data visualizations provide insights into patterns and trends, such as:
- Airline-specific delay frequencies.
- Delay patterns by day of the week.
- ROC curves for model performance evaluation.

# Conclusion
The Logistic Regression model demonstrates the highest accuracy in predicting delays and is recommended for further application. This analysis can help airlines improve operational efficiency, and passengers can better plan their travel based on patterns identified in the delay data.

# Getting Started
To run this project locally:
1. Clone the repository
2. Install dependencies
3. Run the Jupyter Notebook

