# Logistic-Regression--Mini-project

In this project, I have learnt on how to predict if a customer will purchase insurance or not. I have learnt how to split train and testing data and calculating accuracy of a model by using score.

Logistic regression is one of the techniques used for classification. The predicted value is categorical. It is a binary classification, where the asnwere is either 'Yes' or 'No' (0/1). 

Firstly, logistic regression stars by taking a weighted sum of input festures, which is similar to linear regresion , wheree we combine inputs to form a single value. 

example, if we have two features x1, x2, model calculates
  z= w1 * x1 + w2 * x2 + b

  where, w1 and w2 are weights or coefficients for each feature.
  b is the bias term 
  x1 and x2 are input features

Sigmoid function: 
  To convert this linear combination into a probability, we apply sigmoid function which   takes any real-valued number and quanshes into a range between 0 and 1. This is why   
  logistic regression is used for predicting probabilities

    P= 1/ 1+ e^ (-z)
Thresholding:
   p> 0.5 , we classify the instance belonging to class 1
   p<0.5, we classify the instance belonging to class 0

Training the model(optimization)

  To find the best value for w1 and b, logistic regression uses a process called       
  optimization. 

Model Predictions
  Once the model has been trained (found the best weights), it can be used to make 
  predictions on the unseen data. 

I have attached the code and dataset in this repository for references. This mini-project is a part of my Machine learning journey to help me understand the basics and implement my knowledge at the same time.
