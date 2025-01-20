# Loan Default Risk Prediction

## Overview
This project demonstrates the use of machine learning to predict loan default risk. The model is designed to help financial institutions identify high-risk borrowers and make data-driven lending decisions. By analyzing borrower data, the model provides insights into key predictors and achieves exceptional accuracy.

---

## Key Features
- **Highly Accurate Model**: Achieved 99% accuracy using a Random Forest Classifier.
- **Performance Metrics**: 
  - Precision, recall, and F1-scores are near perfect for both classes (default and non-default).
  - ROC-AUC score of 1.00, showcasing flawless discrimination between classes.
- **Feature Importance Analysis**: Identified critical predictors such as:
  - `credit_lines_outstanding`
  - `total_debt_outstanding`
  - `fico_score`
- **Visual Insights**: 
  - ROC Curve
  - Feature Importance
  - Default Distribution

---

## Visualizations

### ROC Curve
The ROC Curve demonstrates the model's exceptional performance with an AUC score of 1.00, indicating perfect predictions.

![ROC Curve](images/roc_curve.png)

### Feature Importance
This chart highlights the most influential features in predicting loan defaults. The top predictors include `credit_lines_outstanding` and `total_debt_outstanding`.

![Feature Importance](images/feature_importance.png)

### Default Distribution
The default distribution visualization highlights the class imbalance in the dataset, where non-defaults significantly outnumber defaults.

![Default Distribution](images/default_distribution.png)

---

## Classification Report
The classification report summarizes the performance of the model across precision, recall, and F1-score metrics:

          precision    recall  f1-score   support

       0       1.00      1.00      1.00      1652
       1       0.99      0.98      0.98       348

accuracy                           0.99      2000

macro avg 0.99 0.99 0.99 2000 weighted avg 0.99 0.99 0.99 2000


---

## Technologies Used
- **Programming Language**: Python
- **Libraries**: 
  - Scikit-learn
  - Pandas
  - Matplotlib
- **Dataset**: Excel file (`Task 3 and 4_Loan_Data.xlsx`)

---

Results
- ROC Curve: Demonstrated perfect performance with an AUC score of 1.00.
- Feature Importance: Key predictors identified for effective decision-making.
- Classification Metrics: Achieved 99% accuracy with high precision and recall across both classes.

Future Work
- Validate the model using additional datasets for generalizability.
- Experiment with advanced algorithms like XGBoost and LightGBM.
- Develop an interactive dashboard for non-technical stakeholders to interpret predictions.

Contact
- If you have feedback or are interested in collaborating, feel free to connect with me on LinkedIn(https://www.linkedin.com/in/nikhil-chandran-0a779b1a4/).
