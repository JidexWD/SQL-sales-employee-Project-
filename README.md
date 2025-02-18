# SQL-sales-employee-Project-
A database project showcasing SQL and Excel as a data analytics tools


## Table of Content 
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools](#tools)
- [Project Structure](#project-structure)
- [Data Analysis](#data-analysis)
- [Data Visualiation](#data-visualization)
- [Results](#results)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
## Project Overview 
stake holders want to know the overview they made of sales for year 2004. they would like to see the break down by product, country and city, also they want the sales value, cost of sales and net profit.
  
## Data Source
  Company's database 

  Data entered manually with mysql 
  ![image](https://github.com/user-attachments/assets/828fc66e-5744-4e81-953f-4c9c2095311c)

## Tools
  MYSQL workbench | Ms Excel 
## Project Structure
  Data
  - Data Collection
     Data collected from the company books 
  - Data Overview
    after data has been setup on mysqql database it can now be cleaned and transformed for queries and analysis
    ![image](https://github.com/user-attachments/assets/f4d6e16a-6b06-497d-b519-4df110fd5163)

    from the side you can see the full database and an overview of the orders table 

    
 
  - Data Transfromation
    ![image](https://github.com/user-attachments/assets/d78529cb-436e-46d4-a207-df2fd6c0a07a)

    tables are joined to extract multiple columns and the result of the query is then copied and sent to excel

    ![image](https://github.com/user-attachments/assets/4c2cd19f-ec8e-4a94-ab03-b286c9c44b94)
    now the needed data has been correctly tranfered to excel and wee can carry out analysis 
 
## Data Analysis 

we maker 3 new columns the salesvalue, cost of sales, net profit 
sales value = byPrice * QuantityOrdered
cost of sales = buyprice * quantityordered
netprofit = cost of sales - sales value 

![image](https://github.com/user-attachments/assets/6d58461b-02af-4abc-9698-50e6798b5057)

now we  make the product overview using pivot table 
sum cost of sales 

![image](https://github.com/user-attachments/assets/d616ab5c-aa78-4854-b864-b6b4da4aaa21)

sum of sales value 

![image](https://github.com/user-attachments/assets/c770ecb9-a46e-4b0f-8c45-663ee9cce4d7)

sum of net profit
![image](https://github.com/user-attachments/assets/78539435-2eb9-44f5-8dfc-8e870dd166aa)


now we look at sales overview by country

![image](https://github.com/user-attachments/assets/2e95b527-85c1-4785-872a-e1130aa678c7)


  
 
  
     
     
