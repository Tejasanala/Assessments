### SQL Assessment Instructions

**Assessment Overview:**
This assessment is designed to evaluate your proficiency in SQL through practical tasks encompassing data manipulation, query formulation, and complex joins and subqueries. The questions are based on a hypothetical advanced banking system that includes various types of accounts, such as savings and current accounts. Ensure to create your own data for testing your queries.

**Database Tables:**

1. **Customers:**

   - `customer_id` (Primary Key)
   - `first_name`
   - `last_name`
   - `DOB` (Date of Birth)
   - `email`
   - `phone_number`
   - `address`

2. **Accounts:**

   - `account_id` (Primary Key)
   - `customer_id` (Foreign Key)
   - `account_type` (e.g., savings, current, zero_balance)
   - `balance`

3. **Transactions:**

   - `transaction_id` (Primary Key)
   - `account_id` (Foreign Key)
   - `transaction_type` (e.g., deposit, withdrawal, transfer)
   - `amount`
   - `transaction_date`

4. **InterestRates:**

   - `interest_rate_id` (Primary Key)
   - `account_type` (e.g., savings, current)
   - `interest_rate`

5. **Branches:**
   - `branch_id` (Primary Key)
   - `branch_name`
   - `address`

**Questions:**

1. Insert at least 10 sample records into each of the following tables: `Customers`, `Accounts`, `Transactions`, `InterestRates`, `Branches`.
2. Write a SQL query to retrieve the name, account type, and email of all customers.
3. Write a SQL query to list all transactions along with the corresponding customer.
4. Write a SQL query to increase the balance of a specific account by a certain amount.
5. Write a SQL query to combine the first and last names of customers as `full_name`.
6. Write a SQL query to remove accounts with a balance of zero where the account type is savings.
7. Write a SQL query to find customers living in a specific city.
8. Write a SQL query to get the account balance for a specific account.
9. Write a SQL query to calculate the interest accrued on savings accounts based on a given interest rate.
10. Write a SQL query to find the average account balance for all customers.
11. Write a SQL query to calculate the average daily balance for each account over a specified period.
12. Identify accounts with the highest number of transactions ordered by descending order.
13. List customers with high aggregate account balances, along with their account types.
14. Identify and list duplicate transactions based on transaction amount, date, and account.
15. Calculate the total balance for each account type, including a subquery within the SELECT clause.

Please make sure to create your own data for these tables to test your queries effectively.
