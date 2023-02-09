# dsc-phase-3-project-
# Customer Churn Analysis
This project aims to build a machine learning model to predict customer churn for a telecom company. The model will use the customer data to identify the key factors that influence churn and the company can then use these insights to develop strategies to reduce churn.

## Data Source
The data for this project was obtained from Kaggle and contains information on 3,333 records and 21 features. The features include:
* state                      object
* account length              int64
* area code                   int64
* phone number               object
* international plan         object
* voice mail plan            object
* number vmail messages       int64
* total day minutes         float64
* total day calls             int64
* total day charge          float64
* total eve minutes         float64
* total eve calls             int64
* total eve charge          float64
* total night minutes       float64
* total night calls           int64
* total night charge        float64
* total intl minutes        float64
* total intl calls            int64
* total intl charge         float64
* customer service calls      int64
* churn                        bool

## Methodology
The analysis used a Random Forest Classifier as the final model that produced the best results.

* The key steps in our methodology were:
* Business Understanding
* Data Understanding, 
* Data Preparation, 
* Modeling, 
* Hyper-parameter tuning
* Model Evaluation, 
* Deployment.

### Business Understanding

Customer churn is the loss of clients by a company. This is a major problem for businesses since retaining customers is cheaper than acquiring new ones.
#### Impact on Business:
High customer churn rates can result in decreased revenues and consequently profits.
The cost of acquiring new customers is high with high budgets going into marketing and sales.
Additionally, lost customers can portray a bad image of a company.
#### Need for a Solution:
For a company to remain competitive it is necessary to understand the reason behind customers leaving and take necessary steps to mitigate this.
An effective solution to customer churn can help businesses improve customer satisfaction, increase retention, and ultimately drive growth and success.

### Data Understanding
Involves Data description interms of distribution and data types.
Data Cleaning: Dealing with missing values and duplicates.
Data Preparation: Encoding categorical variables, Splitting the data into training, testing sets and scaling.

### Modelling

Implementing a Random Forest Classifier
Tuning the model with Grid Search

### Model Evaluation

Evaluating the model's performance with metrics such as accuracy, precision, recall and F1 score

## Key Findings
The key findings of the analysis include:

### The model scores:
accuracy of 0.937
Precision: 0.759
Recall: 0.856
F1 Score: 0.805
### The most important features that contribute to customer churn are:
Customer service calls
Total day minutes
Total day charge
Total international calls
Total evening charge


## Recommendations
Based on the key findings, the following recommendations can be made to reduce customer churn:

### Improving customer service: 
Given that customer service calls and total day minutes are the most important factors contributing to customer churn, the telco should focus on better customer support, training agents, and continuously monitoring and evaluating the customer service process.
### Offer more tailored plans: 
The telco can consider offering more customized plans to customers based on their usage patterns, preferences, and budgets. This can help retain customers and reduce churn.
### Monitor usage patterns: 
Keeping track of customers' usage patterns, such as total day charge and total international charge, can help identify customers at risk of churning. The telco can then take proactive steps to retain them.
### Evaluate pricing strategies: 
The telco can review their pricing strategies and see if they are competitive. By adjusting prices, offering discounts, or bundling services, the telco can reduce the risk of customers switching to other providers.


## Limitations
The limitations of this analysis include:

Limited data
Complexity of random forests
The scores are not perfect.

## Conclusion
The customer churn analysis provides valuable insights for the telecom company on how to reduce customer churn. Implementing the recommended strategies can lead to increased customer retention and ultimately improve the company's bottom line. Further research and analysis is needed to improve the accuracy of the model and refine the recommendations.
