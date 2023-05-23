# phase-3-project

Business overview


Syriatel is a telecommunication company based in Syria that is looking to reduce customer churning inorder to increase their revenue.The company asssigned us  with the role of  building a classifier whose main goal is to predict customer churn in order help the telecom company to retain valuable customers, reduce revenue loss, and improve customer satisfaction. This can ultimately lead to increased revenue and profitability for the company.


Business problem


Churn prediction is a technique used by companies to identify customers who are most likely to stop using their products or services.By using the dataset provided we are going to be exploring the features provided in order to create a classifier that can predict the likelihood of a customer churning and also the factors that lead to high customer churning.with creation of an effective model Syriatel will be able to identify their weaknesses and how to improve inorder to be able to maintain their customers and reduce customers leaving.


Objectives


1.our main objective is to identify the features that lead to high customer churning and to what extent
2.To create predictive,supervised models that can predict churn
3.To identify ways in which we can reduce customer churning by comparing with features causing it.e.g they can improve their customer service calls


Data understanding


inorder to create our model,we used Syria dataset from kaggle to create our our model.The dataset has 3333rows and 21 columns.We identified features that were affecting customer behaviour in the company.features such as customer service,international calls and total day charges.There were no duplicated or missing values in the dataset.I used churn as the target column to predict customers leaving and those remaining in the company.We also dropped some features such as state and areacode since they were not useful in our models.


Modelling


I decided to use recall as our metric of success since its used to predict the true positive rate

We used 4 models to predict the level of churning in our company.The baseline model,KNN Model,DecisionTree model,Randomforest.
Based on the models,the decision tree model was the best performing compared to other models with a recall of 75% and precision of 46%.Therefore it would be safe to use it to predict the churning rate of customers so that we can take the necessary measures.

Evaluation


Logistic regression:r2 score: 73% 
                    Recall:73% 
                    Precision:31%
Decisiontreeclassifier:r2 score:91%
                       Recall:75% 
                       Precision:49%
KNNNeighborsclassifier:r2 score:72% 
                       Recall:73% 
                       Precision:35%
Randomforestclassifier:r2 score:87% 
                       Recall:68% 
                       Precision:58%



Recommendation


From the models we get to see that the Decision tree has the highest recall and therefore can be used to predict the highest rate of customer churning .I would therefore recommend that they use this model so that they can be able to predict the rate of customer churning and put necessary measures befor hand

From the data we get to see that features such as customer service and international plan highly affect the customer churning rate.Syriatel hould make sure that they improve their services so that they can retain customers and avoid revenue loss


Further investigations should be made in order to know what steps to take inorder to reduce by atleast 7% churning e.g offering incentives to customers,look at the targeted market especially if they have international plan or not so that they can retain their customers

conclusion


In conclusion we decided that Syriatel company should use descionTree model to make their predictions since it has the highest recall of 75% so that they can be able to observe the trends and ways on how to reduce churning and increase percentage profit within the year.