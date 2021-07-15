# Titanic-ML-problem

## About the Challenge

The Titanic ML challenge is to form a model that predicts which person on the Titanic will survive. On April 15, 1912, during her first voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone on board, resulting in the death of 1502 out of 2224 passengers and crew. Model will decide based on the trained data, which group of people more likely to survive.

## Approach
The first approach is to analyse the data. Data analysis is an important step before putting it into the model to train. Data contains different features. Some features are not needed and some are empty. So, there is a need to decide which data is to be used, which data is valuable and how can a data be processed. 
The next step is to choose a good model to do the prediction. The better option is to choose different models and test their accuracy on the training data. The better accuracy does not mean the model is the best. There is also needed the analysis of cross-validation with a certain data and try to work out the model of it. The better option is to choose the one model which can predict the better accuracy in both training data and cross-validation test. 

## Model
I have used three techniques of Machine Learning to train the model. These are Logistic Regression, K-nearest neighbours and Linear Support Vector Machines. The accuracy that I am getting on the training and cross-validation set are as follows.
Machine learning technique| Accuracy on Training data|Accuracy on Cross-Validation data
:---|:---:|---:
SVC |79.42|77.95
Logistic regression|79.98|79.42
K-nearest Neighbours|83.46|76.72

From the accuracy point of view, the better option to work on is with logistic regression.
## Observation 

The logistic regression model gave me the same around 80% accuracy also on the test data. It shows that the model was better but did not the best. So, go through more techniques to create machine learning models.  

