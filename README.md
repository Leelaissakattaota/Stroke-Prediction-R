# 🧠 Stroke Risk Prediction: Machine Learning with R
<p align="left">
  <img src="https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white" />
  <img src="https://img.shields.io/badge/Machine%20Learning-F7931E?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Random%20Forest-005963?style=for-the-badge" />
</p>

---

## 📝 Project Overview
Stroke is the **2nd leading cause of death globally**, responsible for approximately 11% of total deaths according to the WHO. This project uses a medical dataset to build a predictive model that identifies whether a patient is likely to experience a stroke based on parameters like **age, gender, BMI, and smoking status.**

## 👤 Author Information
- **Name:** Leela  
- **GitHub:** [leelaissakattaota](https://github.com/leelaissakattaota)
- **Email:** attotaleelaissak@gmail.com
- **Date:** February 01, 2026

---

## 🛠️ Technical Workflow

### 1️⃣ Data Preprocessing
- **Cleaning:** Removed irrelevant columns (ID) and handled missing BMI values using `na.omit`.
- **Transformation:** Converted character-based health data into **Factors** (Categorical variables) so the algorithm can interpret them correctly.

### 2️⃣ Handling Imbalanced Data
Medical datasets often have very few "Positive" cases. I implemented the **ROSE (Random Over-Sampling Examples)** package to balance the training data, ensuring the model doesn't ignore stroke risks.



### 3️⃣ Model Architecture: Random Forest
I utilized the **Random Forest** algorithm with **100 trees**. This ensemble method provides high stability and accuracy by combining multiple decision trees.



---

## 📊 Performance Metrics
After testing the model on a 20% hold-out test set, the results were as follows:

| Metric | Result |
| :--- | :--- |
| **OOB Error Rate** | 14.03% |
| **Training Accuracy** | ~86% |
| **Status** | Successfully Validated & Saved |

---

## 📂 Repository Contents
- 📄 `Build-deploy-stroke-prediction-model-R.Rmd`: The complete source script.
- 🌐 `Build-deploy-stroke-prediction-model-R.html`: Interactive project report.
- 📦 `stroke_prediction_model.rds`: The exported, ready-to-deploy model.
- 📊 `healthcare-dataset-stroke-data.csv`: The raw dataset used.

---

## 🚀 How to Run
1. Clone the repository.
2. Ensure R packages `tidyverse`, `caret`, `randomForest`, and `ROSE` are installed.
3. Open the `.Rmd` file in RStudio and click **Knit**.

---
<p align="center">
  <i>Project completed as part of a Data Science portfolio.</i>
</p>
