# Naïve Bayes Classifier on Diabetes.csv Dataset  

## Overview  
This experiment analyzes and implements the **Naïve Bayes Classifier** on the **Diabetes dataset (`diabetes.csv`)**. The model is evaluated based on classification accuracy and performance metrics.  

## Dataset  
The dataset contains medical records related to diabetes diagnosis, including features such as glucose level, insulin, BMI, and other health indicators.  

## Methodology  

### 1. Data Preprocessing  
- **Handling Missing Values:**  
  - Columns with missing values (e.g., `Glucose`, `BloodPressure`, `SkinThickness`, `Insulin`, `BMI`) are identified.  
  - Missing values are replaced using **mean imputation**.  

- **Feature Scaling:**  
  - Data is normalized using **StandardScaler** to improve classifier performance.  

### 2. Model Training  
- **Naïve Bayes Classifier** (`sklearn.naive_bayes`):  
  - **GaussianNB** is used for continuous numerical features.  
- The model is trained and evaluated using **cross-validation**.  

### 3. Evaluation Metrics  
- **Accuracy** – Measures the overall correctness of the classifier.  
- **Precision** – Measures the proportion of correctly predicted positive cases.  
- **Recall** – Measures the proportion of actual positives correctly identified.  
- **F1-Score** – A balance between precision and recall.  

## Results  
- The Naïve Bayes classifier successfully classifies instances from the diabetes dataset.  
- The model achieves **an average accuracy of approximately 75%** using cross-validation.  

## Implementation  
The implementation is done in **Python** using Jupyter Notebook, with the following libraries:  
- `pandas` and `numpy` for data handling  
- `sklearn.naive_bayes.GaussianNB` for Naïve Bayes classification  
- `sklearn.preprocessing.StandardScaler` for feature scaling  
- `sklearn.model_selection` for train-test split and cross-validation  
- `sklearn.metrics` for computing evaluation metrics  

## Reference  
This practical is based on the **Diabetes dataset (`diabetes.csv`)**, implementing Naïve Bayes classification.  

---

### Running the Code  
1. Load the dataset (`diabetes.csv`).  
2. Preprocess the data (handle missing values, normalize features).  
3. Train and evaluate the **Naïve Bayes Classifier**.  
4. Compute **accuracy, precision, recall, and F1-score**.  

This README provides a structured guide for implementing and analyzing the Naïve Bayes classifier in **Jupyter Notebook** or **Google Colab**. 🚀  

## Authors

- https://github.com/Pushpamehta2k1

