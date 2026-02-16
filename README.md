Project Summary ;
Built a machine learning model to predict whether a loan applicant is likely to default. The goal was to help banks reduce financial risk by identifying high-risk customers before loan approval.

Problem Statement :
Loan defaults lead to major financial losses for banks.
In this project, I developed a classification model to predict loan default (0 = No Default, 1 = Default) using applicant and loan-related features.


Dataset Information ;
Total Records: 30,000+
Target Variable: Loan Status (Default / No Default)


What I Did in This Project :
Performed data cleaning and handled missing values using median and group-based imputation
Removed unrealistic outliers after proper analysis
Conducted Exploratory Data Analysis (EDA) to understand trends and risk patterns
Encoded categorical variables using Label Encoding / One-Hot Encoding
Applied feature scaling where required
Split data into training and testing sets
Built baseline model using Logistic Regression
Improved performance using Random Forest with hyperparameter tuning (GridSearchCV)
Evaluated models using Accuracy, Precision, Recall, F1-Score, ROC-AUC
Analyzed feature importance to understand key risk drivers


Models Used
Logistic Regression
Random Forest (Tuned)


Key Findings :
Applicants with lower income showed higher default probability
Short employment length increased risk
Higher interest rates were strongly linked with defaults
Lower loan grades had significantly higher risk


Business Impact :
Helps financial institutions reduce bad loans
Supports better loan approval decisions
Enables risk-based pricing strategy
Identifies high-risk customer segments


Tools & Technologies
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Jupyter Notebook

Final Result

The tuned Random Forest model achieved strong performance with good balance between precision and recall, and minimal overfitting. The model provides practical insights that can support real-world credit risk assessment.
