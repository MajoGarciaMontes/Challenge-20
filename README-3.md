
# Credit Risk Analysis Report



The purpose of this analysis was to develop and evaluate machine learning models for predicting loan statuses in order to assist a company in making informed lending decisions. In order to help a business make wise lending decisions, this investigation developed and evaluated machine learning models for predicting loan statuses. The dataset included data about loans, including information about borrowers, loan amounts, interest rates, and credit scores. Predicting the loan status, which categorized loans as either healthy or non-healthy, was the objective. On the other hand, the loan status, which represented whether a loan was healthy (0) or not, was the relevant variable. The loan status variable's value_counts shed light on the dataset's class distribution and potential class imbalance.

Now about the stages of the magine, were the following:

- Data Exploration and Preprocessing: The dataset was explored to understand its structure, identify missing values, handle categorical variables, etc.

- Model Selection: Several machine learning models were considered, including Logistic Regression.

- Model Training and Evaluation: The selected models were trained on the training dataset and evaluated using various performance metrics.

- Model Comparison: The performance of the trained models was compared based on the evaluation metrics. 

- Resampling Techniques: To address class imbalance in the dataset, resampling techniques like oversampling (RandomOverSampler) were applied. 

- Model Recommendation: Based on the evaluation results and considerations of model performance, a recommendation was made regarding the preferred model for loan status prediction.

One of the methods used was Logistic Regression. Logistic Regression is a classification algorithm that models the probability of a binary outcome. It was utilized to predict loan statuses based on the provided features.

## Results

The following are the performance metrics obtained from the machine learning models:

### Machine Learning Model 1:
Balanced Accuracy Score: 0.99
Precision Score: 0.85
Recall Score: 0.91
### Machine Learning Model 2:
Balanced Accuracy Score: 0.99
Precision Score: 0.84
Recall Score: 0.99


## Summary

High balanced accuracy scores for both models demonstrate their capacity to reliably forecast both good and negative events. Both models have high precision ratings, which indicates that they can accurately detect positive events. Furthermore, both models' memory scores show a strong capacity to detect positive occurrences.

Given that both models work similarly, it is critical to determine the precise requirements and priorities of the issue at hand. Model 1 can be advised if accuracy (accurately detecting positive cases) is crucial, as it has a precision score of 0.85. However, Model 2 with a recall score of 0.99 would be the better option if recall (recording all positive events) is a crucial criterion.

In summary, both models demonstrate good performance, and the choice between them should be based on the specific needs and priorities of the problem.



