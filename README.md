# Predicting Hospital Readmission
#### Problem Statement:
The primary goal of the project is to build a predictive model that can identify patients who are at high risk of hospital readmission within 30 days after the initial discharge. This predictive model will assist healthcare providers in proactively intervening and providing targeted interventions to reduce readmission rates and improve patient outcomes.
#### Business Use case:
To identify the patient who are at high risk which need special care.
#### Solution Steps:
1. Data Preprocessing: This task involves cleaning and preparing the healthcare data.
You'll need to handle missing values, perform data normalization or scaling, and deal with
categorical variables.
2. Feature Engineering: Create relevant features that can be used for predictive modeling.
This may involve extracting patient demographics, medical history, previous hospitalizations,
and other relevant information.
3. Model Building: Develop a machine learning or statistical model that can predict the
likelihood of hospital readmission within 30 days. Common approaches include logistic
regression, decision trees, random forests, or more advanced models like gradient boosting or
neural networks.
4. Model Evaluation: Assess the performance of the predictive model using appropriate
evaluation metrics such as accuracy, precision, recall, F1-score, ROC curve, and AUC (Area
Under the Curve).
#### Data Description:
* Patient_ID: Unique identifier for each patient.
* Age: Age of the patient in years.
* Gender: Gender of the patient (e.g., Male, Female, Other).
* Admission_Type: Type of admission (e.g., Emergency, Urgent, Elective).
* Diagnosis: Primary diagnosis of the patient upon admission (e.g., Heart Disease, Diabetes, Injury, Infection).
* Num_Lab_Procedures: Number of laboratory procedures performed during the hospital stay.
* Num_Medications: Number of medications prescribed to the patient.
* Num_Outpatient_Visits: Number of outpatient visits prior to the current hospital admission.
* Num_Inpatient_Visits: Number of inpatient visits prior to the current hospital admission.
* Num_Emergency_Visits: Number of emergency room visits prior to the current hospital admission.
* Num_Diagnoses: Number of diagnoses.
* A1C_Result: Result of the A1C test, if available (e.g., Normal, Abnormal).
* Readmitted: Indicates whether the patient was readmitted to the hospital within a certain time frame (e.g., Yes, No).
* service_utilization: Indicates how many time the patient visits  the hospital in a 30 days.
#### Challenge
One specific challenge encountered in this project was the presence of many null values in the A1C_Result column. To address this, a classification model was developed to predict and fill in the missing values in the A1C_Result column based on other available features. Once the missing values were imputed, a predictive model for hospital readmission status was built using the completed dataset.
#### Technologies used:
* Pandas
* Numpy
* Seaborn
* Data Preprocessing
* Data Engineering
* Model Training
* Model Evaluation
