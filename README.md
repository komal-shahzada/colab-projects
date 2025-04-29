# 🩺 Diabetes Prediction Using Machine Learning

This project is focused on predicting whether a person is diabetic or not using various machine learning models. The dataset was obtained from Kaggle and includes multiple symptoms and medical conditions related to diabetes.

## 📌 Features Used
- Gender
- Polyuria
- Polydipsia
- Sudden Weight Loss
- Weakness
- Polyphagia
- Genital Thrush
- Visual Blurring
- Itching
- Irritability
- Delayed Healing
- Partial Paresis
- Muscle Stiffness
- Alopecia
- Obesity
- Age

## 🧠 Machine Learning Models Used
- Support Vector Machine (SVM)
- Logistic Regression
- Decision Tree Classifier
- Voting Classifier (Ensemble - Soft Voting)
- Stacking Classifier
- Grid Search CV for Hyperparameter Tuning
- Polynomial Features for Feature Expansion

## 📊 Accuracy & Evaluation
- **SVM Accuracy (Test):** ~X.XX%
- **Stacking Model Accuracy:** ~X.XX%
- Cross-Validation Score: ~X.XX%

> Confusion Matrix and Classification Report included in notebook.

## 🌐 Live Gradio App
A user-friendly web interface has been created using [Gradio](https://gradio.app/) where users can input symptoms and receive instant predictions.

```python
interface.launch()
