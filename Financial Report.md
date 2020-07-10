# Unit 5 — How do you like them apps?

![Financial Planner](Images/financial-planner.png)

# Financial Report

In this section, I have included a financial report to demonstrate my calculations to the Consumer App Team. It has the the following sections:

1. **Budget Analysis:** Summarize the transaction data from the budget analysis and include images for each chart and table produced.
    Assumptions - 
        1. I have used plaid-python API to generate the correct authentication tokens to access data in the free developer Sandbox
        2. Used the client to generate a public token and requested the following items: ['transactions', 'income', 'assets'] for INSTITUTION_ID = "ins_109508"
        3. Use the access token to fetch the transactions for the last 90 days as of 8 July 2020
    Findings -
        1. Looked at categories for each transaction type, created a new DataFrame using the following fields from the JSON transaction data: date, name, amount, category. (For categories with more than one label, just use the first category label in the list)
        Convert the data types to the appropriate types (i.e. datetimeindex for the date and float for the amount)
        Test the access token by requesting and printing the available test accounts

2. **Retirement Planning:** Summarize the retirement portfolio analysis and include the charts for the Monte Carlo simulation.
    Assumptions - 
    Findings -


### Resources

* [Plaid API Docs](https://plaid.com/docs/)

* [AlpacaDOCS](https://alpaca.markets/docs/)

* [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)

---

### Submission

* Create Jupyter Notebooks for the analysis and planner and host the notebooks on GitHub.

* Include a Markdown Financial Planner report that summarizes your assumptions and findings and include this report in your GitHub repo.

* Submit the link to your GitHub project to Bootcampspot.

