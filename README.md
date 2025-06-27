# Task 4: Logistic Regression – Breast Cancer Classification

##  Objective
Use logistic regression to build a binary classifier that predicts whether a tumor is malignant (M) or benign (B).

##  Dataset
- Source: Kaggle – Breast Cancer Wisconsin Dataset
- Format: `data.csv`
- Target: `diagnosis` (M = malignant, B = benign)

##  Steps Performed
1. Loaded CSV from Kaggle
2. Dropped unused columns (`id`, `Unnamed: 32`)
3. Encoded target column: M → 1, B → 0
4. Standardized features using `StandardScaler`
5. Trained a `LogisticRegression` model
6. Evaluated using:
   - Confusion matrix
   - Classification report (precision, recall, F1-score)
   - ROC-AUC and ROC Curve
7. Tested custom thresholding

##  Results
- Accuracy: ~97%
- ROC-AUC Score: ~0.99
- High recall for detecting malignant tumors

##  Tools Used
- Python, Pandas, NumPy
- Scikit-learn, Matplotlib, Seaborn

##  How to Run
1. Clone the repo
2. Install dependencies:
