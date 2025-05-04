# 🫁 Lung Cancer Detection using Machine Learning

> A predictive analytics project for early lung cancer classification using logistic regression.

## 📌 Overview

Lung cancer remains one of the deadliest diseases globally, and early detection is critical for improving patient survival rates. This project leverages **machine learning**—specifically **Logistic Regression**—to predict lung cancer based on patient symptoms and lifestyle features. By analyzing risk factors, the model aims to support proactive diagnosis and medical intervention.

**Documentation** : [Lung Cancer Detection](https://www.dropbox.com/scl/fi/hfo7qwd4yjj1vhxvdzevu/LungCancerDetection.pdf?rlkey=dbqtq7zicaw92m6wqp8sx9y0s&st=wh77t006&dl=0)

## 🎯 Objectives

- Build a binary classification model to detect the presence of lung cancer.
- Preprocess and balance imbalanced medical data.
- Evaluate the model using robust performance metrics.
- Visualize features contributing to lung cancer risk.


## 🧠 Methodology

### 📥 1. Data Collection
- **Source**: Online lung cancer prediction dataset.
- **Samples**: 284 patients
- **Features (16 total)**:
  - Gender, Age, Smoking, Yellow Fingers, Anxiety, Peer Pressure, Chronic Disease, Fatigue, Allergy, Wheezing, Alcohol, Coughing, Shortness of Breath, Swallowing Difficulty, Chest Pain
  - **Target**: `LUNG_CANCER` (Yes = 1, No = 0)

### 🧹 2. Data Preprocessing
- Removal of duplicates
- Undersampling applied due to class imbalance:
  - Original: 270 (Yes), 39 (No)
  - Post-processing: Balanced samples

### 📊 3. Visualization
- Histograms comparing smokers and non-smokers by cancer status
- Feature correlation heatmaps and symptom trends

### ⚙️ 4. Algorithm Used
- **Logistic Regression**:
  - Binary classification
  - Outputs probabilities using sigmoid function

## 🧪 Model Evaluation

### ✅ Classification Report

| Metric       | Class 1 (Cancer) |
|--------------|------------------|
| Precision    | 0.97             |
| Recall       | 1.00             |
| F1-Score     | 0.98             |
| Accuracy     | **96.77%**       |

### 📈 Regression Metrics

- **Mean Squared Error (MSE)**: 0.0322  
- **Root MSE**: 0.1796  
- **Mean Absolute Error (MAE)**: 0.0322  
- **R² Score**: 0.0333  
