Project Title:

California House Price Prediction using Machine Learning

Short Description:

The project focuses on predicting house prices in California based on various features like location, median income, number of rooms, population, and more. This helps buyers, sellers, and real estate professionals make informed decisions.

Problem Statement:

Accurate prediction of housing prices is essential in real estate for investment planning, mortgage estimation, and policy-making. The problem is to develop a regression model that can predict median house prices in California districts using demographic and geographic features.

Dataset Used:

California Housing Dataset – publicly available from Scikit-learn.

Libraries / Frameworks Used:

Python Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

Optional: XGBoost, LightGBM for advanced regression

Visualization: matplotlib, seaborn

Methodology:

Data Loading & Exploration

Load the dataset and check for missing values.

Explore distributions, correlations, and outliers.

Data Preprocessing

Handle missing values if any (median imputation).

Feature scaling using StandardScaler or MinMaxScaler.

Optionally, create new features (e.g., rooms per household, bedrooms per room).

Train-Test Split

Split dataset into train and test sets (e.g., 80:20).

Model Selection & Training

Train regression models: Linear regression

Model Evaluation

Metrics used:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R² Score

Visualize predicted vs actual values.

Feature importance for tree-based models.
