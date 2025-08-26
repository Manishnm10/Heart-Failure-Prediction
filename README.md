# Heart-Failure-Prediction
Predict a heart attack in a human being using ML.

Overview:
This project aims to predict whether a patient is prone to heart failure using machine learning techniques. It is a binary classification problem based on a dataset containing various numerical and categorical features related to cardiovascular health. The dataset is sourced from publicly available medical data and focuses on early detection to aid in managing cardiovascular diseases (CVDs), which are a leading cause of global mortality.
The analysis is performed in a Jupyter Notebook (heart.ipynb), where data exploration, preprocessing, model training, and evaluation are demonstrated. Logistic Regression is used as the primary model, achieving solid performance metrics.

Dataset:
The dataset (heart.csv) contains 918 entries with 12 attributes. It includes patient information such as age, sex, chest pain type, and other clinical metrics, with the target variable being HeartDisease (1: heart disease, 0: normal).

The dataset is loaded and explored in the notebook.
Features:
Age: Age of the patient (years)
Sex: Sex of the patient (M: Male, F: Female)
ChestPainType: Chest pain type (TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic)
RestingBP: Resting blood pressure (mm Hg)
Cholesterol: Serum cholesterol (mm/dl)
FastingBS: Fasting blood sugar (1: if >120 mg/dl, 0: otherwise)
RestingECG: Resting electrocardiogram results (Normal, ST: ST-T wave abnormality, LVH: Left ventricular hypertrophy)
MaxHR: Maximum heart rate achieved (60-202)
ExerciseAngina: Exercise-induced angina (Y: Yes, N: No)
Oldpeak: ST depression induced by exercise relative to rest
ST_Slope: Slope of the peak exercise ST segment (Up: upsloping, Flat: flat, Down: downsloping)
HeartDisease: Target class (1: heart disease, 0: normal)
