## Customer-Churn-Prediction

### Overview
Consists of a model to predict if a customer will churn based on factors like age, tenure, income, number of dependents, type of plan, billing method, if the customer streams movies, etc. The data is of a telecom company.

### Approach
A lot of data preprocessing has been done to handle outliers, missing values, categorical variables. Univariate and multivariate EDA has been done to better understand and explore the data and trends. 

The dataset seems to somewhat unbalanced and hence, would give a false idea about the accuracy of the model. SMOTE technique has been use to handle imbalanced dataset.

Decision Trees, Random Forest, and XGBoost techniques were used to create the model. Finally, XGBoost classifier had the highest accuracy and so, is chosen for our final model.

GridSearchCV has been used for hyperparameter tuning. 

An accuracy of 96.4% is achieved through this model.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------
