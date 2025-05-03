# Loan Default Prediction Using Machine Learning

A machine learning-based system to predict loan defaults using borrower demographic, financial, and credit history information. This project helps financial institutions identify high-risk loan applicants and reduce credit loss.

##  Problem Statement

Loan default prediction is crucial for lenders to assess financial risk. This project uses a dataset with detailed borrower attributes to train and evaluate multiple models that predict the likelihood of loan default.

##  Data Preprocessing

- **Duplicate Removal**: Ensured each loan entry is unique.
- **Missing Values**: Filled missing `employment length` values with the median.
- **Outlier Removal**: Used IQR method to filter out extreme values in `age` and `income`.
- **Class Balancing**: Applied SMOTE to handle imbalance in default vs. non-default classes.
- **Data Split**: 80% for training, 20% for testing.

##  Models Used

| Model               | Accuracy |
|--------------------|----------|
| Logistic Regression | 74%      |
| Decision Tree       | 93%      |
| Gradient Boosting   | 94%      |


## Tools & Libraries

- Python (pandas, numpy, matplotlib)
- scikit-learn
- imbalanced-learn (SMOTE)
- seaborn

##  Dataset Features

- Age, Income
- Home Ownership
- Employment Length
- Loan Intent & Grade
- Loan Amount & Interest Rate
- Credit History
- Loan Status (Target)

##  Conclusion

Gradient Boosting performed best with 94% accuracy, making it a reliable model for predicting loan defaults. These insights can aid financial institutions in risk mitigation and informed lending decisions.


