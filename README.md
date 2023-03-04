# Road-Traffic-Severity-Classification
![image](https://user-images.githubusercontent.com/68380016/222876469-051dbc37-878f-44de-90b8-f85fd8bfa3b6.png)
The Road Traffic Severity Classification project is a supervised machine learning project that aims to predict the severity of road accidents based on various features such as weather conditions, road surface conditions, and the number of vehicles involved in the accident. The dataset used in this project is obtained from the UK Department for Transport and consists of approximately 250,000 road accidents that occurred between 2005 and 2015.

The project involves several steps such as data cleaning, exploratory data analysis, feature engineering, and model building. In the data cleaning step, missing values are imputed and irrelevant columns are dropped. In the exploratory data analysis step, the distribution of the target variable and the relationship between the features and the target variable are explored using visualizations. In the feature engineering step, new features are created from the existing features to improve the performance of the models.

Several machine learning models such as **logistic regression, random forest classifier, decision tree classifier, and XGBoost classifier are trained on the dataset** using techniques such as **SMOTE** for handling class imbalance. The performance of each model is evaluated using metrics such as **accuracy, precision, recall, and F1-score**.

Finally, a **stacking classifier is built by combining the predictions of the base models using a logistic regression model as the meta-learner**. The hyperparameters of the stacking classifier are optimized using grid search cross-validation. The performance of the stacking classifier is evaluated on a test set and is found to achieve an accuracy of around **94%**.

The project demonstrates how supervised machine learning techniques can be used to predict the severity of road accidents and help in improving road safety by identifying the factors that contribute to more severe accidents.
