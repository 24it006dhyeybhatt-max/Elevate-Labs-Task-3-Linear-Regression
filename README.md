# Elevate-Labs-Task-3-Linear-Regression

# Task 3: Linear Regression

## Objective
To implement and understand Simple and Multiple Linear Regression using Python and Scikit-learn. The model is trained to predict house prices based on different housing features.

## Dataset
**Dataset Name:** Housing.csv

The dataset contains information about houses, including:
- Price
- Area
- Number of bedrooms and bathrooms
- Number of stories
- Main road access
- Guestroom and basement availability
- Hot water heating
- Air conditioning
- Parking
- Preferred area
- Furnishing status

## Tools and Technologies
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Tasks Performed

1. Imported the required Python libraries.
2. Loaded and explored the Housing dataset.
3. Checked missing values and duplicate records.
4. Converted categorical features into numerical values using Label Encoding.
5. Separated input features (X) and target feature (y).
6. Split the dataset into training and testing sets (80:20).
7. Trained a Linear Regression model using Scikit-learn.
8. Predicted house prices using the trained model.
9. Evaluated the model using MAE, MSE, and R² Score.
10. Visualized actual and predicted house prices.
11. Analyzed the model intercept and coefficients.

## Model Evaluation Results

| Evaluation Metric | Result |
|---|---:|
| Mean Absolute Error (MAE) | 979679.69 |
| Mean Squared Error (MSE) | 1771751116594.04 |
| R² Score | 0.6495 |

## Result and Conclusion

The Linear Regression model was successfully implemented and trained using the Housing dataset.

The model achieved an R² score of approximately **0.6495 (64.95%)**, indicating that it explains around 64.95% of the variation in house prices in the test dataset.

This task helped me understand data preprocessing, model training, price prediction, model evaluation, and coefficient interpretation.

## Files Included

- `TASK_3_Linear_Regression.ipynb` – Google Colab notebook containing the implementation.
- `Housing.csv` – Dataset used for training and testing.
- `Task_3_Linear_Regression_Outputs.pdf` – PDF containing the important outputs and results.

## Learning Outcome

Through this task, I learned how to build a Linear Regression model, prepare data for machine learning, evaluate prediction accuracy, and understand the relationship between input features and predicted house prices.
