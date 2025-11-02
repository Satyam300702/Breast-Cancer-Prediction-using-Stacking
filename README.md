🧠 Breast Cancer Prediction using Stacking Ensemble

This project predicts whether a breast tumor is malig
(non-cancerous) using the Breast Cancer Wisconsin Dat
The model uses an advanced Stacking Ensemble approach
LightGBM, and Random Forest to achieve high accuracy 

📌 Project Overview

Early and accurate breast cancer detection is crucial
This project applies multiple ensemble algorithms to 
Breast Cancer Wisconsin Dataset available in sklearn

Model Pipeline
🔹 Base Models

CatBoostClassifier — Handles categorical and numerica

XGBClassifier — Efficient gradient boosting with regu

LGBMClassifier — Lightweight and fast gradient boosti

🔹 Meta Model

RandomForestClassifier — Aggregates base model output

🔹 Training Setup

RandomizedSearchCV used for hyperparameter tuning.

ROC-AUC as the main scoring metric.

StackingClassifier combines base models with the meta

Cross-Validation (cv=5) ensures model generalization.

🧪 Model Performance
Metric	Score
Accuracy	0.9726
ROC-AUC	0.9447
Confusion Matrix	[[41, 2], [0, 71]]

✅ The model achieves high recall and precision, mini
medical diagnostics.
----------------------------------------------------------------------------------------------------------------------------------
git clone:- https://github.com/Satyam300702/Breast-Cancer-Prediction-using-Stacking
cd breast-cancer-ensemble

pip install -r requirements.txt

Live Demo:-