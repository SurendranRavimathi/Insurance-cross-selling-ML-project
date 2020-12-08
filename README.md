# Insurance-cross-selling-ML-project (Python)
Formal Problem Statement
We want you to predict whether a customer is interested in a caravan insurance policy from other data about the customer. Information about customers consists of 86 variables and includes product usage data and sociodemographic data derived from zip area codes. The data was supplied based on a real world business problem. The training set contains over 5000 descriptions of customers, including the information of whether or not they have a caravan insurance policy. A test set contains 4000 customers of whom target variable is not shared with you.
Target Variable is V86.
You need to use train data for building the model and then use that model to predict outcome for given test data. Test dataset does not have a response column; you need to predict those values and submit it in a csv format. We expect outcomes to be either 0 or 1.

for more Information  kindly find the problem statement.pdf

Insurance cross-selling: A general insurance client wanted to know whether an existing policy holder would be interested in a new
car insurance policy. Information about the existing policy holders consisted of 86 variables and included product usage data and
socio-demographic data derived from zip area codes.

Solution: Used XGBoost to create a ML model to predict those customers most likely to respond positively to the new product and
the marketing campaign. Model had an F2 score of 0.37 (Python).

Base line score: 0.26
