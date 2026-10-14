
# CodeOrbit Internship — Task 3
## Simple Linear Regression Using Python

**Student:** Ritesh Kumar Singh  
**Internship:** CodeOrbit Tech — Data Science Internship  
**Project:** Titanic Dataset Analysis  
**Task:** Simple Linear Regression

---

## 1. Objective

To build a Simple Linear Regression model using Python and
Scikit-learn, generate predictions, evaluate model performance,
and visualize the results.

In this experiment, Age is the input feature and Fare is the
numerical target. This is a beginner learning exercise.

## 2. Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## 3. Methodology

1. Load the cleaned Titanic dataset.
2. Select Age as the input feature (X) and Fare as the target (y).
3. Remove rows with missing values in the selected columns.
4. Split the dataset into training and testing sets (80/20).
5. Create and train a Linear Regression model.
6. Generate predictions on the test dataset.
7. Evaluate the model using MAE, MSE, RMSE, and R².
8. Visualize actual and predicted values.
9. Save prediction results and charts.

## 4. Dataset Overview

- Dataset: Titanic
- Original dataset size: 891 records
- Input feature: Age
- Target variable: Fare
- Training/testing split: 80% / 20%

## 5. Model Creation and Training

The model is created and trained using:

```python
model = LinearRegression()
model.fit(X_train, y_train)
```

The fitted model learns a linear equation:

**Predicted Fare = Intercept + (Coefficient × Age)**

The actual coefficient and intercept depend on the model trained
in the notebook.

## 6. Model Evaluation

The model is evaluated using these metrics:

- **MAE:** Mean absolute difference between actual and predicted fares.
- **MSE:** Mean squared prediction error.
- **RMSE:** Square root of MSE, expressed in Fare units.
- **R² Score:** Indicates how well the model explains variation in Fare.

Actual metric values should be copied from the notebook output.

## 7. Visualizations

The project generates:

- `Task3_Actual_vs_Predicted.png`
- `Task3_Regression_Line.png`

These charts help compare model predictions with actual values
and visualize the fitted regression line.

## 8. Key Findings

- The model demonstrates the basic linear regression workflow.
- Age alone may not be sufficient to predict passenger fares.
- Evaluation metrics help identify prediction errors.
- Additional features may improve performance, but require further testing.

## 9. Conclusion

I implemented a Simple Linear Regression model using Python
and Scikit-learn. I selected Age as the input feature and Fare
as the target, split the dataset into training and testing sets,
trained the model, generated predictions, evaluated its performance,
and visualized the results.

This task helped me understand model training, prediction,
evaluation metrics, and regression visualization.

## 10. Limitations

Age alone may not explain passenger fares accurately. Fare can
depend on passenger class, ticket details, and other variables.
This is a learning project, not a reliable real-world prediction system.

## 11. Deliverables Checklist

- [ ] `Task3_Simple_Linear_Regression.ipynb`
- [ ] `Task3_Actual_vs_Predicted.png`
- [ ] `Task3_Regression_Line.png`
- [ ] `CodeOrbit_Task3_Predictions.csv`
- [ ] `CodeOrbit_Task3_Linear_Regression.pkl` (optional)

---

**Report generated on:** 14 October 2026
