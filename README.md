# Development of a Web-Based System for Prediction of Cardiovascular Disease Using Machine Learning

## Objective
To simulate a cardiovascular disease risk prediction system using machine learning (XGBoost) integrated into a user-friendly web interface to support clinical and preventive decision-making.

## Simulation Type
Health Risk Prediction / Clinical Decision Support Simulation

## Types of Dataset
1. Structured clinical data (age
2. gender
3. cholesterol
4. glucose
5. blood pressure
6. smoking status
7. BMI
8. etc.)
9. medical history

## Possible Sources for Dataset
1. UCI Machine Learning Repository
2. Kaggle CVD Datasets
3. WHO Global Health Observatory
4. PhysioNet

## Dataset URLs
1. https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset
2. https://archive.ics.uci.edu/ml/datasets/heart+disease
3. https://physionet.org/

## Setup Instructions
1. 1. Import CVD dataset and explore variable distribution
2. 2. Clean and preprocess (handle missing values, encode categorical features, scale numerical data)
3. 3. Train an XGBoost classifier with hyperparameter tuning
4. 4. Evaluate model using AUC, accuracy, precision, recall, F1-score
5. 5. Build a web app using Flask or Streamlit to input patient data and return prediction
6. 6. Display prediction results with visualisations (e.g., risk bar, probability pie chart)

## Implementation Guide
1. 1. User-friendly web form for clinical data input
2. 2. Real-time risk score prediction (low/medium/high)
3. 3. Visual summary of contributing factors (feature importance)
4. 4. Classification metrics and confusion matrix
5. 5. Downloadable risk report or visual output

## Expected Output(s)
1. Predictive classification of cardiovascular risk; display of ML interpretability (feature importance); accessibility to non-specialists via UI; improved clinical insight for early intervention

## Background Studies
### Machine Learning in Healthcare
Application of supervised learning (XGBoost, Gradient Boosting) in predicting CVD.

### Clinical Risk Modelling
Understanding the limitations of traditional models like Framingham Risk Score.

### Feature Engineering
Importance of preprocessing health-related structured datasets.

### Model Evaluation
Using classification metrics including confusion matrix, ROC-AUC for healthcare models.

### Deployment
Translating machine learning models to a usable web application interface.

### Privacy Considerations
Ensuring patient confidentiality and data protection.

### Usability Studies
Designing simulations that can be accessed in low-resource settings for preventive diagnosis.

### Interpretability
Using SHAP or feature importance to explain predictions to users.
