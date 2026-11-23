# Heart Disease Prediction Using Logistic Regression

## 1. Project Overview
This project focuses on predicting the presence of heart disease using Logistic Regression, a supervised machine learning classification algorithm.

The model analyzes patient-related medical attributes and predicts whether heart disease is present (1) or absent (0).

**Course:** Regression and Classification Algorithms  
**Activity:** CIE 2 – Activity 2  
**Problem Type:** Binary Classification  
**Algorithm:** Logistic Regression

## 2. Objectives
- Understand and analyze the Heart Disease dataset.
- Perform data inspection and preprocessing.
- Identify patterns and relationships using Exploratory Data Analysis (EDA).
- Visualize the distribution of heart disease cases.
- Encode categorical variables into numerical form.
- Apply feature scaling using StandardScaler.
- Build a Logistic Regression classification model.
- Evaluate the model using classification metrics.
- Analyze the confusion matrix and classification report.
- Predict heart disease for new input records.

## 3. Dataset Information
- **Dataset Name:** Heart Disease Dataset
- **Dataset File:** `heart.csv`
- **Total Records:** 918
- **Total Columns:** 12
- **Target Variable:** `HeartDisease`

**Target Classes:**
- `0` – No Heart Disease
- `1` – Heart Disease

### Dataset Features
1. Age
2. Sex
3. ChestPainType
4. RestingBP
5. Cholesterol
6. FastingBS
7. RestingECG
8. MaxHR
9. ExerciseAngina
10. Oldpeak
11. ST_Slope
12. HeartDisease (Target)

**Dataset Source:** Add the exact Kaggle dataset URL you downloaded `heart.csv` from.

## 4. Tools and Technologies
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 5. Project Workflow
1. Import required Python libraries.
2. Load the Heart Disease dataset.
3. Inspect dataset structure and sample records.
4. Check missing values and duplicate records.
5. Perform Exploratory Data Analysis.
6. Visualize target class distribution.
7. Generate a correlation heatmap.
8. Separate independent variables and target variable.
9. Encode categorical features using One-Hot Encoding.
10. Split data into training and testing sets (80:20).
11. Apply StandardScaler.
12. Train the Logistic Regression model.
13. Generate predictions.
14. Evaluate the model using classification metrics.
15. Visualize the confusion matrix.
16. Analyze the classification report.

## 6. Model Evaluation Results

The model was evaluated on 184 test records.

| Metric | Result |
|---|---:|
| Accuracy | 88.59% |
| Precision | 87.16% |
| Recall | 93.14% |
| F1 Score | 90.05% |
| ROC-AUC | 92.97% |

### Interpretation
- **Accuracy:** The model correctly classified approximately 88.59% of test records.
- **Precision:** 87.16% of records predicted as positive were actually positive.
- **Recall:** The model identified approximately 93.14% of actual positive cases.
- **F1 Score:** 90.05%, showing a balance between precision and recall.
- **ROC-AUC:** 92.97%, indicating strong ability to distinguish between the two classes.

## 7. Data Quality Findings
- Total records: 918
- Total features: 12
- Missing values: 0
- Duplicate records: 0
- Training records: 734
- Testing records: 184

## 8. Key Findings
- The dataset contains two target classes: heart disease present and absent.
- Categorical variables were converted using One-Hot Encoding.
- StandardScaler was applied to numerical input features.
- Logistic Regression achieved 88.59% test accuracy.
- The model achieved a recall of 93.14% for the positive class.

## 9. Repository Structure

```text
CIE2-Activity2-AD3169/
│
├── Heart_Failure_Prediction_Dataset.ipynb
├── heart.csv
├── README.md
└── requirements.txt
```

## 10. Conclusion
This project demonstrates the implementation of Logistic Regression for binary classification using a Heart Disease dataset.

The model achieved 88.59% accuracy and 92.97% ROC-AUC on the test dataset. This project provided practical experience in data preprocessing, exploratory data analysis, feature encoding, feature scaling, model training and classification evaluation.

## 11. Limitations
- The model is trained on a particular dataset and may not generalize to every population.
- Its predictions depend on the quality and representativeness of the training data.
- Logistic Regression may not capture all complex relationships between medical features.
- This model is an educational machine learning project and must not be used as a substitute for professional medical diagnosis.

## 12. Author
**Disha Jadhav**  
Roll Number: AD3169  
Third-Year B.Tech – Artificial Intelligence and Data Science

## 13. Faculty Reference
[complexiota – GitHub](https://github.com/complexiota)
## 14.Dataset:https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction?utm_source=chatgpt.com
