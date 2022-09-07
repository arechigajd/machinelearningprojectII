# Predicting Strokes
#### By Jose Daniel Arechiga

## Identifying Patients' potential for a stroke
The dataset I used for my project can be found on Kaggle. The data includes measurements related to a patients health. I was interested in this topic because i personally know people who have endured a stroke. Of them, one explained to me that their stroke was considered a mild case. This made me think perhaps strokes happen more often than I may have expected, or at the very least there is a connection to having a stroke when considering other health issues, as opposed to random. Fast forward to now, I have a chance to go through some stroke data and see what kinds of health ailments may lead to a person having a stroke.

## How to Predict
I'll be making a machine learning model to do this. This can be done through any means where you can run Python code. For this project, I used Google Colaboratory.

## The Process
First thing I did was look through the data for any cleaning that may need to be done. This includes getting rid of any duplicate values, handling missing values, and making sure all of the other data made sense. This can include making sure datatypes are in line with what they should, making sure .value_counts are typical, etc.

## Analysis
From the analysis, the data shows interestingly that those who have never smoked are at the highest risk to get stroke. Overall, however, age seemed to be that main decider of whether a patient is at risk of getting a stroke or not.

## Model
After running a couple models, I found my  tuned Logistic Regression Model to predict whether a patient had a stroke or not to be the most accurate. A Logistic Regression Model, while having "regression" in it's name, is a model use for classification purposes. In this case, it's classifying whether a patient had a stroke or not; essentially classifying whether it was one outcome or the other. A Logistic Regression model has similarities to Linear Regression, however the algorithm differs in that the logistic model will keep the values in the range of 0 to 1.

## Conclusion
We are able to predict with a good degree of certainty what percentage of patients are at risk for having a stroke, or not, based on certain underlying health issues. In turn, we should now be able to foresee what patients may be at greater risk to having a stroke and begin to communicate and put into practice some preventative measures. Applied carefully, we can expect to see how initiating preventive measures for at risk patients will help decrease the amount of paients who acually have a stroke.
