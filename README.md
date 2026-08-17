
# Machine Learning Framework for Urban Traffic Accident Risk Prediction

## Team Members
- Anjali Kasarla - 2420030170 - https://github.com/AnjaliKasarla/KLH-CSE-2026-2420030170-AccidentRiskPrediction
- Vinusha Muppala - 2420030212 - https://github.com/vinusha212/-KLH-CSE-2026-27-2420030212-Accidentriskprediction.git
- Lasya Geethika - 2420030678 - https://github.com/lasya-sys/KLH-CSE-2026-2420030686-AccidentRiskPrediction-

## Supervisor
Dr. Katanguri Swanthana (CSE)

## Abstract
This project develops a Machine Learning framework for predicting urban traffic accident risk using traffic, weather, road, and accident-related information. The system uses ML and NLP techniques to classify situations into Low, Medium, and High risk levels. SHAP/LIME are used for explainable predictions, with a web dashboard for visualization and proactive traffic safety decisions.

## Technologies Used
Python, Scikit-learn, NLP, SHAP, LIME, Pandas, NumPy, Matplotlib, Seaborn, Streamlit, Jupyter Notebook

## Methodology
Data Collection → Data Preprocessing → NLP Analysis → ML Model Training → Risk Classification → SHAP/LIME Explanation → Dashboard → Testing & Evaluation

## Machine Learning Models
Logistic Regression, Decision Tree, Random Forest, Support Vector Machine (SVM)

## Evaluation Metrics
Accuracy, Precision, Recall, F1-Score, ROC-AUC, Confusion Matrix

## Risk Classification
- Low Risk
- Medium Risk
- High Risk

## Repository Structure
/src
/docs
/data
/results
/reports
README.md

## Setup & Execution
```bash
git clone https://github.com/AnjaliKasarla/KLH-CSE-2026-2420030170-AccidentRiskPrediction.git
cd KLH-CSE-2026-2420030170-AccidentRiskPrediction
pip install -r requirements.txt
streamlit run src/app.py
