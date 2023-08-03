### deep-learning-challenge

## Background
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

## Required Steps
Preprocess the Data, Compile, Train, and Evaluate the Model, Optimize the Model, Write a Report on the Neural Network Model

## References
IRS. Tax Exempt Organization Search Bulk Data Downloads. https://www.irs.gov/



#### Analysis

1. Purpose of analysis
The purpose of this analysis was to build a neural network that can predict if applicants will be successful if funded by Alphabet soup.

2. Results
Target Variable 
•	IS_SUCCESSFUL

Features 
•	All columns except 'IS_SUCCESSFUL'

Variables to be Removed 
•	EIN
•	Name

1st Layer Neurons 
•	20
•	relu

2nd Layer Neurons 
•	10
•	relu

3rd Layer Neurons = 
•	3
•	relu



The steps I took to improve the model were:

•	change all activation to relu for accuracy a

•	Changed epochs to 500 as the model was learning and if it had more epochs, it could learn more of the dataset

•	With so many epochs I raised the batch size to make the code run faster.

3. Summary
The overall results of this model were 74%. With almost 75% correct classifications accuracy this can give some predictive ability. We could use a basic clustering model to cluster the classes in which we are trying to solve. I would recommend a cluster because the dataset can be solved by splitting groups and trying to predict which group new samples will belong to.

