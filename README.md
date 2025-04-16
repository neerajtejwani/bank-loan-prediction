Bank Loan Prediction.ipynb | Jupyter notebook with data analysis, preprocessing, model building, and evaluation
bankloans.csv | Sample dataset used for training and testing the model
README.md | Project overview and instructions
Features Used:
age – Age of the applicant
ed – Education level
employ – Years of employment
address – Years at current address
income – Annual income
debtinc – Debt-to-income ratio
creddebt – Credit card debt
othdebt – Other debts
default – Target variable (1 = Default, 0 = No Default)

Model used:
Random Forest Classifier
Model was trained with hyperparameter tuning using cross-validation.

Model Evaluation:
Metric | Value
Accuracy | 80%
Precision (Default = 1.0) | 71%
Recall (Default = 1.0) | 34%
F1-score (Default = 1.0) | 47%
Support (Default = 1.0) | 58
