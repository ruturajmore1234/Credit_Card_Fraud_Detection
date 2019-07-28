# Credit_Card_Fraud_Detection
Logistic Regression classifier along with SMOTE sampling technique is used for classification.
#Conclusion:

|  Sampling   |       Model       |  SearchCV  |Scoring Metrics|Train_model_score|Test_model_score|best panalty|Best lambda|
|-------------|-------------------|------------|---------------|----------------:|---------------:|------------|----------:|
|SMOTE        |Logistic Regression|GridSearchCV|accuracy       |          0.97525|          0.9452|l1          |          4|
|SMOTE        |Logistic Regression|GridSearchCV|precision      |          0.06032|          0.9731|l1          |          1|
|SMOTE        |Logistic Regression|GridSearchCV|recall         |          0.91837|          0.9157|l1          |          4|
|SMOTE        |Logistic Regression|GridSearchCV|f1             |          0.11321|          0.9435|l1          |          4|
|UnderSampling|Logistic Regression|GridSearchCV|accuracy       |          0.94898|          0.9518|l1          |          5|
|UnderSampling|Logistic Regression|GridSearchCV|precision      |          0.94898|          0.9759|l1          |          5|
|UnderSampling|Logistic Regression|GridSearchCV|recall         |          0.94898|          0.9264|l1          |          5|
|UnderSampling|Logistic Regression|GridSearchCV|f1             |          0.94898|          0.9505|l1          |          5|
