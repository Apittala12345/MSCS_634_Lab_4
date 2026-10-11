
# MSCS-634 Lab 4: Regression Analysis with Regularization Techniques

**Course:** MSCS-634 – Advanced Big Data and Data Mining  
**University:** University of the Cumberlands  
**Semester:** Fall 2026

## Lab Objective

This lab demonstrates the implementation and evaluation of regression models using the Diabetes dataset from scikit-learn.

## Dataset

The Diabetes dataset contains 442 patient observations, 10 baseline input features, and a quantitative disease progression target.

## Techniques Implemented

1. Simple Linear Regression using BMI
2. Multiple Linear Regression using all 10 predictors
3. Polynomial Regression using different degrees
4. Ridge Regression with L2 regularization
5. Lasso Regression with L1 regularization

## Evaluation Metrics

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared (R²)

## Visualizations

- Target distribution histogram
- Feature correlation heatmap
- Simple Linear Regression line
- Actual vs predicted scatter plots
- Polynomial regression curves
- Polynomial training vs testing R²
- Ridge and Lasso coefficient comparison
- Effect of alpha on regularization performance
- Final model RMSE and R² comparisons

## Key Insights

- Using multiple features allows a regression model to capture more information than BMI alone.
- Polynomial degree affects model flexibility and the risk of overfitting.
- Ridge and Lasso help control model complexity through regularization.
- Lasso may reduce some coefficients to zero, supporting feature selection.
- Cross-validation helps identify useful regularization strengths.
- Training and testing performance must be compared to assess generalization.

The notebook contains the complete evaluation results and model comparison.

## Challenges and Decisions

- BMI was selected for Simple and Polynomial Regression because of its relationship with the target.
- A consistent 80/20 train-test split was used.
- Several polynomial degrees were evaluated to investigate underfitting and overfitting.
- Feature scaling was applied within the regularization pipelines.
- Five-fold cross-validation was used to select Ridge and Lasso alpha values.
- Model performance was compared using the same testing observations.

## Technologies

Python, Jupyter Notebook, NumPy, Pandas, Matplotlib, Seaborn, and Scikit-learn.

## How to Run

1. Install the required Python libraries.
2. Open `MSCS_634_Lab_4.ipynb` in Jupyter Notebook.
3. Select Kernel → Restart Kernel and Run All Cells.
4. Review the generated evaluation metrics, visualizations, and conclusions.

## Repository Contents

- `MSCS_634_Lab_4.ipynb`
- `README.md`
