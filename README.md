# Titanic Fare Prediction — Simple Linear Regression

## CodeOrbit Tech — Data Science Internship | Task 3

**Author:** Ritesh Kumar Singh

## Project Overview
This project demonstrates Simple Linear Regression using Python and Scikit-learn. The Titanic dataset is used to train a model that predicts Fare from Age as a beginner machine-learning exercise.

## Objectives
- Prepare input features and a numerical target.
- Split data into training and testing sets.
- Train a Linear Regression model.
- Generate predictions.
- Evaluate the model using MAE, MSE, RMSE, and R².
- Visualize actual versus predicted values and the fitted regression line.

## Tools Used
- Python
- Pandas and NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Model
Input feature: Age  
Target variable: Fare

The model learns a linear equation:

`Predicted Fare = Intercept + (Coefficient × Age)`

## Evaluation
The notebook calculates:
- MAE — Mean Absolute Error
- MSE — Mean Squared Error
- RMSE — Root Mean Squared Error
- R² — Coefficient of Determination

Refer to the notebook output for the actual metric values.

## Visualizations
- Actual versus predicted Fare.
- Age versus Fare with the fitted regression line.

## Limitations
Age alone may not explain passenger fares accurately. This is a learning exercise, not a reliable real-world fare prediction system.

## How to Run
1. Install the required packages: `pip install pandas numpy matplotlib scikit-learn`.
2. Open the notebook in Jupyter.
3. Make sure the cleaned Titanic CSV is available.
4. Update the dataset path if necessary.
5. Run the notebook cells in order.

## Conclusion
This project demonstrates model training, prediction, evaluation, and visualization using a basic regression algorithm. The evaluation metrics help assess how well the model performs on unseen test records.
