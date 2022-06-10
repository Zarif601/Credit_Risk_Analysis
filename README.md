# Credit_Risk_Analysis

## Overview of the analysis:

This project uses different machine learning models to try to predict credit risk. The target labels in this analysis is 'low_risk' as in its not as risky to issue a loan to the individual, and 'high_risk' meaning the loanee would probably be unable to pay back the loan. We analyze the different models to see which model best predict credit risk through different accuracy metrics.

### Purpose:

Through analyzing credit risk, credit card companies will be able to better determine who to lend money and issue credit cards to. Credit card companies lending money is very common today, and being able to predict which clients to lend to would very much help these companies make such decisions.

## Results:

In this project 6 machine learning models were used to see which model predicts credit risk more accurately. The data was transformed using these 6 models and afterwards Logistic Regression was performed on it.  Their findings are as below:

#### 1. Naive Random Oversampling

Using naive random oversampling and then logistic regression, we got an accuracy score of 0.6614329112986135, which means the model correctly predicts 66% of the time. The precision, recall and f1 score of this model are shown below:

![Random Oversampling Report]()

#### 2. SMOTE Oversampling

This model generated an accuracy score of 0.6581159869962674, which is slightly lower than the random oversampling. Here are its precision, recall and f1 score:

![SMOTE Oversampling Report]()

#### 3. Undersampling

In this case the model generated accuracy score of 0.5439153831192286. This accuracy score is much worse than the previous two. Showing its precision, recall and f1 score below:

![Undersampling Report]()

#### 4. Combination (SMOTEENN) Sampling

This model generates an accuracy score of 0.6710719627856143. This score is slightly higher than that of the first two models. Displaying the metrics below:

![Combination Report]()

#### 5. Balanced Random Forest Classifier

The next two models are Ensemble Classifiers where as the first four were Resampling models. This model's accuracy score is 0.7885466545953005. This is much higher than the accuracy score of all the resampling models we have seen before. Here are its metrics:

![BRF Report]()

#### 6. Easy Ensemble AdaBoost Classifier

This final model generates an accuracy score of 0.9316600714093861, which is very accurate. Compared to other models, this one far outperforms them all. Here are the precision, recall and f1 score of this model:

![Easy Ensemble Report]()

## Summary:

