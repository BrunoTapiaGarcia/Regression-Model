# Predict bike rentals for Divvy.

Objective 

The bike sharing industry has grown tremendously in recent years, with an estimated global value of $2.8 billion in 2023. This is due to a number of factors, such as convenience, sustainability, and physical fitness. The primary objective of this project is to predict the number of bike rentals for Dyyv, a leading company based in Chicago, over a 30-day period. By accurately forecasting rental volumes, the company can optimize operations, enhance service offerings, and contribute to the broader goal of promoting sustainable urban mobility.


Dataset

<a href="chicago_training_data.xlsx">Download chicago_training_data.xlsx</a>


**Model types used:**

**Gradient Boosting Regressor:** This model builds an ensemble of weak learners, typically decision trees, and combines them to improve prediction accuracy. It is particularly effective in capturing complex patterns and interactions within the data.

**K-Nearest Neighbors (KNN):** This model predicts the target value based on the average values of the k-nearest data points. It's useful for capturing local patterns and relationships within the dataset.

**Decision Tree Regressor:** This model splits the data into branches based on feature values, creating a tree-like structure that makes decisions at each node. It's intuitive and capable of modeling non-linear relationships in the data

**Modeling Steps**

Package and Dataset Imports: Import libraries and load the dataset.

Exploratory Data Analysis (EDA) and Data Preprocessing (DP):

EDA: Analyze data using statistics, histograms, and correlations.
DP: Handle missing values, perform feature engineering, and prepare data for modeling.
Candidate Model Development: Develop and evaluate various models.

Hyperparameter Tuning: Optimize model parameters for better performance.

Final Model Selection: Choose the best-performing model for final predictions.


Document:

<a href="Rentals_prediction_Divvy.ipynb">Download the Jupyter file</a>,

<a href="Rentals_prediction_Divvy.html">View project in HTML</a>



