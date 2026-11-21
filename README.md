# Customer Churn Risk Prediction

## Project Overview
This project predicts customer churn in the telecommunications industry using Statistical Machine Learning techniques. It compares Logistic Regression and Decision Tree classifiers and includes an interactive prototype for individual customer predictions.

## Dataset
**IBM Telco Customer Churn Dataset**
- 7,043 customer records
- 21 original columns
- [Dataset Source](https://raw.githubusercontent.com/IBM/telco-customer-churn-on-icp4d/master/data/Telco-Customer-Churn.csv)

## Technologies Used
- Python
- Google Colab
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- ipywidgets

## Machine Learning Models
1. Logistic Regression
2. Decision Tree Classifier

## Model Performance

| Metric | Logistic Regression | Decision Tree |
|---|---:|---:|
| Accuracy | 74.02% | 75.80% |
| Precision | 50.70% | 53.02% |
| Recall | 77.54% | 77.54% |
| F1-score | 61.31% | 62.98% |
| ROC-AUC | 83.85% | 83.40% |

## Interactive Prototype
The project includes an interactive prototype built using ipywidgets. Users can enter customer details and obtain:
- Predicted churn class
- Estimated churn probability
- Churn risk category (Low, Medium, or High)

The prototype uses the trained Logistic Regression pipeline.

## Project Files
- `Customer_Churn_Risk_Prediction.ipynb` — Complete project notebook, including preprocessing, analysis, model training, evaluation, and prototype.

## How to Run
1. Open the notebook in Google Colab.
2. Run all cells in sequence.
3. Wait for preprocessing, model training, and evaluation to complete.
4. Use the interactive prototype to enter customer details and view predictions.

## Limitations
The models are evaluated on a held-out test set from the same dataset. Their performance may differ when applied to future customers or data from other telecommunications providers. Predictions should be treated as decision-support estimates, not guarantees.
