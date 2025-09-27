# Missing-Categorical-Data-Handling
This notebook focuses on handling missing values in categorical features using Mode Imputation.

Method: Mode imputation replaces missing values in a categorical column with the most frequently occurring category (the mode).

Dataset: The notebook uses a dataset containing Categorical_Data from a fictional customer survey.

Key Concepts Demonstrated:

Preprocessing: Irrelevant columns are removed to focus on the categorical features with missing data, such as Ever_Married, Graduated, Profession, and Var_1.

Visualizing Categorical Data: Bar plots are used to visualize the frequency of each category in a column like Profession and Gender to identify the mode.

Using Scikit-learn: It demonstrates the use of sklearn.impute.SimpleImputer with the strategy='most_frequent' parameter to perform mode imputation efficiently.

Validating Imputation: The notebook verifies that the missing values have been successfully filled by checking the percentage of null values again.
