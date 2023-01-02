This repo is for my first complete data science project.  I'll be using the telco churn dataset to predict customer churn.

1) project description with goals

- Follow the data science pipeline (data acquistion, data preparation, exploratory data analysis and statistical testing, modeling, and model evaluation) and document code, findings, and keytakeaways and deliver a jupyter notebook final report

- Create modules (acquire.py, prepare.py) that make your process repeatable and your report (notebook) easier to read and follow.

- Ask exploratory questions of your data that will help you understand more about the attributes and drivers of customers churning. Answer questions through charts and statistical tests.

- Construct a model to predict customer churn using classification techniques, and make predictions for a group of customers.

- Refine your work into a Report, in the form of a jupyter notebook, that you will walk through in a 5 minute presentation to a group of collegues and managers about the work you did, why, goals, what you found, your methdologies, and your conclusions.

- Be prepared to answer panel questions about your code, process, findings and key takeaways, and model.


2) initial hypotheses and/or questions you have of the data, ideas
Does payment type impact churn? Does Mailed check payment have higher churn than electronic payment?  What payment types could be offered to reduce churn?
Does internet service type impact churn?  Does older technology service types like DSL  have higher churn than more modern technology like Fiber?
Does contract type impact churn? Do certain contract types have higher churn than others?
Does streaming movies or tv impact churn? Would investing more in streaming services reduce churn?
Does tenure impact churn?  Does tenure need to be rewarded to reduce churn?


3) data dictionary


| Feature | Definition |
|:--------|:-----------|
|payment_type| 1 = , 2 = , 3 = |
|contract_type|1 = , 2 = , 3 = |
|internet_service_type|1 = , 2 = , 3 = |
|gender| 1 = Male, 0 = Female|
|||




4) project planning (lay out your process through the data science pipeline)

1) Data Acquistion
    pull telco data from SQL server

2) Data Preperation
    clean/prep data, drop or rename columns as needed, change datatypes as needed

3) Exploratory Data Analysis and Statistic Testing
    use matplotlib and seaborn to plot data and look for trends/possible relationships

    use the appropriate statistics tests to check for relationship

4) Modeling

5) Model Evaluation



5) instructions or an explanation of how someone else can reproduce your project and findings (What would someone need to be able to recreate your project on their own?)



6) key findings, recommendations, and takeaways from your project.