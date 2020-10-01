# Churn_in_Telecom
Predicting Customer churn in Telecome using different models such as Gradient Boosting, AdaBoosting, Random Forest, DecisionTreeClassifier.

DATA QUESTION.

As you probably guessed from the title of the dataset, this model aims to predict churn — a very common problem businesses face. Thinking about which metrics we want to use to evaluate our model, let’s think about what we want our model to predict and what is worse: a false negative prediction or a false positive prediction. Our model should predict whether a customer in our dataset will stay with the company(False) or if they will leave (True).

In this scenario, we have:

False negative: the model predicts that a customer stays with the company (False), when in fact that customer churns (True).

False positive: the model predicts that a customer will churn (True), when in fact they will stay(False).

Given this, we would probably argue that false negatives are more costly to the company as it would be a missed opportunity to market towards keeping those customers. For this reason, we will use accuracy and recall scores in confusion matrix to evaluate our model performance.
