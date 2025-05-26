# 🧠 Coding Week – Machine Learning

This repository contains the solution to **Task 1** from the **Coding Week – Machine Learning** challenge. The objective was to build and evaluate a predictive model based on a provided dataset, following a standard machine learning workflow.

---

## 📌 Task Overview

The task involved understanding and modeling a dataset to predict binary outcomes. Although the final model underperformed compared to a simple baseline (always predicting "No"), the exercise demonstrates a full pipeline of data analysis and model interpretation.

---

## 🧰 Tech Stack & Libraries

| Library       | Version  |
|---------------|----------|
| pandas        | 2.2.3    |
| numpy         | 2.2.6    |
| matplotlib    | 3.10.3   |
| seaborn       | 0.13.2   |
| plotly        | 6.1.1    |
| scikit-learn  | 1.6.1    |

---

## 🔍 Project Structure

The `Task1.ipynb` notebook follows this flow:

1. **Feature Hypothesis**  
   - Attempted to infer the nature and meaning of features in the absence of explicit metadata.
   
2. **Exploratory Data Analysis (EDA)**  
   - Statistical summaries and visualizations to understand data distributions, correlations, and potential outliers.

3. **Model Building**  
   - Developed a classification model using `scikit-learn` pipelines and standard techniques.
   - Evaluated model performance using accuracy and comparison with a naive baseline.

4. **Model Interpretation**  
   - Applied SHAP (SHapley Additive exPlanations) to understand the impact of individual features on model predictions.

---

## ❗ Current Limitations

- **Model Performance**: Accuracy is currently lower than a baseline model predicting "No" for all cases.
- **Feature Understanding**: Dataset columns were not labeled, requiring assumptions and guesses.

---

## 🚀 Future Improvements

- Access to actual feature definitions to refine preprocessing and modeling
- Hyperparameter tuning and feature engineering
- Exploring alternative algorithms (e.g., XGBoost, LightGBM)
- Model performance metrics beyond accuracy (e.g., F1-score, ROC-AUC)

---

## 📂 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Coding-Week-ML.git
   cd Coding-Week-ML
