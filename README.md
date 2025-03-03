# Machine_Learning_End_Project
## Car Price Prediction Project

## Objective
The objective of this project is to build a predictive model to estimate car prices based on various features. A Chinese automobile company aims to enter the U.S. market and wants to understand the key factors influencing car prices to optimize their strategy.

## Business Goal
The model will help the management understand pricing dynamics in the American market and adjust car designs, marketing strategies, and business plans accordingly.

## Dataset
The dataset consists of multiple independent variables affecting car prices, collected from various market surveys.

## Key Components

### 1. Loading and Preprocessing
- Loaded the dataset.
- Handled missing values by removing nulls.
- Encoded categorical variables using one-hot encoding.
- Standardized numerical features using `StandardScaler`.

### 2. Model Implementation
Implemented five regression algorithms:
1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor
4. Gradient Boosting Regressor
5. Support Vector Regressor

### 3. Model Evaluation
- Compared models based on:
  - R-squared (R²)
  - Mean Squared Error (MSE)
  - Mean Absolute Error (MAE)
- Identified the best-performing model.

### 4. Feature Importance Analysis
- Analyzed important features using Random Forest feature importances.
- Visualized the top 10 influential features.

### 5. Hyperparameter Tuning 
- Performed GridSearchCV tuning for `RandomForestRegressor`.
- Optimized `n_estimators`, `max_depth`, and `min_samples_split`.
- Improved model performance.


## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn


## Results and Insights
- The dataset was successfully cleaned and preprocessed.
- Random Forest was the best-performing model.
- Top influencing factors in car pricing were identified.
- Hyperparameter tuning improved model performance.



