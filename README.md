# Data analyst challenge
Welcome to the data analyst challenge. The purpose of this challenge is to assess your aptitude and skill with Structured Query Language (SQL). We at Robin pride ourselves on reporting accuracy, data integrity, and effective communication. In this challenge you will show us your skills in these areas by setting up tables in a SQL database, writing queries to answer 3 questions, and visually presenting your results. Visualizations can be done in your choice of tool such as MS Excel, Jupyter, etc. 

You have 5 days after receiving the challenge to return it to us. Email a zipped folder to your recruiter containing a single file for each SQL query, your data visualizations, and any supporting documents you'd like to include. We encourage the use of online resources like Stack Overflow.   

## Getting started
Grab the 3 csv files from this repo. These files contain sample sales data from a car dealership. Take these files and create a table in a database for each one. You can use any SQL database you prefer. We recommend using Postgres and have instructions below for how to set up your tables using PGAdmin.  

### Setting up a database with PGAdmin
If you do not already have PGAdmin on your computer, download and install it from here: https://www.pgadmin.org/download/

Once installed, launch PGAdmin. This will open the application in a web browser. Then follow the steps below to create your tables.
1. Create a schema by right clicking `Schemas` and selecting `create`. 
2. Create a table for each CSV file by right clicking `Tables` and selecting `create`.
3. In the create table dialog modal, add each column from the CSV and the appropriate datatype. 
4. Click on each table and go to Tools > Import/Export and select Import. Choose the file you are uploading and select `Yes` under Miscellaneous > Header.  


## Questions

### 1. Which product has the highest sales in 2003 and 2004?
Write a SQL query to show which product had the highest sales in the years 2003 and 2004. Your results should show the rank of every product, the product name, and the total sales of each product. You are only given the unit price and sales quantity, so total sales amount will need to be calculated. Did you filter some sales data out, and why?

Create a visualization to show your results. Be prepared to explain why you chose this visualization type, and why it works well for this data. 

### 2. What is the average, minimum, and maximum sales price per deal size?
Write a SQL query to determine the average sales price per deal size. Did you filter some sales data out, and why? 

BONUS: Compare the average to the median sales price. Do they align? Is there any significance to these results?  

Create a visualization to show your results. Be prepared to explain why you chose this visualization type, and why it works well for this data. 

### 3. What are the total sales, the most popular product, and largest contributing country all per region?
Write one or more queries to find the total sales per region, the most popular product line per region, and the country with the highest sales per region. Did you filter some sales data out, and why? 

Create one or more visualization(s) to show your results. Be prepared to explain why you chose this visualization type, and why it works well for this data. 

## Send us your results

Once you complete the challenge, zip all files and email them to your recruiter. They will share these with the hiring manager and the technical lead for your interview process. The results of this challenge, your SQL queries, and visualizations will all be discussed during the technical portion of your final interview. 
