# MaternalGuard
AI-Powered Maternal Health Risk Prediction and Postpartum Wellness Companion
# MaternalGuard: AI-Powered Maternal Health Risk Prediction & Postpartum Wellness Companion

## Overview

MaternalGuard is an AI-based healthcare project designed to assist pregnant and postpartum women by predicting maternal health risks and providing postpartum wellness monitoring. The system uses Machine Learning techniques to analyze maternal health parameters and classify patients into risk categories while also offering a wellness assessment module for postpartum recovery.

**Note:** This project is intended for educational and research purposes only and should not be used as a substitute for professional medical advice or diagnosis.

---

## Features

### Maternal Health Risk Prediction

* Predicts maternal health risk levels:

  * Low Risk
  * Mid Risk
  * High Risk
* Uses machine learning algorithms for classification.
* Supports data-driven healthcare decision support.

### Explainable AI

* SHAP (SHapley Additive Explanations) integration.
* Identifies which health factors contribute most to risk prediction.
* Improves transparency and interpretability.

### Postpartum Wellness Module

* Sleep Score Analysis
* Mood Score Analysis
* Stress Wellness Assessment
* Recovery Score Calculation
* Personalized wellness recommendations

### Data Visualization

* Risk distribution analysis
* Blood pressure analysis
* Blood sugar analysis
* Feature importance visualization

---

## Dataset

The project uses the Maternal Health Risk Dataset containing:

| Feature     | Description              |
| ----------- | ------------------------ |
| Age         | Mother's age             |
| SystolicBP  | Systolic blood pressure  |
| DiastolicBP | Diastolic blood pressure |
| BS          | Blood sugar level        |
| BodyTemp    | Body temperature         |
| HeartRate   | Heart rate               |
| RiskLevel   | Risk category            |

---

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* XGBoost
* SHAP
* Git & GitHub

---

## Project Structure

``text
MaternalGuard/
│
├── dataset/
│   └── maternal_health.csv
│
├── notebooks/
│   └── MaternalGuard.ipynb
│
├── models/
│   └── maternal_model.pkl
│
├── reports/
│
├── screenshots/
│
├── README.md
│
└── requirements.txt
`

---

## Machine Learning Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. Explainable AI (SHAP)
9. Postpartum Wellness Assessment
10. Deployment Preparation

---

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

---

## Future Enhancements

* Real-time maternal monitoring
* Wearable device integration
* Voice-based emotional analysis
* Multilingual support (Tamil and English)
* Streamlit web application deployment
* Personalized AI healthcare assistant

---

## Results

The model successfully predicts maternal health risk levels and provides explainable insights into the contributing factors. The postpartum wellness module offers a simple framework for monitoring recovery and emotional well-being after childbirth.

---
