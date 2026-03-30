# 👥 Group Project: Diabetes Risk Prediction

## 🎯 Objective
The objective of this project is to develop and evaluate supervised learning models (Logistic Regression and CART) to predict diabetes risk using 2 datasets with differing feature characteristics. Model performance is assessed using classification metrics with emphasis on recall due to the healthcare context.

## 📊 Results

### 1️⃣ Early Symptoms Dataset
This dataset consists primarily of binary symptom indicators. Such features may exhibit non-linear interactions that influence diabetes risk.

#### 📈 Logistic Regression

**Confusion Matrix**

|                | Predicted Positive | Predicted Negative |
|----------------|-------------------|-------------------|
| Actual Positive | 49 (TP)           | 3 (FN)            |
| Actual Negative | 7 (FP)            | 16 (TN)           |

**Performance Metrics**

| Metric        | Value |
|--------------|-------|
| Accuracy     | 86.7% |
| Precision    | 87.5% |
| Recall       | 94.2% |
| Specificity  | 69.6% |

#### 🌳 CART (Decision Tree)

**Confusion Matrix**

|                | Predicted Positive | Predicted Negative |
|----------------|-------------------|-------------------|
| Actual Positive | 50 (TP)           | 2 (FN)            |
| Actual Negative | 3 (FP)            | 20 (TN)           |

**Performance Metrics**

| Metric        | Value |
|--------------|-------|
| Accuracy     | 93.3% |
| Precision    | 94.3% |
| Recall       | 96.2% |
| Specificity  | 87.0% |

### 2️⃣ Health Indicators Dataset
This dataset contains continuous numerical variables representing physiological and lifestyle indicators.

#### 📈 Logistic Regression

**Confusion Matrix**

|                | Predicted Positive | Predicted Negative |
|----------------|-------------------|-------------------|
| Actual Positive | 239 (TP)          | 61 (FN)           |
| Actual Negative | 91 (FP)           | 209 (TN)          |

**Performance Metrics**

| Metric        | Value |
|--------------|-------|
| Accuracy     | 74.7% |
| Precision    | 72.4% |
| Recall       | 79.7% |
| Specificity  | 69.7% |

#### 🌳 CART (Decision Tree)

**Confusion Matrix**

|                | Predicted Positive | Predicted Negative |
|----------------|-------------------|-------------------|
| Actual Positive | 237 (TP)          | 63 (FN)           |
| Actual Negative | 109 (FP)          | 191 (TN)          |

**Performance Metrics**

| Metric        | Value |
|--------------|-------|
| Accuracy     | 71.3% |
| Precision    | 68.5% |
| Recall       | 79.0% |
| Specificity  | 63.7% |
