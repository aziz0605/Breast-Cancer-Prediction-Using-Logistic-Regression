# 🎗️ Breast Cancer Prediction Using Logistic Regression

## 📌 Project Overview

This project focuses on predicting breast cancer conditions using Machine Learning techniques.

A Logistic Regression classification algorithm is used to classify breast cancer cases into two categories: Malignant (Cancer) and Benign (Non-Cancer).

The project uses the Breast Cancer Wisconsin Dataset available in Scikit-learn and evaluates the model using accuracy, confusion matrix, and classification report.

## 🎯 Project Objectives

- Load and understand the Breast Cancer dataset.
- Perform dataset analysis and statistical summary.
- Check missing values and duplicate records.
- Split the dataset into training and testing sets.
- Build a Logistic Regression classification model.
- Predict breast cancer conditions.
- Evaluate model performance using different metrics.
- Visualize the confusion matrix using a heatmap.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

## 📂 Dataset Description

This project uses the built-in Breast Cancer Wisconsin Dataset from Scikit-learn.

**Dataset Information:**
- Total Samples: 569
- Total Features: 30
- Target Classes: 2

**Target Variable:**
- 0 – Malignant
- 1 – Benign

The dataset contains features related to cell nucleus characteristics, such as:

- Mean Radius
- Mean Texture
- Mean Perimeter
- Mean Area
- Mean Smoothness
- Mean Compactness
- Mean Concavity
- Mean Symmetry

## ⚙️ Project Workflow

### 1. Dataset Loading
Load the Breast Cancer dataset using Scikit-learn and convert it into a Pandas DataFrame.

### 2. Data Preparation
Perform basic dataset analysis:

- Check dataset shape.
- Check missing values.
- Identify column data types.
- Check duplicate records.
- Generate statistical summaries.

### 3. Data Splitting
Split the dataset into training and testing sets.

- Training Data: 80%
- Testing Data: 20%
- Random State: 42

### 4. Model Training

Build a Logistic Regression classification model using Scikit-learn.

**Algorithm:** Logistic Regression

### 5. Prediction

Use the trained Logistic Regression model to predict the target classes for the test dataset.

### 6. Model Evaluation

Evaluate model performance using:

- Accuracy Score
- Confusion Matrix
- Precision
- Recall
- F1-Score
- Classification Report

### 7. Data Visualization

Visualize the confusion matrix using a Seaborn heatmap to understand the model's prediction performance.
<img width="501" height="393" alt="image" src="https://github.com/user-attachments/assets/308c3f3f-2ee8-4bb0-8dde-d40ab3e71286" />

## 📊 Model Performance

The Logistic Regression model achieved the following result in the current notebook:

| Evaluation Metric | Result |
|---|---:|
| Accuracy | 95.61% |
| Weighted Precision | 0.96 |
| Weighted Recall | 0.96 |
| Weighted F1-Score | 0.96 |

**Confusion Matrix:**

```text
[[39  4]
 [ 1 70]]
```

## 📈 Visualizations

### 1. Confusion Matrix - Heatmap

A heatmap visualization of the confusion matrix showing the actual and predicted classification results.

## 🚀 How to Run This Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/Breast-Cancer-Prediction-Using-Logistic-Regression.git
```

### Step 2: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Step 3: Open Jupyter Notebook

```bash
jupyter notebook
```

### Step 4: Run the Notebook

Open the notebook file:

`BREAST_CANCER_PREDICTION_USER_LOGISTIC_REGRESSION.ipynb`

Run all cells to execute the project.

**Note:** The dataset is loaded directly from Scikit-learn, so no separate dataset CSV file is required.

## 🎓 Learning Outcomes

- Understanding Machine Learning classification.
- Working with the Scikit-learn dataset.
- Performing basic data analysis.
- Implementing Logistic Regression.
- Evaluating classification models.
- Visualizing confusion matrices using Seaborn.

## ⚠️ Disclaimer

This project is developed for educational and learning purposes only. It is not intended for medical diagnosis or clinical decision-making.

## 👨‍💻 Author

**Mohamed Aziz**

## ⭐ Conclusion

This project demonstrates the application of Logistic Regression in breast cancer classification. It provides practical experience in dataset analysis, model training, prediction, and performance evaluation using Python and Machine Learning libraries.
