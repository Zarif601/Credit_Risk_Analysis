# Credit_Risk_Analysis

## Overview of the analysis:

This project uses different machine learning models to try to predict credit risk. The target labels in this analysis is 'low_risk' as in its not as risky to issue a loan to the individual, and 'high_risk' meaning the loanee would probably be unable to pay back the loan. We analyze the different models to see which model best predict credit risk through different accuracy metrics.

### Purpose:

Through analyzing credit risk, credit card companies will be able to better determine who to lend money and issue credit cards to. Credit card companies lending money is very common today, and being able to predict which clients to lend to would very much help these companies make such decisions.

## Results:

In this project 6 machine learning models were used to see which model predicts credit risk more accurately. The data was transformed using these 6 models and afterwards Logistic Regression was performed on it.  Their findings are as below:

#### 1. Naive Random Oversampling

Using naive random oversampling and then logistic regression, we got an accuracy score of 0.6614329112986135, which means the model correctly predicts 66% of the time. The precision, recall and f1 score of this model are shown below:

![Random Oversampling Report](https://github.com/Zarif601/Credit_Risk_Analysis/blob/main/Images/Random%20Oversampling%20Report.PNG)

#### 2. SMOTE Oversampling

This model generated an accuracy score of 0.6581159869962674, which is slightly lower than the random oversampling. Here are its precision, recall and f1 score:

![SMOTE Oversampling Report](https://github.com/Zarif601/Credit_Risk_Analysis/blob/main/Images/SMOTE%20Oversampling%20Report.PNG)

#### 3. Undersampling

In this case the model generated accuracy score of 0.5439153831192286. This accuracy score is much worse than the previous two. Showing its precision, recall and f1 score below:

![Undersampling Report](https://github.com/Zarif601/Credit_Risk_Analysis/blob/main/Images/Undersampling%20Report.PNG)

#### 4. Combination (SMOTEENN) Sampling

This model generates an accuracy score of 0.6710719627856143. This score is slightly higher than that of the first two models. Displaying the metrics below:

![Combination Report](https://github.com/Zarif601/Credit_Risk_Analysis/blob/main/Images/Combination%20Report.PNG)

#### 5. Balanced Random Forest Classifier

The next two models are Ensemble Classifiers where as the first four were Resampling models. This model's accuracy score is 0.7885466545953005. This is much higher than the accuracy score of all the resampling models we have seen before. Here are its metrics:

![BRF Report](https://github.com/Zarif601/Credit_Risk_Analysis/blob/main/Images/BRF%20Report.PNG)

#### 6. Easy Ensemble AdaBoost Classifier

This final model generates an accuracy score of 0.9316600714093861, which is very accurate. Compared to other models, this one far outperforms them all. Here are the precision, recall and f1 score of this model:

![Easy Ensemble Report](https://github.com/Zarif601/Credit_Risk_Analysis/blob/main/Images/Easy%20Ensemble%20Report.PNG)

## Summary:

Based on the performance of the above mentioned models we can see that the Easy Ensemble AdaBoost Classifier performed with an accuracy of 93%. It also has a high average f1 score of 0.97. However, if we look at the precision of accurately predicting high risk loans, it has a value of 0.09, which is extremely low. However, all the other models also perform poorly with low precision scores in the same category. As such, I would not suggest any of these machine learning models for the company to determine credit risk. It would be best for them to try other models and see if those perform better than the ones tried here.
