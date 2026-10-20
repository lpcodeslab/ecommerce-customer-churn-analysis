# ecommerce-customer-churn-analysis
SQL-based e-commerce customer churn analysis project using customer behaviour, tenure, payment preferences, satisfaction scores, complaints, and order history to explore customer retention patterns.
## 📖 The Project.....

The E-Commerce Customer Churn Analysis project focuses on exploring customer data using SQL and MySQL to understand customer churn and retention patterns.

The project uses a database named `ecomm` and a table named `customer_churn`, which contains customer-related information such as tenure, payment preferences, satisfaction scores, complaints, order history, and churn status.

The main purpose of this project is to apply SQL techniques to organise, retrieve, and analyse customer data. The analysis aims to identify patterns that may be associated with customer churn and provide insights that could help an e-commerce business improve customer satisfaction and retention.

### Project Goals

- Understand customer churn behaviour.
- Explore customer characteristics and purchasing patterns.
- Analyse customer data using SQL queries.
- Investigate factors potentially associated with churn.
- Develop data-driven ideas for improving customer retention.

## ⚙️ Procedure

### Step 1: Database Creation

Create a database named `ecomm` to store the customer churn data.

```sql
CREATE DATABASE ecomm;
USE ecomm;
```

### Step 2: Table Creation

Create a table named `customer_churn` with the appropriate columns and data types to store customer information.

The table structure should match the `CREATE TABLE` statement in the provided SQL script.

### Step 3: Data Insertion

Execute the `INSERT INTO` statements in the SQL script to populate the `customer_churn` table with customer records.

### Step 4: Data Verification

Check that the records have been inserted successfully.

```sql
SELECT *
FROM customer_churn;
```

Check the total number of records:

```sql
SELECT COUNT(*) AS total_customers
FROM customer_churn;
```

### Step 5: Data Exploration

Explore the dataset to understand its structure and the information available for analysis.

Examples include checking customer tenure, payment preferences, satisfaction scores, complaints, order history, and churn status.

### Step 6: Customer Churn Analysis

Use SQL queries to investigate customer churn patterns. Possible analyses include:

- Counting churned and retained customers.
- Calculating the overall churn rate.
- Comparing churn rates across customer groups.
- Exploring the relationship between customer tenure and churn.
- Investigating whether satisfaction scores or complaints are associated with churn.
