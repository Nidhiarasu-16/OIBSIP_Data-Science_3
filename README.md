# Used Car Price Prediction

Project Overview :
This project focuses on predicting the selling price of used cars based on multiple influencing factors such as car age, present price, transmission type, fuel type, and ownership history.
The objective is to build a regression-based machine learning model that can learn pricing patterns from historical data and make reliable predictions for unseen cars.
This project demonstrates the end-to-end data science workflow, from data understanding and preprocessing to model training and evaluation.

Objectives :
- To analyze the factors that significantly affect the selling price of used cars.
- To preprocess and transform raw data into a machine-learning-ready format.
- To build a regression model capable of predicting car prices accurately.To evaluate model performance using appropriate regression metrics.
- To enable price prediction for custom user-defined car inputs.

Dataset Description :
- The dataset contains information about both new and used cars.
- Each row represents a single car record.
- Key Features :
    1. Selling_Price (Target Variable): Price at which the car is sold.
    2. Present_Price: Current ex-showroom price of the car.
    3. Driven_kms: Total distance driven by the car.
    4. Car_Age: Age of the car derived from the manufacturing year.
    5. Fuel_Type: Type of fuel used (Petrol, Diesel, CNG).
    6. Selling_Type: Dealer or Individual seller.
    7. Transmission: Manual or Automatic.
    8. Owner: Number of previous owners.

Problem Type :
- Supervised Learning
- Regression Problem
- The target variable (Selling_Price) is continuous, requiring regression-based models.

Tools and Technology :
1. Programming Language: Python
2. Development Environment: Jupyter Notebook / VS Code
3. Libraries Used:
4. NumPy – numerical computations
5. Pandas – data manipulation and analysis
6. Matplotlib & Seaborn – data visualization
7. Scikit-learn – preprocessing, model building, and evaluation

Methodology :
1. Data Understanding:
    - Analyzed feature types (numerical and categorical).
    - Identified the target variable and predictors.
2. Data Preprocessing:
    - Removed non-informative features such as Car_Name.
    - Created a new feature Car_Age from the manufacturing year.
    - Applied One-Hot Encoding to categorical variables.
    - Avoided outlier removal to preserve real-world price behavior.
3. Exploratory Data Analysis (EDA):
    - Studied relationships between selling price and key predictors.
    - Identified trends such as depreciation with increased car age and kilometers driven.
4. Model Building:
    - Split data into training and testing sets (80:20 ratio).
    - Trained a Linear Regression model as a baseline.
5. Model Evaluation:
    - Used Mean Absolute Error (MAE) to measure average prediction error.
    - Used R² Score to evaluate how well the model explains price variance.
6. Prediction:
    - Enabled prediction for custom car configurations using trained model.

Key Insights :
- Selling price decreases significantly as car age and driven kilometers increase.
- Automatic transmission cars generally have higher resale value than manual ones.
- Cars sold by dealers tend to have higher selling prices compared to individual sellers.
- Present price is one of the strongest predictors of selling price.
- Linear Regression provides a clear baseline and interpretability for price prediction tasks.
