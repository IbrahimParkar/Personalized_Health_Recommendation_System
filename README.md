# Personalized Health Recommendation System

This repository contains the code and data for the Personalized Health Recommendation System project. The project aims to develop a health website capable of harnessing individual health data to generate personalized health recommendations, fostering early detection and more effective management of health issues. The system leverages various Machine Learning (ML) algorithms to predict diseases like arrhythmia, sleep apnea, insomnia, and stroke.

## Disease Prediction Performance Metrics

### Heart Arrhythmia
- **Model:** Random Forest
  - Precision: 1
  - Recall: 1
  - F1 Score: 1
  - Accuracy: 1
  - balanced_accuracy: 1
  - auc: 1

### Sleep Apnea and Insomnia
- **Model:** Support Vector Machine
  - Precision: 88.98
  - Recall: 89.28
  - F1 Score: 88.7
  - Accuracy: 89.2
  - Balanced AUC: 78.3
  - AUC: 88.92

### Stroke
- **Models:** 
  - **Random Forest Classifier**
    - Precision: 93.81
    - Recall: 93.99
    - F1 Score: 92.14
    - Accuracy: 95.90
    - Balanced AUC: 93.79
    - AUC: 93.99
      
  - **Decision Trees**
    - Precision: 95.18
    - Recall: 95.20
    - F1 Score: 95.74
    - Accuracy: 94.67
    - Balanced AUC: 95.19
    - AUC: 94.67
      
  - **Voting Classifier**
    - Precision: 95.67
    - Recall: 95.71
    - F1 Score: 95.67
    - Accuracy: 95.75
    - Balanced AUC: 95.67
    - AUC: 95.67

## Usage

1. **Arrhythmia Prediction:**
   - The prediction model for arrhythmia uses Random Forest.
   - Navigate to the `arrhythmia` folder to access the code and data. The code includes preprocessing, model training, and implementation.

2. **Sleep Apnea Prediction:**
   - The prediction model for sleep apnea uses a Support Vector Machine.
   - Navigate to the `sleep_apnea` folder to access the code and data. The code includes preprocessing, model training, and implementation.

3. **Stroke Prediction:**
   - The prediction models for stroke include a Random Forest Classifier, Decision Tree, and Voting Classifier.
   - Navigate to the `stroke` folder to access the code and data. The code includes preprocessing, model training, and implementation.

4. **Website Interaction:**
    - Navigate to the project directory in your terminal or command prompt.
    - Run `python app.py` to start the Flask server locally.
    - Open your web browser and go to `http://127.0.0.1:5000` or `http://localhost:5000` to access the application.
    - Create a detailed health profile by filling out the provided form with personal health information, demographics, medical history, and lifestyle factors.
    - Upload health-related data obtained from smart devices, such as physiological measurements like heart rate, blood pressure, and activity levels.
    - Receive personalized health predictions and recommendations based on the submitted health profile and uploaded data.
    - Get suggestions for nearby healthcare facilities where you can seek further evaluation and treatment based on the predicted health conditions.
