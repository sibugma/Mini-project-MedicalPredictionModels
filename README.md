# README
#Mini-project-MedicalPredictionModels

This repository contains three Python scripts that use different machine learning algorithms to make predictions based on medical data. Each script imports relevant libraries, collects user input, and uses various classifiers to predict outcomes based on training data. 

## Requirements
- Python 3.x
- Libraries: `numpy`, `sklearn`

Install requirements using:
```bash
pip install numpy scikit-learn
```

## File Descriptions

### 1. Tumor Classification
**File:** `tumor_classification.py`

This script predicts the likelihood of a tumor being benign or malignant based on its size and the patient’s age. It uses the following models:
1. **Logistic Regression**
2. **K-Nearest Neighbors (KNeighborsClassifier)**
3. **KMeans Clustering**

**User Input:**
- Tumor size (integer)
- Patient age (integer)

**Output:** The script outputs predictions from each model (0: benign, 1: malignant).

### 2. Patient Risk Assessment
**File:** `patient_risk_assessment.py`

This script predicts the risk of a patient developing a particular condition based on various health metrics. The models used include:
1. **Logistic Regression**
2. **Decision Tree Classifier**
3. **K-Nearest Neighbors (KNeighborsClassifier)**

**User Input:**
- Patient age (integer)
- Gender (0 for male, 1 for female)
- Race (encoded as 0, 1, or 2)
- BMI (integer)
- Max Blood Pressure (integer)
- Min Blood Pressure (integer)
- Cholesterol level (integer)
- Blood sugar before eating (integer)
- Blood sugar after eating (integer)

**Output:** The script outputs a prediction from each model (0: low risk, 1: high risk).

### 3. Smoking and Health Risk Prediction
**File:** `smoking_health_risk.py`

This script predicts the likelihood of a health issue based on gender, age, and smoking status. The models used in this script are:
1. **Logistic Regression**
2. **Decision Tree Classifier**
3. **K-Nearest Neighbors (KNeighborsClassifier)**

**User Input:**
- Gender (0 for male, 1 for female)
- Age of patient (integer)
- Smoking status (0: non-smoker, 1: smoker)

**Output:** The script outputs predictions from each model (0: low risk, 1: high risk).

## Usage
1. Run each file in a terminal or an IDE.
2. Follow the on-screen prompts to enter the required data.
3. View the predicted outputs for each model displayed in the console.

