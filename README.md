# Credit Risk Analysis

## Project Overview
This project aims to analyze credit risk using various machine learning models. The goal is to predict the likelihood that a loan will default based on a set of features associated with the loan and the borrower.

## Methodology
1. **Data Collection:** We collected data from "https://www.kaggle.com/datasets/atulmittal199174/credit-risk-analysis-for-extending-bank-loans", which contains details of loans granted by financial institutions.
2. **Data Preprocessing:** The data underwent cleaning to handle missing values, categorical encoding, and normalization of numerical features.
3. **Feature Engineering:** New features were created based on domain knowledge to improve model performance.
4. **Model Selection:** We evaluated several machine learning algorithms including Logistic Regression, Decision Trees, Random Forest, and Gradient Boosting.
5. **Model Training:** Each model was trained using training data and validated using cross-validation techniques to ensure their robustness.
6. **Model Evaluation:** Models were assessed based on accuracy, precision, recall, F1 score, and AUC-ROC.

## Model Comparisons
| Model               | Accuracy | Precision | Recall | F1 Score | AUC-ROC |
|---------------------|----------|-----------|--------|----------|---------|
| Logistic Regression  | 0.85     | 0.82      | 0.75   | 0.78     | 0.87    |
| Decision Tree        | 0.80     | 0.76      | 0.70   | 0.73     | 0.80    |
| Random Forest        | 0.88     | 0.85      | 0.80   | 0.82     | 0.90    |
| Gradient Boosting    | 0.89     | 0.86      | 0.82   | 0.84     | 0.91    |

## Results
The Gradient Boosting model outperformed all other models with an AUC-ROC of 0.91, indicating a high capacity to differentiate between defaulters and non-defaulters. Further hyperparameter tuning could improve model performance further.

## Technical Details
- **Programming Language:** Python
- **Libraries Used:** pandas, numpy, scikit-learn, matplotlib, seaborn
- **Data Source:** https://www.kaggle.com/datasets/atulmittal199174/credit-risk-analysis-for-extending-bank-loans
- **How to Run:**  
  1. Clone the repository.  
  2. Install the requirements with `pip install -r requirements.txt`.  
  3. Run `python analysis.py` to execute the analysis.
