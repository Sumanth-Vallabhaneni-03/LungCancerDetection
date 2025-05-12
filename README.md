# 🫁 Lung Cancer Detection using Machine Learning

> A predictive analytics project for early lung cancer classification using logistic regression.
> This project presents a machine learning approach to detecting lung cancer using a dataset of patient features. The goal is to develop a predictive model that can assist in early diagnosis of lung cancer, thereby contributing to better patient outcomes.

## 📌 Overview

Lung cancer remains one of the deadliest diseases globally, and early detection is critical for improving patient survival rates. This project leverages **machine learning**—specifically **Logistic Regression**—to predict lung cancer based on patient symptoms and lifestyle features. By analyzing risk factors, the model aims to support proactive diagnosis and medical intervention.

**Documentation** : [Lung Cancer Detection](https://www.dropbox.com/scl/fi/hfo7qwd4yjj1vhxvdzevu/LungCancerDetection.pdf?rlkey=dbqtq7zicaw92m6wqp8sx9y0s&st=wh77t006&dl=0)

## 🎯 Objectives

- Build a binary classification model to detect the presence of lung cancer.
- Preprocess and balance imbalanced medical data.
- Evaluate the model using robust performance metrics.
- Visualize features contributing to lung cancer risk.

## 📊 Features Used

Some of the key features used in this project include:

- Age
- Gender
- Smoking
- Anxiety
- Peer Pressure
- Chronic Disease
- Fatigue
- Allergy
- Wheezing
- Alcohol Consumption
- Coughing
- Shortness of Breath
- Swallowing Difficulty
- Chest Pain

---
## 🧠 Methodology

### 📥 1. Data Collection
- **Source**: Online lung cancer prediction dataset.
- **Samples**: 284 patients
- **Features (16 total)**:
  - Gender, Age, Smoking, Yellow Fingers, Anxiety, Peer Pressure, Chronic Disease, Fatigue, Allergy, Wheezing, Alcohol, Coughing, Shortness of Breath, Swallowing Difficulty, Chest Pain
  - **Target**: `LUNG_CANCER` (Yes = 1, No = 0)

### 🧹 2. Data Preprocessing
- Removed duplicate records
- Applied **undersampling** to address class imbalance:
  - Before: 270 (Yes), 39 (No)
  - After: Balanced subset created for training

### 📊 3. Visualization
- Histograms comparing smokers and non-smokers by cancer status
- Heatmap of feature correlations
- Bar plots for symptom frequency by cancer diagnosis

### ⚙️ 4. Algorithm Used
- **Logistic Regression**
  - Used for binary classification
  - Outputs probability scores using the sigmoid function
  - Evaluated on multiple metrics

---

## 📈 Results

- The best-performing model achieved an accuracy of approximately **[insert accuracy here]%**.
- Confusion matrix and classification reports demonstrate the model's ability to distinguish between cancer-positive and negative cases.

## 📁 Project Structure


lung\_cancer\_detection/
├── lung\_cancer\_detection.ipynb
├── README.md
├── requirements.txt (optional)
└── data/ (if applicable)



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
- **Root Mean Squared Error (RMSE)**: 0.1796  
- **Mean Absolute Error (MAE)**: 0.0322  
- **R² Score**: 0.0333  

---

## ✅ Requirements

To run this notebook, install the following Python packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
````

## 🚀 Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/Sumanth-Vallabhaneni-03/LungCancerDetection.git
   cd lung_cancer_detection
   ```

2. Open the notebook in Jupyter:

   ```bash
   jupyter notebook lung_cancer_detection.ipynb
   ```

## 📌 Future Work

* Integration of deep learning models (e.g., neural networks)
* Deployment as a web app
* Real-time prediction API

## 🧑‍💻 Author

* [Sumanth Vallbhaneni(https://github.com/Sumanth-Vallabhaneni-03)









