# Sales-Insight
Sales Insights Data Analysis Project Using MySQL and Tableau
#Data Analysis Using SQL
1. Use any sales database (here i am using a dummy db) import it.
2. Peform Queries to Analize the database
3. For eg: 
#Show total number of customers
SELECT count(*) FROM customers;
#Show transactions where currency is US dollars
SELECT * from transactions where currency="USD"
#Show transactions in 2019 join by date table
SELECT transactions.*, date.* FROM transactions INNER JOIN date ON transactions.order_date=date.date where date.year=2019;
4. After Analyzing go to Tableu connect your MySQL database 
5. Clean your data (for eg : convert -1 Amount to 1 since amount cannot be -ve)
6. Create sheets (for eg : Total revenue, Total sales etc) seperatly
7. Create your dashboard 
