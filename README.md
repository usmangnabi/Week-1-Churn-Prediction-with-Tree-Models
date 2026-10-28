# Customer Churn Prediction Using Tree-Based Models

A machine learning project to predict customer churn in the telecommunications industry using classification algorithms, ensemble learning, and model explainability techniques.

## 📌 Project Overview

Customer churn occurs when customers stop using a company's services. Predicting churn helps businesses identify customers who may leave and develop better retention strategies.

This project uses the **Telco Customer Churn dataset** to build, tune, and compare machine learning models for identifying potential churn.

## 🎯 Project Objectives

- Prepare customer data for machine learning and address class imbalance.
- Establish a baseline using Logistic Regression.
- Compare Decision Trees using Gini and Entropy criteria.
- Evaluate Bagging and Random Forest ensemble methods.
- Tune AdaBoost, Gradient Boosting, and XGBoost using cross-validation.
- Compare model performance using standard classification metrics.
- Interpret important churn-related features using SHAP.

## 🤖 Machine Learning Models

| Category | Models |
|---|---|
| Baseline | Logistic Regression |
| Decision Trees | Gini, Entropy |
| Ensemble Learning | Bagging, Random Forest |
| Boosting | AdaBoost, Gradient Boosting, XGBoost |

## 📊 Model Evaluation

Models are evaluated on a separate test dataset, while validation data and cross-validation support model selection and hyperparameter tuning.

The following metrics are used:

- **Accuracy:** Overall proportion of correct predictions.
- **Precision:** Proportion of predicted churn cases that are actual churn cases.
- **Recall:** Proportion of actual churn cases correctly identified.
- **F1-Score:** Balance between precision and recall.
- **ROC-AUC:** Ability to distinguish between churn and non-churn customers.

## 🔍 Model Explainability

**SHAP (SHapley Additive exPlanations)** is used to understand how features contribute to model predictions. This helps identify influential customer characteristics and provides insights that may support customer-retention decisions.

Feature importance indicates predictive influence, not necessarily causation.

## 🛠️ Technologies Used

- Python
- Pandas and NumPy
- Scikit-learn
- XGBoost
- Matplotlib and Seaborn
- SHAP
- Jupyter Notebook

## 📁 Repository Structure

```text
customer-churn-prediction/
├── churn_prediction.ipynb
├── requirements.txt
└── README.md
```

- `churn_prediction.ipynb` — Data preprocessing, model training, tuning, evaluation, and visualizations.
- `requirements.txt` — Required Python libraries.
- `README.md` — Project documentation and setup instructions.

## 🚀 Getting Started

### 1. Clone the Repository

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Prepare the Dataset

Download the Telco Customer Churn dataset and place it at the file path expected by the notebook. Update the dataset path if necessary.

### 4. Run the Notebook

Open `churn_prediction.ipynb` in Jupyter Notebook or another compatible notebook environment and run the cells from top to bottom.

## 📈 Results

The notebook presents the model comparison, evaluation metrics, visualizations, and SHAP explanations. The final model selection should be based on the recorded evaluation results and the project's prediction objectives.

## ⚠️ Limitations

- Results depend on the dataset, preprocessing choices, and model parameters.
- Class imbalance and the choice of evaluation metric can affect model comparisons.
- Predictive relationships do not establish that a feature causes customer churn.
- Real-world deployment would require further validation on new customer data.

## 👨‍💻 Project Goal

To develop practical machine learning skills by building an end-to-end customer churn prediction workflow, comparing classification algorithms, and interpreting model predictions.

---

*This project is intended for educational and portfolio purposes.*
