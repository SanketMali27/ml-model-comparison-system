# Machine Learning Model Comparison System

## Overview

This project compares the performance of multiple Machine Learning classification algorithms on the same dataset. The objective is to understand how different models behave under identical conditions and identify the best-performing model using various evaluation metrics.

The project includes data preprocessing, feature scaling, model training, performance evaluation, and result visualization.

---

## Features

* Data preprocessing and cleaning
* Train-test data splitting
* Feature scaling using StandardScaler
* Training multiple Machine Learning models
* Performance evaluation using:

  * Accuracy
  * Precision
  * Recall
  * F1-Score
* Model comparison through visualizations
* Automatic identification of the best-performing model

---

## Models Implemented

* Logistic Regression
* Random Forest Classifier
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)
* Decision Tree Classifier

---

## Dataset

The project uses a Heart Disease Classification dataset.

Target Variable:

* `target`

  * 1 = Presence of Heart Disease
  * 0 = Absence of Heart Disease

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib

---

## Project Structure

```text
Model_Comparison_Project/
│
├── heart.csv
├── model_comparison.py
├── model_comparison_results.csv
├── requirements.txt
├── README.md
└── .gitignore
```

---

## Installation

### Clone Repository

```bash
git clone https://github.com/SanketMali27/ml-model-comparison-system.git
cd ml-model-comparison-system
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

Windows:

```bash
venv\Scripts\activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run Project

```bash
python model_comparison.py
```

---

## Evaluation Metrics

The models are evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score

These metrics help determine the effectiveness of each classification algorithm.

---

## Sample Workflow

1. Load dataset
2. Handle missing values
3. Split data into training and testing sets
4. Apply feature scaling
5. Train multiple ML models
6. Generate predictions
7. Evaluate performance
8. Compare results
9. Visualize model performance
10. Select the best-performing model

---

## Learning Outcomes

Through this project, I gained practical experience in:

* Data preprocessing
* Feature engineering concepts
* Model training and testing
* Classification metrics
* Machine Learning model comparison
* Performance analysis and visualization

---

## Future Enhancements

* Hyperparameter Tuning using GridSearchCV
* Cross Validation
* Confusion Matrix Visualization
* ROC-AUC Curve Analysis
* Streamlit Web Application Deployment
* Support for additional datasets

---

## Author

**Sanket Mali**

* Full Stack Developer
* AI/ML Enthusiast

GitHub: https://github.com/SanketMali27
