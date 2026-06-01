# Heart-Disease-Prediction-ML
Heart Disease Prediction using Machine Learning - Pluto Academy AI &amp; ML Internship Project
# Heart Disease Prediction Using Machine Learning

## Project Overview

This project was developed as part of the Pluto Academy AI & ML Internship Program.

The objective of this project is to predict whether a patient has heart disease based on medical attributes using Machine Learning algorithms and compare their performance.
If the github file is not opening, do refer to this google colab link:
https://colab.research.google.com/drive/1zN41c5yDSX7hO64JVrCwSEbtluxXaTMc?usp=sharing
---

## Dataset

Heart Disease Prediction Dataset (Kaggle)

Dataset Link:
https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset

The dataset contains medical attributes such as age, sex, chest pain type, cholesterol level, resting blood pressure, maximum heart rate achieved, exercise-induced angina, and other health-related parameters used to predict the presence of heart disease.

Target Variable:

* 0 = No Heart Disease
* 1 = Heart Disease

---

## Data Preprocessing

The following preprocessing steps were performed:

* Checked dataset structure and statistical summary
* Verified missing values
* Removed 723 duplicate records
* Performed correlation analysis
* Selected important features
* Split data into training and testing sets (80:20)
* Applied feature scaling using StandardScaler

---

## Machine Learning Models Used

1. Logistic Regression
2. Random Forest Classifier
3. K-Nearest Neighbors (KNN)

---

## Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score

---

## Results

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 85%      |
| Random Forest       | 85%      |
| KNN                 | 84%      |

### Best Model

Logistic Regression achieved the best overall performance with the highest F1-score and balanced Precision and Recall values.

---

## Visualizations

* Correlation Heatmap
* Feature Importance Analysis
* Confusion Matrix
* Classification Reports

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Google Colab

---

## Author

Monika

Pluto Academy AI & ML Internship Project
