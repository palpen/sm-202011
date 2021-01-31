# Sunday, 31 January 2021

# How to explain projects to a business person
## Loan Default Project
- Objective:
    - Using accepted loan application data, the goal is to predict which customers are going default on their loan
- Approach
    - The model uses demographic, past credit history information (FICO score, current outstanding loans) and other historical banking information of customers (income, days with the bank, etc) and historical data on the current status of the loan (whether it was fully paid off or in default).
    - To predict future outcomes, I train a binary classification model that predicts when a customers is in default or not in default
- Results
   - Using future data (data that was not seen by the model), I was able to predict 40% of actual cases of customers who defaulted relative to not having model. (TO ADD)
    - These 40% of defaulted loans represent X$ of credit which is roughly X% of the total amount of all the applications that defaulted in the sample (which is around X$)

## Sales Forecasting
- Objective
    - Build a model that can provide a two-week forecast of quantity demanded for each 4500 items across 54 stores
- Approach
    - Used historical data on store by item level number of unit sold
    - To predict future unit sold, I train a regression model using the historical sales and promotion data. For example, I created variables representing volatility in the items sold in past 3, 7, 30 days, or the average number of units sold for past 3, 7, 30 days. I also use historical information on when a given item was being promoted in the store (e.g. item was on sale, or was placed in brochure, etc)
- Results
    - How to tie to business outcomes: becasue this is a kaggle competition, no business baseline
   - But if I was actually working for this grocery chain I would
        - Ask the business for the current approach they use to forecast demand
        - Compare the forecast of my model over the two week time horizon and compare it with the forecast of the current approach over the same time horizon
        - Business impact: compare average deviation from actual demand between my model and current approach.


# Saturday, 19 December 2020
- X Project 1 feedback
- X Project 2
    - Work in progress
- X Reschedule session missed on Thursday
    - Continue on Saturday
- X Resume review
    - Reschedule for this afternoon
- Sharpestmind job resume and job interview feedback


# Saturday, 12 December 2020

- X Review final solution for project 1
    - Fill in README explaining source code and main insight and findings from project
    - Merge branch to main (the master branch)
- Plan project 2
- Schedule for remaining sessions
    - Job search timeline? Find job within a month
        - Check Scotiabank jobs
    - Resume review
        - Add projects to resume
        - Edit current resume (Palermo)
        - Reach out to Alejandro for help with Resume, job search strategy, etc. (Srujana)
    - Interview practice
        - Project review, key insights, explain methodology in detail
        - Schedule practice technical interviews
    - Job applications
        - Start applying to 2 to 3 jobs per day (Srujana)
