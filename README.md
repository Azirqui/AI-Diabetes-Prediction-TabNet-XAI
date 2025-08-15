# 📊 AI-Driven Diabetes Prediction with TabNet and Explainable AI

## Repository Name Suggestion: `AI-Diabetes-Prediction-TabNet-XAI`

## README.md

## 🚀 Overview

[cite_start]Diabetes is a significant global health challenge, leading to serious complications like heart disease, kidney failure, and hypertension[cite: 7]. [cite_start]Early and reliable prediction is critical for timely intervention[cite: 8]. [cite_start]This project utilizes TabNet, an advanced deep learning model, to predict 13 types of diabetes using a dataset with 33 clinical and lifestyle features[cite: 8]. [cite_start]The model achieves an accuracy of 88.5% [cite: 9] [cite_start]and integrates explainable AI techniques such as SHAP and LIME to uncover feature importance and ensure transparency[cite: 9]. [cite_start]By combining accuracy with interpretability, this approach offers a powerful solution for enhancing automated healthcare systems and improving patient outcomes[cite: 10].

## ✨ Features

* **13-Type Diabetes Prediction:** Capable of predicting 13 distinct types of diabetes.
* **High Accuracy:** Achieves a test accuracy of 88.50%
* **TabNet Model:** Employs TabNet for robust and effective predictive modeling.
* **Explainable AI (XAI):** Integrates SHAP and LIME to interpret model predictions and identify feature importance, ensuring transparency and trustworthiness.
* **Missing Data Handling:** Utilizes GAIN for imputation to address missing data.
* **Comprehensive Data Preprocessing:** Includes imputation, encoding, scaling, and SMOTE for data preparation.
* **Feedback Loop:** Designed for continuous improvement with new data.

## 💡 Methodology

The methodology involves several key stages, as depicted in the workflow:

1.  **Data Preprocessing:**
    * Imputation 
    * Encoding 
    * Scaling 
    * SMOTE (for handling imbalanced datasets)
2.  **Feature Engineering:**
    * Selecting features 
    * Extracting features 
3.  **Model Training & Selection:**
    * Training the TabNet model
    * Selecting the optimal model 
    * Evaluating the model
4.  **Explainable AI (XAI) Analysis:**
    * SHAP (SHapley Additive exPlanations) for understanding feature contribution
    * Summary plots for visualization 
5.  **Prediction & Feedback:**
    * Making predictions 
    * Incorporating feedback with new data to improve the model 

## 📊 Results

The model demonstrates strong performance:

* **Validation Accuracy:** 88.33% 
* **Test Accuracy:** 88.50% 
* **Top Identified Features:** Family history, BMI, and genetic markers were identified as key features influencing predictions

### Performance Metrics (Partial)

| Class | Recall | Precision | F1-Score |
| :---- | :----- | :-------- | :------- |
| 01    | 0.91   | 0.97      | 0.94     |
| 02    | 0.88   | 0.88      | 0.88     |
| 03    | 0.89   | 0.96      | 0.92     |
| 04    | 0.92   | 0.85      | 0.89     |

* Class 01 shows the highest performance (Precision = 0.97, F1-score = 0.94).
* Class 04 has a slightly lower recall (0.85), suggesting that some instances of this class are missed.
* Overall, the balanced performance across classes indicates the robustness of the model.

### Confusion Matrix

The confusion matrix shows the performance of our model across all classes. Each row represents the true label, and each column represents the predicted label. High diagonal values indicate correct predictions, while off-diagonal values highlight misclassifications. It helps evaluate model performance by showing true versus predicted classifications.

*(You would typically embed an image of your confusion matrix here, e.g., `![Confusion Matrix](path/to/confusion_matrix.png)`)*

## 🛠️ Technologies and Tools

* Python
* TabNet
* SHAP [cite: 70]
* LIME
* pandas [cite: 75]
* scikit-learn (`sklearn`) [cite: 74]
* matplotlib [cite: 69]

## 🎯 Objective

To develop a robust, interpretable, and accurate prediction model for 13 types of diabetes, utilizing TabNet, GAIN for handling missing data, and SHAP/LIME for explainability.

## 🧑‍💻 Researched By

* Ch. Noman Ahmad

## 👨‍🏫 Supervised By

* Mr. Nouman Shafi 

## 🎓 Affiliation

Department of Computer Science , University of Engineering and Technology (UET) Lahore