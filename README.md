# Churn_modelling_EDA

**What is Churn Prediction?**
churn prediction can help one to foresee if the person is leaving so that you can have adequate time to prepare strategies to engage them. I have been busy these few weeks researching on this topic. In the area of HR, there are always a group of employees who tender their resignations even though they are doing well and the company wants to retain them. However, it is always too late to retain them as they have already been accepted of a better job offering by another company. Hence, why do we not engage the staff even before they start looking for other job opportunities? This is where Employee Churn Prediction comes into play.
Various techniques were used such as EDA (Exploratory Data Analysis), Cluster analysis and Churn prediction model. The main objective is to analyse the customers’ behaviour and develop a retention plan to lower the churn rate.

**How to start?**
Below are the general workflow on how to kickstart your churn prediction project. The main challenge will be the data collection process. We should collect as many data points as we have at different timestamps if possible.

1.Data collection
2.Data pre-processing
3.Exploratory Data Analysis (EDA)
4.Churn prediction model
5.Retention plan

**1. Data collection**
Data collection may sound easy, but what if your data is from multiple sources. Data on your employee may be difficult to collect especially on employees’ grades, relationship with supervisors/colleagues and their life events (e.g. marriage, parenthood and etc). We need to be clear of our project objective so that data collection can be simpler. Understanding our data is also critical especially during the next step — Data Preprocessing.

**2. Data pre-processing**
For instance, you are predicting employees who will leave within 6 months on a quarterly basis for the past 3 years. So, preprocessing is must.

**3. Exploratory Data Analysis (EDA)**
Before you start on EDA, you have to first group/transform your data into 3 categories — Numeric, Nominal and Binary and set your target column as Churn.
A correlation heatmap is also useful to check if there is any relationship between the input features.

**4.Churn prediction model**
Various models should be used to compare which model works better for the dataset. Popular models include Logistic Regression , Random forest and Gradient boosting . Hyperparameter Tunning process is also used to get the best parameters for each model.

**5.Retention plan**
The last step is to use the generated model on current data to find out the probability of churn. With the identified churn group, we can further group them into different risk factors — low, medium, high risk. Retention plan can be provided to the high risk group.



