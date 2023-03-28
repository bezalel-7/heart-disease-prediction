# Predicting heart disease using machine learning

This notebook looks into using various Python-based machine learning and data science libraries in an attempt to build a machine learning model capable of predicting whether or not someone has heart disease based on their medical attributes.

## Approach

We're going to take the following approach:

1. Problem Definition
    - Given clinical parameters about a patient, can we predict whether or not they have heart disease?

2. Data
    - The original data came from the Cleavland data from the UCI Machine Learning Repository. [Link](https://archive.ics.uci.edu/ml/datasets/heart+Disease)
    - There is also a version of it available on Kaggle. [Link](https://www.kaggle.com/datasets/sumaiyatasmeem/heart-disease-classification-dataset)

3. Evaluation
    - If we can reach 95% accuracy at predicting whether or not a patient has heart disease during the proof of concept, we'll pursue the project.

4. Features
    - age - age in years
    - sex - (1 = male; 0 = female)
    - cp - chest pain type
        - 0: Typical angina: chest pain related decrease blood supply to the heart
        - 1: Atypical angina: chest pain not related to heart
        - 2: Non-anginal pain: typically esophageal spasms (non heart related)
        - 3: Asymptomatic: chest pain not showing signs of disease
    - trestbps - resting blood pressure (in mm Hg on admission to the hospital) anything above 130-140 is typically cause for concern
    - chol - serum cholestoral in mg/dl
        - serum = LDL + HDL + .2 * triglycerides
        - above 200 is cause for concern
    - fbs - (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
        - '>126' mg/dL signals diabetes
    - restecg - resting electrocardiographic results
        - 0: Nothing to note
        - 1: ST-T Wave abnormality can range from mild symptoms to severe problems signals non-normal heart beat
        - 2: Possible or definite left ventricular hypertrophy Enlarged heart's main pumping chamber
    - thalach - maximum heart rate achieved
    - exang - exercise induced angina (1 = yes; 0 = no)
    - oldpeak - ST depression induced by exercise relative to rest looks at stress of heart during excercise unhealthy heart will stress more
    - slope - the slope of the peak exercise ST segment
        - 0: Upsloping: better heart rate with excercise (uncommon)
        - 1: Flatsloping: minimal change (typical healthy heart)
        - 2: Downslopins: signs of unhealthy heart
    - ca - number of major vessels (0-3) colored by flourosopy
        - colored vessel means the doctor can see the blood passing through the more blood movement the better (no clots)
    - thal - thalium stress result
        - 1,3: normal
        - 6: fixed defect: used to be defect but ok now
        - 7: reversable defect: no proper blood movement when excercising
    - target - have disease or not (1=yes, 0=no) (= the predicted attribute)

## Modelling

The notebook contains the following sections:

* Data exploration and visualization
* Data preprocessing and cleaning
* Modelling using various machine learning algorithms such as Logistic Regression, K-Nearest Neighbors, Random Forest, and XGBoost.
* Model evaluation using metrics such as accuracy, precision, recall, F1 score, and ROC-AUC.

## Experimentation

We will be experimenting with different models, feature engineering, and hyperparameter tuning to improve the model's accuracy and predictive power.

## Conclusion

This project showcases how machine learning can be used to predict the presence of heart disease in patients using their medical attributes. By achieving high accuracy, the model can be used to assist healthcare professionals in making better-informed decisions regarding patient care.
