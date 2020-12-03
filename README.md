# data_science_test_real

This is my solution to a real data science test taken when applying for a job in a real company.
The data scientist that was evaluating my application qualified it as "strong".

---

## Data Science Exercise

Key to the role is the ability to apply data science concepts and best practices to drive real business value.

### Challenge:
Files 'maus_sample.csv', 'members_sample.csv' and 'transactions_sample.csv' are dummy datasets of members, transactions and monthly active users (MAUs). The challenge is to use this data to illustrate your analytic, data engineering and modelling skills.

### Questions:

#### Python Executed SQL:
1. Read the three .csv files into three Pandas DataFrames: **transactions**, **members** and **maus**.
2. Add a column to the members DataFrame with the country’s (ipAddressCountryCode) income level using this API:
(https://datahelpdesk.worldbank.org/knowledgebase/articles/898590-country-api-queries). 
3. Convert members (with the income level column), transactions and maus into three tables in an empty MySQL database.
4. Ensure the columns are VARCHAR, INT and DATETIME where relevant.
5. Ensure that indexes are created on the tables to enable you to answer the following questions with optimized SQL queries: Which device has a larger proportion of premium members? Which Country has the oldest members (dobYEAR)? What is the average transaction value in GBP (Price) per country income level?
6. Answer the above questions, in SQL executed from Python.

#### Python Visualization and Modelling:
7. In Python plot the number of members by last click (refSource).
8. In Python plot MAUs by gender.
9. Plot MAUs by date.
10. Plot monthly transactions by income level.
11. Create a model to predict transactions, that could be used to get real business value.
12. Describe how you would use the model.

This is purposefully vague. The idea is to see how you would apply modelling in a sensible way -  you could do a classification, regression; predict how often, how much, if ever a member will transact - whatever makes sense to you.

We want to see how you would design the model, preprocess the data, train and test it. We also want to know how you would use that model to get real business value. But don’t spend too much time optimizing parameters or engineering elaborate features.
