# What-is-your-life-worth
A Predictive Analytics Approach to Assessing life Insurance Risks with Prudential

![image](https://user-images.githubusercontent.com/47016027/89235170-af9b1b80-d5bb-11ea-9f12-950961b10fbd.png)
# Introduction 
Studies have shown that only 40% of US citizens own life insurance, millennials account for only 1 out of 5 of the 40%. Getting life insurance is a long and tiring process which requires customers to take numerous medical exams that can take up to 30 days. The process turns people off especially in this one-click shopping world with on-demand everything. This study will be using machine learning to accurately predict risk classifications of customers, thereby making the process of owning life insurance shorter and less labor intensive while maintaining the customers privacy boundaries.
# Data
The dataset chosen to be analyzed is called “Life insurance assessment” which consists of information about life insurance applicants. It was compiled by Prudential, one of the largest issuers of life insurance in the USA, for a study on how to accurately classify risk using a more automated approach. This data was obtained from kaggle. https://www.kaggle.com/datasets
# Methodology 
3 algorithms were employed
  1. Classification and Regression Tree (CART)
  2. C5.0 Decision Tree
  3. k-Nearest Neighbor (k-NN)
# CART
![Screen Shot 2020-08-03 at 7 05 08 PM](https://user-images.githubusercontent.com/47016027/89235911-3270a600-d5bd-11ea-974f-30048dd69e0c.png)
# C5.0 
The C5 algorithm is a decision tree model, more specifically it is a variant of the ID3 model which is known as the most widely known decision tree algorithm. In place of using the Gini Index to measure the purity of a class as a result of a decision to branch along the particular attribute, ID3 and its variants use entropy to measure the extent of the uncertainty or randomness in a data set (Sharda et al., 2015).  

![Screen Shot 2020-08-03 at 7 06 53 PM](https://user-images.githubusercontent.com/47016027/89236299-289b7280-d5be-11ea-9a57-1b1e9eec39f3.png)
# K-NN
k-NN is a instance-based learning algorithm where the function is approximated locally and all final computations are done after the actual prediction is made. The objective of the k-NN model is assign a new object to a classification based upon its k nearest neighbors.

![Screen Shot 2020-08-03 at 7 06 25 PM](https://user-images.githubusercontent.com/47016027/89236324-3cdf6f80-d5be-11ea-8cf5-8de8671a1ebe.png)
# Result
Each model was subjected to a 10-fold cross validation and then evaluated using a confusion matrix, other data such as predictor variable sensitivity was also extracted from the models. The C5 gave the best performance with the highest accuracy rate of 71.8%,
# Contributions 
The models adopted in this study can predict risk classification and identify the most significant risk factors in classifying life insurance risk. With this knowledge, life insurance companies can correctly classify customers into their appropriate risk status. This will help them quote the right premium and would reduce “Risk pooling”. It will also help reducing the lengthy process of getting life insurance policy. This will in turn, impact public perception of the industry and entice more people to get life insurance.
