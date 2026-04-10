# Heart-Disease-Prediction
## Objective
To build a machine learning model that predicts whether a person is at risk of heart disease based on various clinical health metrics. This is a binary classification task where we distinguish between 'no disease' (0) and 'presence of disease' (1).

## Dataset
**Source:** UCI Heart Disease Dataset (via Kaggle).
**Samples:** 920 patients.
**Features:**
- `age`: Age in years
- `sex`: Gender (Male/Female)
- `cp`: Chest pain type
- `trestbps`: Resting blood pressure
- `chol`: Serum cholesterol in mg/dl
- `fbs`: Fasting blood sugar > 120 mg/dl
- `restecg`: Resting electrocardiographic results
- `thalch`: Maximum heart rate achieved
- `exang`: Exercise induced angina
- `oldpeak`: ST depression induced by exercise relative to rest
- `slope`: The slope of the peak exercise ST segment
- `ca`: Number of major vessels colored by flourosopy
- `thal`: Thalassemia type
- `target`: Heart disease diagnosis (0 = healthy, 1 = disease present)

## Workflow
1. **Data Exploration & Cleaning:** 
   - Identify and handle missing values in columns like `ca`, `thal`, and `slope`.
   - Perform descriptive statistics and visualize target distribution.
2. **Preprocessing:**
   - Convert multi-class labels into binary labels.
   - Impute missing values (median for numerical, mode for categorical).
   - Encode categorical variables using one-hot encoding.
3. **Modeling:**
   - Train classification models (Logistic Regression or Decision Trees).
4. **Evaluation:**
   - Assess performance using Accuracy, Confusion Matrix, and ROC-AUC curves.
   - Analyze feature importance to understand key health indicators.
