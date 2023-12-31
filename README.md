# Fraud_Detection_Analysis <br>
Developing a model for predicting fraudulent transactions for a financial company and use insights from the model to develop an actionable plan. Data for the case is available in CSV format having 6362620 rows and 10 columns. <br>
Data Dictionary: The data dictionary of the dataset can be found in Data Dictionary. <br>
Data Source: The dataset can be found in [here](https://drive.google.com/file/d/1F3BPsVFMolfjn8Qiwwfg848Ox32iB5P2/view?usp=sharing), file could not be added here as it is over the max limit of 25MB. <br>

The tasks I had to execute: <br>
1.Proactive detection of fraud while answering following questions. <br>
2. Data cleaning including missing values, outliers and multi-collinearity. <br>
3. Trying various ML models on the final cleaned dataset. <br>
     I started off by first training the model and then testing it using the two basic classifier models -> Decision Tree and Random Forests. Of these two, Random Forest came out as a better performer. <br>
     After this, I tried to use the various Boosting models (XGBoost, AdaBoost, Gradient Boosting and CatBoost). These 4 gave very high level of performance with an average accuracy score of 99.9%. Overall, XGBoost came out as the best performer of these Boosting models. <br>
4. Demonstrate the performance of the model by using best set of tools. <br>
