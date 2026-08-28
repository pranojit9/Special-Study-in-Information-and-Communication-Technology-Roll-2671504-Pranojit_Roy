# 🧬 Disease Prediction with Logistic Regression and SVM

## 📌 Project Overview

This project focuses on **breast cancer disease prediction** using the **Breast Cancer Wisconsin (Diagnostic) Dataset**.

Two machine learning classification models are implemented and compared:

- 📊 Logistic Regression
- 🎯 Support Vector Machine (SVM)

The models are evaluated using **Accuracy, Precision, Recall/Sensitivity, and Specificity**.

---

## 🧬 Dataset

**Dataset:** Breast Cancer Wisconsin (Diagnostic)  
**Source:** Scikit-learn Built-in Dataset

- **Samples:** 569
- **Features:** 30 numerical features
- **Classification:** Binary Classification
- **0 → Benign**
- **1 → Malignant**

The features represent measurements calculated from digitized images of breast masses.

---

## ⚙️ Project Workflow

1. Load the medical dataset
2. Check missing values
3. Split data into training and testing sets
4. Apply `StandardScaler`
5. Train Logistic Regression
6. Train SVM with RBF kernel
7. Generate predictions
8. Visualize confusion matrices
9. Compare model performance

---

## 📊 Evaluation Metrics

- **Accuracy:** Overall percentage of correct predictions.
- **Precision:** Correctness of positive predictions.
- **Recall/Sensitivity:** Ability to detect actual disease cases.
- **Specificity:** Ability to correctly identify non-disease cases.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

---

## 🎯 Conclusion

This project demonstrates the use of **Logistic Regression and SVM** for breast cancer classification. The models are compared using multiple evaluation metrics.

The project can be extended toward **Federated AI for Healthcare**, where models can be trained across multiple hospitals while keeping patient data locally stored.

---

# 📝 Short Notes

## 1. Function of Scikit-learn Models

### Logistic Regression

1. Used for binary classification.
2. Predicts the probability of a class.
3. Suitable for disease prediction.
4. In this project, it predicts **Benign vs. Malignant**.

### SVM (Support Vector Machine)

1. Used for classification problems.
2. Finds an optimal decision boundary between classes.
3. RBF kernel can handle nonlinear data.
4. In this project, it classifies breast tumors.

---

## 2. Visualizing the Confusion Matrix

1. Shows correct and incorrect model predictions.
2. Contains **True Positive, True Negative, False Positive, and False Negative** values.
3. Helps identify false positive and false negative cases.
4. A heatmap makes the classification results easier to understand.

---

## 3. Evaluation Metrics (Model Evaluation)

1. **Accuracy** measures the overall percentage of correct predictions.
2. **Precision** measures the correctness of positive predictions.
3. **Recall/Sensitivity** measures the ability to detect actual disease cases.
4. **Specificity** measures the ability to correctly identify non-disease cases.

---

## 4. Linear Regression

1. Linear Regression is a supervised machine learning algorithm.
2. It is mainly used to predict continuous numerical values.
3. It models the relationship between input and output variables.
4. It is different from Logistic Regression, which is mainly used for classification.

---

## 5. SVM

1. SVM stands for **Support Vector Machine**.
2. It finds an optimal decision boundary between different classes.
3. The **RBF kernel** can handle nonlinear relationships in data.
4. In this project, SVM is used for **Benign and Malignant tumor classification**.
