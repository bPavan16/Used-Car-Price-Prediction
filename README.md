# Used Car Price Prediction

This project was developed as an individual endeavor to predict the price of used cars based on various car attributes. Using multiple regression models, I explored how factors like brand, model, mileage, and engine type influence pricing. This project allowed me to apply a range of machine learning algorithms and to deepen my understanding of model tuning and feature engineering.

## Project Overview

The primary objective of this project is to predict used car prices accurately, leveraging various machine learning algorithms. Through data analysis and model tuning, I aimed to achieve an optimized predictive tool that can provide insights into used car pricing.

## Dataset

The dataset used in this project contains the following features:

- **brand**: Manufacturer of the car (e.g., Toyota, Ford).
- **model**: Specific model of the car (e.g., Corolla, Mustang).
- **model_year**: Year the car model was manufactured, which influences depreciation.
- **mileage**: Total miles the car has been driven, which affects value.
- **fuel_type**: Type of fuel (e.g., petrol, diesel, electric).
- **engine**: Engine specifications, typically represented by engine capacity, which affects performance.
- **transmission**: Type of transmission (e.g., automatic, manual).
- **ext_col**: Exterior color of the car.
- **int_col**: Interior color of the car.
- **accident**: Whether the car has a history of accidents (yes or no).
- **clean_title**: Indicates if the car has a clean title, showing it hasn’t been a total loss.
- **price**: The target variable representing the car’s price.

## Models Implemented

During this project, I implemented a variety of machine learning algorithms to understand their effectiveness in predicting car prices. These include:

1. **Linear Regression**
2. **Random Forest Regressor**
3. **Decision Tree Regressor**
4. **XGBoost Regressor**
5. **CatBoost Regressor**
6. **AdaBoost Regressor**
7. **LightGBM Regressor**
8. **ElasticNet Regression**

### Hyperparameter Tuning

To enhance model performance, I used **RandomizedSearchCV** for hyperparameter tuning. This allowed me to efficiently explore a range of hyperparameters and select the best configurations for each model.

## Project Workflow

1. **Data Preprocessing**:
   - Handled missing values, encoded categorical variables, and normalized numerical features.
   - Split data into training and testing sets.

2. **Exploratory Data Analysis (EDA)**:
   - Analyzed relationships between each feature and the target variable (price).
   - Identified high-impact features for the predictive models.

3. **Model Training and Evaluation**:
   - Trained each model on the training set and evaluated on the test set using metrics such as RMSE, MAE, and R².
   - Compared model performances to determine the best-fit model for price prediction.

4. **Hyperparameter Tuning**:
   - Used RandomizedSearchCV to fine-tune each model's hyperparameters for optimal performance.

## Key Learnings

This project helped me build a strong understanding of machine learning models, especially ensemble models like XGBoost, CatBoost, and LightGBM. I also gained insight into how tuning hyperparameters and selecting relevant features impact predictive accuracy.

## Results

- The **XGBoost** and **Random Forest** models delivered the most accurate results.
- **ElasticNet Regression** was effective in handling multicollinearity and selecting important features.
- Hyperparameter tuning with RandomizedSearchCV contributed significantly to model improvement.

## Conclusion

This project provided valuable hands-on experience with multiple machine learning techniques, especially in regression tasks. It enabled me to compare models effectively and gain insights into the factors influencing car prices.

## Installation and Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/bPavan16/Used-Car-Price-Prediction.git
