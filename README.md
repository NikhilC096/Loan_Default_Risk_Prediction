# Loan Default Risk Prediction Model

## Overview
This project demonstrates the use of machine learning to predict loan default risk. The model helps financial institutions identify high-risk borrowers and make data-driven decisions.

## Key Features
- **Machine Learning Model**: Built a Random Forest Classifier to predict default risk with 99% accuracy.
- **Performance Metrics**:
  - ROC-AUC Score: 1.00
  - Precision, Recall, and F1-Score: High performance for both default and non-default cases.
- **Feature Importance**: Identified key predictors like `credit_lines_outstanding` and `total_debt_outstanding`.
- **Visualizations**: 
  - ROC Curve
  - Feature Importance
  - Default Distribution

## Technologies Used
- Python
- Libraries: Scikit-learn, Pandas, Matplotlib
- Dataset: Excel file (`Task 3 and 4_Loan_Data.xlsx`)

Results
- ROC Curve: Perfect model performance with AUC = 1.00.
- Feature Importance: Top predictors identified for better decision-making.
- Default Distribution: Insights into the imbalance between default and non-default cases.
Future Work
- Experiment with additional datasets to validate the model.
- Explore advanced machine learning algorithms (e.g., XGBoost).
- Build an interactive dashboard for visualizing predictions.
Contact
- Feel free to share feedback or collaborate!
