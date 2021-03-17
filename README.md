# Telecom-customer-churn-prediction
This project is about predicting whether a customer will change telecommunications provider or not.This problem statement is targeted at enabling churn reduction using analytics concepts and predicting new churn on test dataset.

The Churn (loss of customers to competition) is a problem for companies because it is more expensive to acquire a new customer than to keep your existing one from leaving.

Dataset :
<ul>
  <li> train.csv - the training set - Contains 4250 lines with 20 columns. 3652 samples (85.93%) belong to class churn=no and 598 samples (14.07%) belong to class churn=yes </li>
  <li>test.csv - the test set - Contains 750 lines with 20 columns: the index of each sample and the 19 features (missing the target variable "churn"). </li>
</ul>

### Project Flow

<ol>
 <li>Importing and investigating the data</li>
 <li>Data Pre-processing</li>
 <li>Checking Missing Value in Data</li>
 <li>Data Visualization</li>
 <li>Changing Categorical column values to numeric codes</li>
 <li>Feature Scaling</li>
 <li>Train-Test Split</li>
 <li>Random Forest Model</li>
 <li>Logistic Regression Model</li>
 <li>K-Nearest Neighbors Model</li>
 <li>Naive Bayes Model</li>
 <li>Model Comparison</li>
 <li>Features Importance</li>
 <li>AUC & ROC Curve</li>
 <li>Final Test Data Predictions</li>
 <li>Saving the OutPut</li>


## Results:  


<ol>
 <li>Random Forest accuracy: 94.87 %</li>
 <li>Logisitc Regression accuracy: 83.68 %</li>
 <li> KNN accuracy: 89.45 %</li>
 <li>Naive Bayes accuracy: 80.97 %</li>
 <li>roc_auc_score = 0.90</li>
  
## Checking the distribution of the target variable on train data (Given):

<img src = 'Distribution of Customer Churning on train data.png' width = "400" height = "300"/>

## Checking the distribution of the target variable on test data (Predicted):

<img src = 'Distribution of Customer Churning on test data.png' width = "400" height = "300"/>



## Ways to Reduce Customer Churn

1. Focussing attention towards your better customers

Instead of spending huge amount of resources to try to incentivize the customers who are likely to churn based on customer behavior analysis, it is better for the company to spend those resources on it’s existing customers. This will not only ensure customer loyalty but will also create meaningful long term relationship with those customers.

2. Analyzing customer churn pattern

Analyzing the churn pattern of customers is the key method by which it can understand which customers are about to leave and which features of a company’s product are most important to the customers. It may be possible that customers prefer all: low, medium and high valued products or subscriptions that would be suitable to them according to their needs or they may also prefer only low valued products. Changing churn behavior of customers when pricing or features of products are changed along with time is also an essential analysis that must be done by the company.

3. Developing a grievance redressal system

While using a company’s products, it is very likely that customers will have some issues with them at some point of time. Therefore, it is extremely essential that a company install a feedback system and also create a system of fast and reliable customer service. These things add up a lot to increase the overall customer experience over long durations of time.

4. Creating a new subscription model and improving renewal system

While a company may have designed their products and subscription models
to tend to the need of it’s customers, it may be better off if it can provide more tailor made packages and features to it’s customers. This will ensure that they get to pay only for the services that they actually need and do not end up paying extravagantly for services they have no use for.
The company should also focus on improving it’s renewal model by providing flexibility to it’s customers for auto-renewal or change of subscription plan during run-period of subscription of an already subscribed plan.
