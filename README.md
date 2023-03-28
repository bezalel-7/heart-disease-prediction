Predicting Heart Disease using Machine Learning
This project is aimed at building a machine learning model that can predict whether or not a patient has heart disease based on their medical attributes. The model is built using various Python-based machine learning and data science libraries.

Problem Definition
Given clinical parameters about a patient, can we predict whether or not they have heart disease?

Data
The original data used for this project was obtained from the Cleavland data from the UCI Machine Learning Repository, and can also be found on Kaggle. The dataset contains 14 columns, with each column representing a medical attribute of the patient.

Evaluation
The goal of this project is to achieve a prediction accuracy of at least 95%.

Features
Here is a description of the features in the dataset:

age: Age of the patient in years
sex: Gender of the patient (1 = male, 0 = female)
cp: Type of chest pain experienced by the patient (0 = typical angina, 1 = atypical angina, 2 = non-anginal pain, 3 = asymptomatic)
trestbps: Resting blood pressure of the patient (in mm Hg on admission to the hospital)
chol: Serum cholesterol level of the patient in mg/dl
fbs: Fasting blood sugar level of the patient (> 120 mg/dl) (1 = true; 0 = false)
restecg: Resting electrocardiographic results (0 = normal, 1 = ST-T wave abnormality, 2 = possible or definite left ventricular hypertrophy)
thalach: Maximum heart rate achieved during exercise
exang: Exercise-induced angina (1 = yes; 0 = no)
oldpeak: ST depression induced by exercise relative to rest
slope: Slope of the peak exercise ST segment (0 = upsloping, 1 = flatsloping, 2 = downsloping)
ca: Number of major vessels colored by fluoroscopy (0-3)
thal: Thallium stress result (1, 3 = normal, 6 = fixed defect, 7 = reversible defect)
target: Presence of heart disease in the patient (1 = yes, 0 = no)
Modelling
The notebook contains the following sections:

Data exploration and visualization
Data preprocessing and cleaning
Modelling using various machine learning algorithms such as Logistic Regression, K-Nearest Neighbors, Random Forest, and XGBoost.
Model evaluation using metrics such as accuracy, precision, recall, F1 score, and ROC-AUC.
Experimentation
We will be experimenting with different models, feature engineering, and hyperparameter tuning to improve the model's accuracy and predictive power.

Conclusion
This project showcases how machine learning can be used to predict the presence of heart disease in patients using their medical attributes. By achieving high accuracy, the model can be used to assist healthcare professionals in making better-informed decisions regarding patient care.
