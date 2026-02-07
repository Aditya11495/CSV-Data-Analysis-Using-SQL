**CSV Data Analysis Using SQL**
**Overview**

This project shows how to import CSV files into a SQL database and perform common data analysis operations using SQL.

**Tools Used**
MySQL
SQL
CSV files

**Key Operations**
Loading CSV data into tables
Filtering and sorting data
Aggregations using SUM, COUNT, AVG
GROUP BY and HAVING
Subqueries and joins


**Purpose**
To practice real-world SQL queries and build a strong SQL portfolio project for Data Analyst roles

**QUERIES**

**CREATE TABLE read_csv (
    order_id INT,
    amount INT,
    profit INT,
    quantity INT,
    category VARCHAR(50),
    sub_category VARCHAR(50),
    payment_mode VARCHAR(30),
    order_date DATE,
    customer_name VARCHAR(100),
    state VARCHAR(50),
    city VARCHAR(50),
    year_month varchar(7));
    
LOAD DATA INFILE
'C:/ProgramData/MySQL/MySQL Server 8.0/Uploads/Sales Dataset_new.csv'
INTO TABLE read_csv
FIELDS TERMINATED BY ','
ENCLOSED BY '"'
LINES TERMINATED BY '\n'
IGNORE 1 ROWS;
);**



