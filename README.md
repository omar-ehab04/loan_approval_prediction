# loan_approval_prediction

I've built a model to predict whether a loan application will be approved based on a dataset containing various applicant and loan details.



Here's a quick look at the steps I've taken so far:



1.  **Data Loading and Exploration:** Loaded the dataset and explored its structure, including identifying numerical and categorical features.

2.  **Data Cleaning and Preprocessing:** Handled missing values (none found in this dataset), removed irrelevant columns ('loan_id'), and transformed the 'loan_status' target variable using Label Encoding.

3.  **Feature Analysis:** Examined the variance and distribution of numerical features and visualized their relationships using distribution plots and probability plots.

4.  **Feature Scaling:** Applied StandardScaler to standardize the numerical features.

5.  **Handling Class Imbalance:** Used RandomUnderSampler to balance the classes in the target variable by undersampling the majority class.

6.  **Model Building (Initial):** Started building a predictive model using Logistic Regression and Decision Tree Classifier, focusing on the 'cibil_score' feature.
