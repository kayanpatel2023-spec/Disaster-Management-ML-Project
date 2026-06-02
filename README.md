# Disaster Management Prediction Using Machine Learning
Machine Learning based Disaster Management System using Synthetic Dataset

## Project Overview

This project focuses on predicting whether a disaster event will become a major disaster using Machine Learning techniques. A synthetic disaster dataset was created and analyzed to support disaster management decision-making.

The system performs data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and performance evaluation using multiple machine learning algorithms.

---

## Objectives

- Analyze disaster-related data.
- Identify factors influencing disaster severity.
- Compare multiple machine learning models.
- Predict whether a disaster is classified as a major disaster.
- Support disaster response and resource planning.

---

## Dataset

The project uses a **synthetic disaster events dataset** containing information such as:

- Disaster Type
- Location
- Number of People Affected
- Economic Loss
- Relief Aid Provided
- Infrastructure Damage
- Target Variable: Major Disaster (Yes/No)

---

## Project Workflow

### 1. Data Collection
- Imported synthetic disaster dataset using Pandas.

### 2. Data Exploration
- Checked dataset information.
- Verified missing values.
- Analyzed feature distributions.

### 3. Exploratory Data Analysis (EDA)
- Distribution of major disasters.
- Disaster type frequency analysis.
- Visualizations using Matplotlib and Seaborn.

### 4. Feature Engineering
- Converted categorical features into numerical values using Label Encoding.
- Mapped aid-related values into machine-readable format.

### 5. Data Preprocessing
- Feature selection.
- Train-Test Split (80:20).
- Standardization using StandardScaler.

### 6. Model Training
The following machine learning models were trained and evaluated:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Gradient Boosting

### 7. Model Evaluation
Performance was measured using:

- Accuracy
- Precision
- Recall
- F1 Score
- Specificity

---

## Results

| Model | Accuracy | Precision | Recall | F1 Score | Specificity |
|---------|----------|-----------|--------|----------|------------|
| Logistic Regression | 99.93% | 100.00% | 99.81% | 99.90% | 100.00% |
| Decision Tree | 100.00% | 100.00% | 100.00% | 100.00% | 100.00% |
| Random Forest | 99.93% | 100.00% | 99.81% | 99.90% | 100.00% |
| SVM | 99.93% | 100.00% | 99.81% | 99.90% | 100.00% |
| KNN | 94.08% | 91.92% | 92.93% | 92.42% | 94.81% |
| Naive Bayes | 95.68% | 92.71% | 96.46% | 94.55% | 95.17% |
| Gradient Boosting | 100.00% | 100.00% | 100.00% | 100.00% | 100.00% |

---

## Best Performing Models

🏆 **Decision Tree** and **Gradient Boosting** achieved:

- 100% Accuracy
- 100% Precision
- 100% Recall
- 100% F1 Score
- 100% Specificity

These models provided the best classification performance on the synthetic disaster dataset.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Google Colab
- GitHub

---

## Repository Structure

```text
Disaster-Management-ML-Project/
│
├── data/
│   └── synthetic_disaster_events_2025.csv
│
├── notebooks/
│   └── disaster_management.ipynb
│
├── README.md
│
└── requirements.txt
```

---

## Future Improvements

- Use real-world disaster datasets.
- Integrate live weather and disaster APIs.
- Deploy as a web application.
- Add deep learning models.
- Develop real-time disaster alert systems.

---

## Author

Kayan Patel

Machine Learning Project – Disaster Management Prediction System
