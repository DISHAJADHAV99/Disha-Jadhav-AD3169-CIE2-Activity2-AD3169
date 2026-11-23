# Decision Log – Heart Disease Prediction

## 1. Algorithm Selection
I selected Logistic Regression because the target variable, HeartDisease, has two classes: 0 (No Heart Disease) and 1 (Heart Disease).

## 2. Data Preprocessing
I checked missing values and duplicate records, encoded categorical variables using one-hot encoding, and applied StandardScaler to numerical features.

## 3. Train-Test Split
I used an 80:20 train-test split with stratification to maintain the class distribution.

## 4. Evaluation Metrics
I evaluated the model using accuracy, precision, recall, F1-score, specificity and ROC-AUC.

## 5. Threshold Selection
I compared decision thresholds of 0.3, 0.5 and 0.7 to understand their effect on false positives and false negatives.

## 6. Important Decision
I considered false negatives particularly important because missing a potential heart disease case can be serious. Therefore, recall was an important metric when comparing thresholds.

## 7. Final Decision
The final threshold was selected after comparing the evaluation results at all three thresholds.
