# 🩺 An Integrated Explainable AI System for PCOS Detection Using Clinical and Ultrasound Data

## 📌 Overview

Polycystic Ovary Syndrome (PCOS) is one of the most common endocrine disorders affecting women of reproductive age. Early diagnosis is challenging due to diverse symptoms and complex clinical manifestations.

This project presents an **Explainable Multi-Modal PCOS Detection System** that integrates:

- Clinical Data Analysis
- Ultrasound Image Classification
- Explainable AI (SHAP & Grad-CAM)
- Severity Scoring
- Infertility Risk Assessment
- Real-Time Web Deployment

The system combines Machine Learning and Deep Learning techniques to provide accurate, interpretable, and clinically meaningful predictions.

---

## 🎯 Objectives

- Predict PCOS using clinical and hormonal parameters.
- Detect PCOS from ovarian ultrasound images.
- Provide explainable predictions using SHAP and Grad-CAM.
- Assess PCOS severity through domain-wise scoring.
- Estimate infertility risk using clinical biomarkers.
- Deploy the solution as an interactive web application.

---

## 🗂️ Datasets Used

### 1. Clinical Dataset

**PCOS Dataset (Without Infertility)**

- Source: Kaggle
- Records: 541 Patients
- Features: 45 Clinical Attributes

Dataset Link:

https://www.kaggle.com/datasets/prasoonkottarathil/polycystic-ovary-syndrome-pcos

---

### 2. Ultrasound Dataset

**PCOS XAI Ultrasound Dataset**

- Source: Kaggle
- Images after preprocessing: 3,996

Dataset Link:

https://www.kaggle.com/datasets/ibadeus/pcos-xai-ultrasound-dataset

---

## 🔬 Methodology

### Clinical Prediction Pipeline

1. Data Cleaning
2. Missing Value Imputation (MICE)
3. Robust Scaling
4. Feature Engineering
5. Model Training
6. SHAP Explainability
7. Severity & Infertility Risk Assessment

#### Models Used

- Logistic Regression
- Random Forest
- Gradient Boosting
- CatBoost
- Stacked Ensemble (Final Model)

---

### Ultrasound Image Pipeline

1. Image Preprocessing
2. Data Augmentation
3. Transfer Learning
4. Model Evaluation
5. Grad-CAM Visualization

#### Models Evaluated

- ResNet50
- EfficientNetB0
- DenseNet121
- MobileNetV2

#### Final Selected Model

**DenseNet121**

Reason:

- Highest Validation AUC
- Highest MCC
- Superior Generalization Performance

---

## 🤖 Explainable AI

### SHAP (Clinical Model)

Used for:

- Global Feature Importance
- Local Prediction Explanation
- Clinical Interpretation

### Grad-CAM (Image Model)

Used for:

- Visual Explanation
- Model Attention Mapping
- Clinical Validation

---

## 📊 Model Performance

### Clinical Model

| Model | Accuracy |
|---------|---------|
| Logistic Regression | 89.9% |
| Random Forest | 91.7% |
| Gradient Boosting | 90.8% |
| CatBoost | 92.7% |
| Stacked Ensemble | 95.4% |

---

### Ultrasound Model

| Model | Accuracy | ROC-AUC |
|---------|---------|---------|
| ResNet50 | 98.00% | 99.99% |
| EfficientNetB0 | 98.83% | 99.93% |
| DenseNet121 | 98.83% | 99.94% |
| MobileNetV2 | 98.33% | 99.98% |

---

## ⚕️ Additional Features

### Severity Scoring

The system evaluates severity across:

- Reproductive Domain
- Metabolic Domain
- Androgenic Domain
- General Symptoms Domain

Severity Levels:

- Mild
- Moderate
- Severe

---

### Infertility Risk Assessment

Risk Categories:

- Low Risk
- Moderate Risk
- High Risk

Based on:

- Hormonal Indicators
- Ovulation Status
- Follicle Characteristics
- Menstrual Cycle Patterns

---

## 🚀 Deployment

### Clinical Prediction App

https://huggingface.co/spaces/DheivaCodes/PCOS_detection_clinical

### Ultrasound Detection App

https://huggingface.co/spaces/DheivaCodes/PCOS_Ultrasound_Image_Detection

### Integrated Multi-Modal System

https://huggingface.co/spaces/DheivaCodes/An_Integrated_System_For_PCOS_Detection

---

## 🛠️ Technologies Used

### Machine Learning

- Scikit-Learn
- CatBoost

### Deep Learning

- PyTorch
- TorchVision

### Explainable AI

- SHAP
- Grad-CAM

### Data Processing

- Pandas
- NumPy

### Visualization

- Matplotlib
- Seaborn

### Deployment

- Gradio
- Hugging Face Spaces

---

## 🌟 Key Contributions

- Multi-modal PCOS Detection Framework
- Clinical + Ultrasound Data Integration
- Explainable AI using SHAP and Grad-CAM
- Domain-wise Severity Scoring
- Infertility Risk Assessment
- Real-Time Deployment
- Clinician-Oriented Decision Support

---

## 🔮 Future Scope

- Multi-center Clinical Validation
- Federated Learning Framework
- Electronic Health Record Integration
- Mobile Application Development
- Fertility Outcome Prediction
- Real-Time Ultrasound Integration

---

## 👩‍💻 Author

**Dheiva Priya V**

B.Tech Artificial Intelligence and Data Science

Major Project

**An Integrated Explainable AI System for PCOS Detection Using Clinical and Ultrasound Data**

---

## 📜 License

This project is intended for academic and research purposes only.

Dataset copyrights belong to their respective owners.
