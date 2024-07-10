# Sentiment Analysis
 Before launching new products, companies engage 
in market testing. It's crucial for them to thoroughly 
understand and analyze customer sentiments expressed in 
reviews, particularly regarding health and personal care 
products
The motivation behind this project stems from the 
observation that customers often churn or disengage from 
products/services when their sentiments or concerns 
expressed in reviews are not adequately addressed by 
companies. By analyzing these sentiments, we aim to 
uncover valuable insights into customer pain points, 
satisfaction levels, and areas for improvement. Addressing 
these sentiments can lead to enhanced customer retention, 
loyalty, and ultimately, improved business performance
Who: The stakeholders involved in our project include:
Reviewers: Customers who provide feedback , reviews 
Product Companies: Manufacturers and sellers of health 
and personal care products who are interested in analysing
customer feedback to improve products and services.
E-commerce Platforms: Online platforms where
customers leave reviews and purchase. They benefit from 
improved customer satisfaction and engagement

Data Sources
We obtained our data from an open data source of Stanford 
Large Network Dataset Collection (link)
Collecting Data
In the future, we can collect data from product reviews 
across multiple online e-commerce platforms
Features
Our data contains review text, ID of the reviewer, product 
ID, time of the review, helpfulness of the review, overall 
rating, summary of the review
Building Models
We created machine learning models like logistic 
regression, SVC, and random forest to understand the 
sentiments. We have tested our model on a size of 0.2. We 
can update the models every 3 months or when there is a 
new product to be launched


The predictions provide insights into how customers 
perceive the products. This can further be used to make 
decisions related to product launches and improvisations. It 
also helps prevent customer churn by staying on top of 
customer feedback and making changes quickly


Before deployment, we conducted an in-depth analysis 
using metrics such as confusion matrix, ROC AUC, 
precision, and recall scores. These metrics helped us 
assess the model's fit with the data and its accuracy in 
predicting sentiments.
