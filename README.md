# Housing-Regression-Analysis is a machine learning project that explores the Boston Housing dataset to predict median house prices (MEDV) using linear and polynomial regression techniques. This project demonstrates data cleaning, exploratory data analysis (EDA), model training, evaluation, and visualization of residuals and predictions.

#  Project Highlights
✅ Loaded and cleaned the dataset (handled missing values, dropped rows with NaN)
✅ Performed EDA — statistical summary, correlation heatmap
✅ Built simple linear regression using RM (average number of rooms) as predictor
✅ Evaluated model performance on training and testing sets (MAE, MSE, RMSE)
✅ Visualized predictions, residuals, and their distributions
✅ Implemented polynomial regression (degree=1) and compared results
✅ Extended model to use all features (multivariable regression)

#  Dataset
Boston Housing Dataset (CSV file),
Features: CRIM, ZN, INDUS, CHAS, NOX, RM, AGE, DIS, RAD, TAX, PTRATIO, B, LSTAT,
Target: MEDV (Median value of owner-occupied homes in $1000’s).

#  Libraries & Tools
Python,
Pandas, NumPy,
Matplotlib, Seaborn,
Scikit-learn.

#  Visualizations
Correlation heatmap of features,
Scatter plots: actual vs predicted prices,
Residual plots and histograms.

#  Future Improvements
Try Ridge/Lasso regularization,
Hyperparameter tuning,
Use more complex polynomial degrees,
Cross-validation for better evaluation.
