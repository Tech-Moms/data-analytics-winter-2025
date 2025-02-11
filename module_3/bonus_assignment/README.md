Tech-Moms Student SQL Analysis
In this assignment, you will use Deep Note, a data analysis tool, to explore the Tech-Moms applicant dataset using SQL. You will upload the applicant dataset into Deep Note and answer key questions to gain insights from the data.

Step 1: Create a Deep Note Account & Upload Data
Deepnote.com is a collaborative data science notebook platform designed for data analytics and data science work. It allows users to write and run code in SQL (as well as Python and R) directly within the browser, making it accessible and easy to use without requiring software installation.

[ ] Go to Deep Note and create a free account if you haven't already.
 
 Download:
 
[ ] 1. [electronic_items](https://github.com/ABura22/data-analytics-winter-2025/blob/main/module_3/bonus_assignment/electronic_items.csv) to solve the Question 1

[ ] 2. employee_data  and department_data to solve Question 2

[ ] 3. sales_data  to solve Question 3

[ ] 4. sales_data_2   and product_data to solve Question 4

[ ] 5. gap_sales_data to solve Question 5

[ ] 6. book_data and borrower_data to solve Question 6

[ ] 7. sales_data_3 to solve Question 7

   
 In Deep Note, create a new project.
 
 Upload the .csv file into your project.
 
Video: [Overview, Create a Deep Note Account, & Upload Data](https://www.loom.com/share/5fc400d191dd414088c900cadbc439e5?sid=80486bf3-c3b9-400d-897e-f8f82eabd741) 

Step 2: Get to Know Your Data
In order to get to know your data, you'll want to see a preview of the table. Use Deep Note's built-in SQL editor to explore the dataset.



To start, write the following query:

 SELECT
    *
 FROM [your_table_name]
 LIMIT 10;
Note: [your_table_name] will be the exact name of the csv file you uploaded in double quotes. See example below.

Screenshot 2024-09-12 at 8 31 52 AM
This will give you a preview of 10 rows so you can get to know what the data and columns look like generally.

Step 3: Step into the role of a data analyst

1. You have a table called electronic_items. Write an SQL query to find the average price of electronic items in each category, considering only categories where the average price exceeds 500 and at least 20 total quantity of items is available. Additionally, only include items with a warranty period of 12 months or more. Return the category name along with the average price of items in that category. Order the result by average price (round to 2 decimal places) in descending order.

2. You are provided with two tables: Employees and Departments. The Employees table contains information about employees, including their IDs, names, salaries, and department IDs. The Departments table contains information about departments, including their IDs and names. Your task is to write an SQL query to find the average salary of employees in each department, but only include departments that have more than 2 employees. Display department name and average salary rounded to 2 decimal places. Sort the result by average salary in descending order.

3. You are provided with the table:sales_data. Write an SQL query to retrieve the total sales amount for each product category in the month of February 2022, only including sales made on weekdays (Monday to Friday). Display the output in ascending order of total sales.

4. You are provided with two tables: Products and Sales_2. The Products table contains information about various products, including their IDs, names, and prices. The Sales table contains data about sales transactions, including the product IDs, quantities sold, and dates of sale. Your task is to write an SQL query to find the total sales amount for each product. Display product name and total sales. Sort the result by product name.
   
5. You have a table called gap_sales. Write an SQL query to find the total sales for each category in each store for the Q2 (April-June) of 2023. Return the store ID, category name, and total sales for each category in each store. Sort the result by total sales in ascending order

6. You are provided with two tables: borrower_data, book_data. Imagine you're working for a library and you're tasked with generating a report on the borrowing habits of patrons. You have two tables in your database: Books and Borrowers.Write an SQL to display the name of each borrower along with a comma-separated list of the books they have borrowed in alphabetical order, display the output in ascending order of Borrower Name

7. You are provided with sales_data_3. Write an SQL query to retrieve the total sales amount for each product category in the month of February 2022, only including sales made on weekdays (Monday to Friday). Display the output in ascending order of total sales.


