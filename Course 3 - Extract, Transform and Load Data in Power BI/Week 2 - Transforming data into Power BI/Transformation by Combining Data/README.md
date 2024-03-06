# Case study
Adventure Works has data with details, such as Sales Order ID, Order Date, Product Key, Quantity, Unit Price, Reseller Key, Product, Reseller and some other fields are stored in separate tables. These tables have a relationship with the Sales table because of the relational data architecture. 
As you have learned before, although this relational data structure provides data integrity, it only shows the key values. To list the other details of the related tables, you must merge tables with joins. 
Your manager, Adio Quinn, has assigned a task to you to list the Sales data with the Sales Order ID, Order Date, Product Name, Quantity and Unit Price columns. To do this, you must merge the Sales and Product tables by creating a Power BI query that merges the data.
Adio sends you the two .xlsx files containing the Adventure Works company sales data named Sales.xlsx, and product data named Product.xlsx. The data sets have a common column named ProductKey. You will use the common column and match the columns. You need to read data from the two tables.

1.This exercise aims to assist you in understanding how to combine data by merging data.
2. By the end of this exercise, you’ll understand how to merge data in Power Query, to explore the relationships between two tables and match the related data.

## Step 1: Download the Excel files
Download the Sales.xlsx and Product.xlsx files, which will be used in this exercise.

## Step 2: Create a Power BI project
Create a Power BI project and open the Power Query editor. 
Create a new Power BI project called Exercise – Merging two tables. 

## Step 3: Open the Power Query Editor
Open the Power Query editor and import your datasets, Sales and Product.

## Step 4: Merge queries
After selecting the Sales data in the Queries pane, select Merge Queries. 
In the opened window, the Sales table will be shown automatically in the upper section of the window. 
Choose the next table for merging, which is Product.
ProductKey is the common column between the tables, so click on the ProductKey columns in each table. 
For the Join Kind dropdown, choose the join type Left Outer Join, which selects all records from the left table and matching records from the right table.

## Step 5: Select column(s) from Product
After you merged the tables, a new column, named Product is added to the right side of the Sales data. This allows you to choose columns from the Product table. 
Select the column named Product from the Product table. 

## Step 6: Choose and reorder columns from Sales
After you add the new column, Product, it is added to the Sales query as Product.Product. You must rename this column as Product  to avoid confusion. 
Move the Product field from right to left.
Remove the unwanted columns,  Product Key (name of product is added by merge, so you will not need the key value of product), Reseller Key, Employee Key and Sales Territory Key columns.
Reorder the final list as indicated in your task to Sales Order Number, Order Date, Product, Quantity and UnitPrice.
