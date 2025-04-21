# Mitron-Bank-Product-Strategy-Banking-Project
Power BI Project
### Project Overview
Mitron Bank is a legacy financial institution headquartered in Hyderabad.

They want to introduce a new line of credit cards, aiming to broaden its product offerings and reach in the financial market. 

AtliQ Data Services came to know about this through an internal link and approached Mitron Bank with a proposal to implement this project.
However, the strategy director of Mitron Bank, Mr. Bashnir Rover is skeptical and asked them to do a pilot project with the sample data before handing over them the full project. They provided a sample dataset of 4000 customers across five cities on their online spending and other details.

**Objective:** we have to guide them in tailoring the credit cards to customer needs and market trends. The successful acquisition of this project depends on the actionable, data-driven recommendations we provide to impress Mr. Bashnir Rover & his team.

This project is part of the Codebasics resume project [challenge](https://codebasics.io/challenge/codebasics-resume-project-challenge).

Please check the -
-  Live [Report](PENDING
-  Video [Presentation]

 ### Key Business Metrics
 - **Total Customers:** The total numbers of customers.
 - **Average Monthly Income:**  Indicates the monthly average income of the customer.
 - **Average Income Utilisation %:** This indicates the average income utilisation in percentage of the customer.
 - **Average Monthly Spend:** The average of each customer's personal monthly spending.
 - **Overall Average Monthly Spend:** Represents the average monthly spending across all customer combined.
 - **Total Spend:** The total spendings of customers.
### Discovering Datasets
Lets understand the dataset provided.

We have 1 [dimension](https://www.techtarget.com/searchdatamanagement/definition/dimension-table#:~:text=What%20is%20a%20dimension%20table,defined%20in%20a%20dimensional%20model.) table and 1
[fact](https://en.wikipedia.org/wiki/Fact_table) table as follows -

- dim_customers
     - customer_id
     - age_group
       - 21-24
       - 25-34
       - 35-45
       - 45+
     - city
       - Bengaluru
       - Chennai
       - Delhi NCR
       - Hyderabad
       - Mumbai
     - occupation
       - Business Owners
       - Freelancers
       - Government Employees
       - Salaried IT Employees
       - Salaried Other Employees
     - gender
       - Male
       - Female
     - marital_status
       - Married
       - Single
     - avg_income
  
 - fact_spends (This table is normalized and has more details which will help further in building reports)

   - customer_id
   - month
       - May
       - June
       - July
       - August
       - September
       - October  
   - category
       - Apparel
       - Bills
       - Electronics
       - Entertainment
       - Food
       - Groceries
       - Health & Wellness
       - Others
       - Travel
   - payment_type
       - Credit Card
       - Debit Card
       - Net Banking
       - UPI
   - spend
 ### Importing the dataset to Power BI
 These datasets are in CSV file format. We will import them to Power BI using the folder connector.
 ### Data Model
  For this project Star schema model is used.
  

         
