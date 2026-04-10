# Credit Risk Analysis

## Project Overview
This project aims to analyze credit risk using various machine learning models. The goal is to predict the likelihood that a loan will default based on a set of features associated with the loan and borrower characteristics.

## Methodology
1. **Data Collection:** Collected data from "https://www.kaggle.com/datasets/atulmittal199174/credit-risk-analysis-for-extending-bank-loans", which contains details of loans granted by financial institutions.
2. **Data Preprocessing:** The data underwent cleaning to handle missing values, categorical encoding, and normalization of numerical features.
3. **Feature Engineering:** New features were created based on domain knowledge to improve model performance.
4. **Model Selection:** We evaluated several machine learning algorithms including Logistic Regression, Support Vector Classifier (SVC), and Random Forest.
5. **Model Training:** Each model was trained using training data and validated using cross-validation techniques to ensure their robustness.
6. **Model Evaluation:** Models were assessed based on accuracy, precision, recall, and F1 score.

## Model Comparisons
| Model                       | Test Accuracy |
|-----------------------------|---------------|
| Random Forest               | 0.8214        |
| Logistic Regression         | 0.8071        |
| Support Vector Machine      | 0.7929        |
| Tuned SVM (GridSearchCV)    | 0.7929        |
| XGBoost                     | 0.7643        |
| Voting Ensemble             | 0.8143        |

## Results
The current notebook implementation evaluates multiple classifiers on the loan default dataset. The best single-model accuracy is achieved by **Random Forest** at approximately 82.14%. A soft voting ensemble of Random Forest, Logistic Regression, and XGBoost also performs well at about 81.43%.

## Technical Details
- **Programming Language:** Python
- **Libraries Used:** pandas, numpy, scikit-learn, matplotlib, seaborn, xgboost
- **Data Source:** https://www.kaggle.com/datasets/atulmittal199174/credit-risk-analysis-for-extending-bank-loans
- **How to Run:**  
  1. Clone the repository.  
  2. Install the requirements with `pip install -r requirements.txt`.  
  3. Run the Jupyter notebook `credit_risk_analyzer.ipynb` to execute the analysis.