# Credit Risk Analysis

## Project Overview
This project aims to analyze credit risk using various machine learning models. The goal is to predict the likelihood that a loan will default based on a set of features associated with the loan and borrower characteristics.

## Methodology
1. **Data Collection:** We collected data from "https://www.kaggle.com/datasets/atulmittal199174/credit-risk-analysis-for-extending-bank-loans", which contains details of loans granted by financial institutions.
2. **Data Preprocessing:** The data underwent cleaning to handle missing values, categorical encoding, and normalization of numerical features.
3. **Feature Engineering:** New features were created based on domain knowledge to improve model performance.
4. **Model Selection:** We evaluated several machine learning algorithms including Logistic Regression, Support Vector Classifier (SVC), and Random Forest.
5. **Model Training:** Each model was trained using training data and validated using cross-validation techniques to ensure their robustness.
6. **Model Evaluation:** Models were assessed based on accuracy, precision, recall, and F1 score.

## Model Comparisons
| Model               | Accuracy | Precision | Recall | F1 Score |
|---------------------|----------|-----------|--------|----------|
| Logistic Regression  | 0.85     | 0.82      | 0.75   | 0.78     |
| SVC                  | 0.83     | 0.80      | 0.72   | 0.76     |
| Random Forest        | 0.88     | 0.85      | 0.80   | 0.82     |

## Results
The **Random Forest** model outperformed the other models with an accuracy of 0.88 and F1 score of 0.82, demonstrating strong capacity to predict credit default risk. This ensemble method effectively captures complex patterns in the data.

## Technical Details
- **Programming Language:** Python
- **Libraries Used:** pandas, numpy, scikit-learn, matplotlib, seaborn
- **Data Source:** https://www.kaggle.com/datasets/atulmittal199174/credit-risk-analysis-for-extending-bank-loans
- **How to Run:**  
  1. Clone the repository.  
  2. Install the requirements with `pip install -r requirements.txt`.  
  3. Run the Jupyter notebook `credit_risk_analyzer.ipynb` to execute the analysis.