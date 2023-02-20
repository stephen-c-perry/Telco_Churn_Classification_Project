# Telco Churn Classification Project


I'll be using the telco churn dataset to find drivers of churn and predict which current customers will churn.  This is important because it will help Telco retain customers and improve customer satisfaction.

1) Goals

- Follow the data science pipeline (data acquistion, data preparation, exploratory data analysis and statistical testing, modeling, and model evaluation) and document code, findings, and keytakeaways and deliver a jupyter notebook final report

- Create modules (acquire.py, prepare.py) that make process repeatable and final_report notebook easier to read and follow.

- Ask exploratory questions of data that will help to understand more about the attributes and drivers of customers churning. Answer questions through charts and statistical tests.

- Construct a model to predict customer churn using classification techniques, and make predictions for a group of customers.

- Refine work into a final report, in the form of a jupyter notebook, that I will walk through in a 5 minute presentation to a group of collegues and managers about the work I did, why, goals, what I found, methodologies, and conclusions.


2) Initial questions I have of the data, ideas
- Does payment type impact churn? Does Mailed check payment have higher churn than electronic payment?  What payment types could be offered to reduce churn?
- Does internet service type impact churn?  Does older technology service types like DSL have higher churn than more modern technology like Fiber?
- Does contract type impact churn? Do certain contract types have higher churn than others?
- Does streaming movies or tv impact churn? Would investing more in streaming services reduce churn?
- Does tenure impact churn?  Does tenure need to be rewarded to reduce churn?


3) Data Dictionary

| Feature | Definition | Values |
|:--------|:-----------|:-------
|gender| The customer's gender| Male or Female|
|senior_citizen| Is this customer a senior citizen?| {'Yes': 1, 'No': 0} |
|partner| Does this person live with a partner?|'Yes', 'No'|
|dependents| Does this person live with dependents?| 'Yes', 'No'|
|tenure| The number of **months** a customer has been with the company| *float* |
|phone_service| Does this person subscribe to phone service?| 'Yes', 'No'|
|multiple_lines| Does this person have multiple phone lines?| 'Yes', 'No', 'No phone service'|
|online_security| Does this person subscribe to online security?| 'Yes', 'No', 'No internet service'|
|online_backup| Does this person subscribe to online backup?| 'Yes', 'No', 'No internet service'
|device_protection| Does this person subscribe to device protection?| 'Yes', 'No', 'No internet service'
|tech_support| Does this person subscribe to tech support?| 'Yes', 'No', 'No internet service'
|streaming_tv| Does this person subscribe to streaming TV?| 'Yes', 'No', 'No internet service'
|streaming_movies| Does this person subscribe to streaming movies?| 'Yes', 'No', 'No internet service'
|paperless_billing| Does this person use paperless billing?| 'Yes', 'No'
|monthly_charges| The amount a customer is currently charged per month| *float* |
|total_charges| The amount a customer has been charged since becoming a customer| *float* |
|contract_type| The length of contract the customer currently has| 'Month-to-month', 'One-year', or 'Two-year'|
|internet_service_type| Type of internet service | 'DSL', 'Fiber', 'None'|
|payment_type| The way the customer pays their bill. |'Mailed check', 'Electronic check', 'Credit card (automatic)', 'Bank transfer (automatic)'
|**Target variable**
|churn_encoded| Did the customer leave the company? | {'Yes': 1, 'No': 0}|



4) Project Planning

1) Data Acquistion
    pull telco data from SQL server

2) Data Preperation
    clean/prep data, drop or rename columns as needed, change datatypes as needed

3) Exploratory Data Analysis and Statistic Testing
    use matplotlib and seaborn to plot data and look for trends/possible relationships

    use the appropriate statistics tests to check for relationship

4) Modeling
In order to make predicitions on which customers will churn I will use several classification models. 

5) Model Evaluation
 I'll compare the accuracy of each model to the baseline and identify the most accurate model.


5) To reproduce my results download the dataset at the link below:
https://www.kaggle.com/datasets/blastchar/telco-customer-churn

Then clone this github and run the notebook final_report.ipynb

6) Recommendations

To increase customer retention, consider offering discounts for 2 year contracts.  Doing this will address two drivers of churn with one change (shorter contracts and higher monthly charges).  Additionally, consider doing a customer satisfaction survey to see if there are problems with the fiber optic service or if it needs to be improved because of new competition.