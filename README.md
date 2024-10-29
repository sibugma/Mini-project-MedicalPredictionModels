# Mini-project-MedicalPredictionModels
1. Tumor Classification

File: tumor_classification.py

This script predicts the likelihood of a tumor being benign or malignant based on its size and the patient’s age. It uses the following models:

    Logistic Regression
    K-Nearest Neighbors (KNeighborsClassifier)
    KMeans Clustering

User Input:

    Tumor size (integer)
    Patient age (integer)

Output: The script outputs predictions from each model (0: benign, 1: malignant).
2. Patient Risk Assessment

File: patient_risk_assessment.py

This script predicts the risk of a patient developing a particular condition based on various health metrics. The models used include:

    Logistic Regression
    Decision Tree Classifier
    K-Nearest Neighbors (KNeighborsClassifier)

User Input:

    Patient age (integer)
    Gender (0 for male, 1 for female)
    Race (encoded as 0, 1, or 2)
    BMI (integer)
    Max Blood Pressure (integer)
    Min Blood Pressure (integer)
    Cholesterol level (integer)
    Blood sugar before eating (integer)
    Blood sugar after eating (integer)

Output: The script outputs a prediction from each model (0: low risk, 1: high risk).
3. Smoking and Health Risk Prediction

File: smoking_health_risk.py

This script predicts the likelihood of a health issue based on gender, age, and smoking status. The models used in this script are:

    Logistic Regression
    Decision Tree Classifier
    K-Nearest Neighbors (KNeighborsClassifier)

User Input:

    Gender (0 for male, 1 for female)
    Age of patient (integer)
    Smoking status (0: non-smoker, 1: smoker)

Output: The script outputs predictions from each model (0: low risk, 1: high risk).
Usage

    Run each file in a terminal or an IDE.
    Follow the on-screen prompts to enter the required data.
    View the predicted outputs for each model displayed in the console.
