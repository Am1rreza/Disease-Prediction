# 🩺 Disease Prediction using Machine Learning

This project focuses on predicting diseases based on common symptoms using machine learning algorithms. It includes preprocessing, class balancing, model evaluation, and performance visualization.

---

## 📊 Dataset Overview

The dataset contains **2,000 patient records**, with 10 binary symptom indicators and a target label (`disease`):

| Symptom        | Type  |
|----------------|--------|
| fever          | 0 or 1 |
| headache       | 0 or 1 |
| nausea         | 0 or 1 |
| vomiting       | 0 or 1 |
| fatigue        | 0 or 1 |
| joint_pain     | 0 or 1 |
| skin_rash      | 0 or 1 |
| cough          | 0 or 1 |
| weight_loss    | 0 or 1 |
| yellow_eyes    | 0 or 1 |

- Target: `disease` (categorical)

---

## 🧠 Models Used

The following classification models are trained and evaluated using **Stratified K-Fold Cross-Validation (10-fold)**:

- ✅ **Support Vector Machine (SVM)**
- ✅ **Naive Bayes**
- ✅ **Random Forest**

---

## ⚙️ Key Techniques

- **Label Encoding**: To convert the disease label to numeric.
- **SMOTE Oversampling**: To handle imbalanced class distribution.
- **Cross-Validation**: For reliable model evaluation.
- **Confusion Matrix**: To visualize classification results.

---

## 📈 Results

Each model’s performance is evaluated based on **accuracy**:

- Mean accuracy scores printed in the output
- Confusion matrix plotted for SVM results

---
