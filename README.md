Deep Learning Model for Predicting Telecom Customer Churn:

Goal is to analyze telecom customers based on the 21 customer’s attributes and to predict behavior to retain customers, i.e. to predict if a customer is going to cancel their subscription or not with the telecom service provider. The raw data contains 7043 rows (customers) and 21 columns (features), and the “Churn” column is our target.

Dataset link: https://www.kaggle.com/blastchar/telco-customer-churn

Developed model is then compared with respect to the changing hyper-parameters:
a.	1 Hidden Layer vs 2 Hidden Layers
b.	No of neurons in hidden layers between (a)2/3 the size of the input layer, plus 	the size of the output layer, and (b) twice the size of the input layer
c.	Batch Size 2, 4, 8 (See documentation in model.fit) 
d.	Activation function - ReLU and your choice