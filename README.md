# Business-Request-from-Sales-Management

## 📝 Project Task

The business request for this data analyst project was an executive sales report for sales manager.

- Reporter: Sales Manager
- Value of Change: Visual dashboards and improved Sales reporting or follow up or sales force
- Necessary Systems: Power BI, CRM System
- Other Relevant Info: Budgets have been delivered in Excel for 2021-2023

## 🌟 **User Stories**

Based on the request that was made from the business company, the following user stories were defined to fulfill delivery and ensure that acceptance criteria were maintained throughout the project.

▪ Sales Manager	To get a dashboard overview of internet sales.	
Can follow better which customers and products sells the best.	
A Power BI dashboard which updates data once a day.

▪ Sales Representative	A detailed overview of Internet Sales per Customers.	
Can follow up my customers that buys the most and who we can sell ore to.	
A Power BI dashboard which allows me to filter data for each customer.

▪ Sales Representative	A detailed overview of Internet Sales per Products.	
Can follow up my Products that sells the most.
A Power BI dashboard which allows me to filter data for each Product.

▪ Sales Manager	A dashboard overview of internet sales.	
Follow sales over time against budget.	
A Power Bi dashboard with graphs and KPIs comparing against budget.

## ✏️ Data Cleansing & Transformation (SQL)

To create the necessary data model for doing analysis and fulfilling the business needs defined in the user stories the following tables were extracted using SQL.

One data source (sales budgets) were provided in Excel format and were connected in the data model in a later step of the process.

Below are the cleansed and transformed necessary data.

-DIM_Calendar: Cleansed DIM_Date Table

-DIM_Customers: Cleansed DIM_Customers Table

-DIM_Products: Cleansed DIM_Products Table

-FACT_InternetSales: Cleansed FACT_InternetSales Table

-FACT_Budget: Sent Over Data

# Data Model

Below is a screenshot of the data model after cleansed and prepared tables were read into Power BI.

This data model also shows how FACT_Budget hsa been connected to FACT_InternetSales and other necessary DIM tables.

![Data_Model](https://user-images.githubusercontent.com/122797480/229294923-92d967c1-54aa-47ea-94d8-d5c561c9efaa.jpg)
# Sales Management Dashboard

The finished sales management dashboard with one page which works as a dashboard and overview, with two other pages focused on combining tables for necessary details and visualizations to show sales over time, per customers and per products.

![Sales_Overview](https://user-images.githubusercontent.com/122797480/229293863-bc0a892e-cd06-4d00-ba34-98970c50c9af.jpg)
![Product_Details](https://user-images.githubusercontent.com/122797480/229294972-740cbe8b-13f6-448d-834d-b51bf89b9c71.jpg)
![Customer_Details](https://user-images.githubusercontent.com/122797480/229294987-f4d766af-6856-4181-936f-972dde1cb4e5.jpg)
