Project Summary: Model Comparison on Salary Prediction (Multiple Models)

This project evaluates five different regression models on the same dataset to identify which algorithm best predicts salary based on position level. To ensure fairness and reusability, all models were built using a generic machine learning pipeline.

This is part of my daily machine learning practice and GitHub uploads.

📌 Objective

To compare the performance of multiple regression models and determine which one provides the most accurate salary predictions for this dataset.

📊 Dataset

The dataset (Position_Salaries.csv) contains:

Position

Level

Salary

This dataset is small, non-linear, and ideal for testing different regression techniques.

🤖 Models Evaluated

Using a generic ML pipeline, I implemented the following models:

Multiple Linear Regression

Polynomial Regression

Support Vector Regression (SVR)

Decision Tree Regression

Random Forest Regression

Each model was trained, evaluated, and compared using the same pipeline structure.

🛠️ Steps Performed

Built a reusable data preprocessing + training pipeline

Trained all five models independently

Predicted salary values

Calculated evaluation metrics (R² Score, MAE, RMSE, etc.)

Exported results to Model_Selection.csv

Compared model performance side-by-side

Visualized prediction curves for each model

📈 Key Insight

Linear Regression underfits the data due to non-linearity.

Polynomial Regression captures the curve effectively.

SVR with RBF kernel performs well on small non-linear datasets.

Decision Tree shows step-like predictions and may overfit.

Random Forest Regression emerges as the best model, offering smooth, accurate predictions with reduced overfitting.

(You can update this line if your results differ.)

🧪 Outputs

Model_Selection.csv containing performance metrics

Visual comparison of model prediction curves

Generic pipelines for each regression technique

Final selected best model

🚀 Conclusion

This project highlights the importance of:

Testing multiple algorithms

Using a consistent pipeline

Choosing the model that fits the dataset’s pattern

By comparing all five models fairly, we can confidently select the most appropriate algorithm for salary prediction on this dataset.
