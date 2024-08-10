# Machine-learning

Problem Description:

A Chinese automobile company aspires to enter the US market by setting up their manufacturing unit there and producing cars locally to give competition to their US and European counterparts. They have contracted an automobile consulting company to understand the factors on which the pricing of cars depends. Specifically, they want to understand the factors affecting the pricing of cars in the American market, since those may be very different from the Chinese market. Essentially, the company wants to know:

*Which variables are significant in predicting the price of a car*

*How well those variables describe the price of a car*

Based on various market surveys, the consulting firm has gathered a large dataset of different types of cars across the American market.

Dataset:  https://drive.google.com/file/d/1FHmYNLs9v0Enc-UExEMpitOFGsWvB2dP/view?usp=drive_link

## Steps
### 1. Data Loading and Preprocessing
Data Loading: Load the dataset and perform initial exploration.
Data Cleaning: Handle missing values, remove duplicates, and address inconsistencies.
Feature Engineering: Create and transform features to prepare the dataset for modeling.
One-Hot Encoding: Encode categorical variables for model input.
Feature Scaling: Normalize or standardize features as needed.


### 2. Model Implementation
The following regression models were implemented:

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Gradient Boosting Regressor

Support Vector Regressor

### 3. Model Evaluation
Models were evaluated using the following metrics:

R-squared

Mean Squared Error (MSE)

Mean Absolute Error (MAE)

### 4. Feature Importance Analysis
Feature importance was analyzed using methods such as feature importance scores from tree-based models and coefficients from linear models.

### 5. Hyperparameter Tuning
Hyperparameter tuning was performed to optimize the best-performing model using techniques like Grid Search.

### 6. Conclusion
The project successfully identified the key factors influencing car prices in the American market and provided a predictive model to assist the company in strategic decision-making.
