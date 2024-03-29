# Case study
Adventure Works needs your help to analyze its sales data and create a Power BI report that visualizes this data in a meaningful way. Before the analysis can begin, the raw data must be cleaned and transformed to make sure it's accurate and consistent.
The company sends you the CSV file containing the raw dataset named SalesFile.csv. The dataset consists of important data related to recent sales, such as product categories, manufacturing prices, sales prices, units sold, and other similar details.
However, the file also contains errors like missing values, incorrect data types, and inconsistent formatting. Help Adventure Works to resolve these issues using Power Query editor so that they can produce an accurate and reliable report.
1. This exercise aims to assist you in understanding how to address common data issues such as missing values, incorrect data types, and inconsistent formatting.
2. By the end of this exercise, you’ll understand how to import, clean, and transform data in Power BI Desktop to ensure accurate and reliable analysis.

# Instructions
Create a new Power BI project called Exercise – Preparing a dataset. Follow the prompts below to complete the exercise.

## Step 1: Load the workbook
Download the Microsoft Excel workbook SalesFile.xlsx.
Import the SalesFile.xlsx Excel file as your dataset in Power BI.

## Step 2: Open the Power Query Editor
Open the Power Query editor to begin editing your data.

## Step 3: Address missing values
Locate and select the Units Sold column. 
Identify all null values within the column and replace them with a value of 0. 
Repeat this task for the Sale Price, Sales, and Profit columns.

## Step 4: Clean the Manufacturing Price and Sale Price columns
Locate and select the Manufacturing Price and Sale Price columns. 
Change the data type for both columns to Decimal Number.
Repeat this task for the Sales and Profit columns.

## Step 5: Clean the Discount Band Column
Select the Discount Band column. 
Locate each instance of value 1 in the column. Replace each instance of this value with None.
Then change the data type of the column to Text.

## Step 6: Clean the Units Sold column
Select the Units Sold column. Search for and locate all instances of the text value six hundred. 
Replace each instance of this text value with the numerical value 600.
Then change the column's data type to Whole Number.

## Step 7: Address inconsistencies in the Date column
Select the Date column. Ensure that the column’s data type is Date. 
The column also contains several null values. Replace all null values with the default date of March 03rd 2023. 
Next, select the Month Number column. Change the column's data type to Whole Number.

## Step 8: Drop records with errors
Select the Manufacturing Price column. The column contains errors in rows 6 and 38. Use the Remove Errors feature to drop these records. 
Repeat the same steps for the errors in the Sales and Profit columns.

## Step 9: Drop duplicate rows
You need to identify several duplicate rows that the dataset contains. 
Tip: Check the Products column
Once identified, remove these duplicate rows from the dataset.

## Step 10: Apply the data transformations
Once you have completed all the above data cleaning steps, select the Close & Apply button.
By completing this action, you can apply your transformations and update the dataset.

# Activity
Apply a pivot
In this activity, you will convert an Adventure Works Excel file called Product-Color Model.xlsx  that includes Product ID, Color, and Model data. You need to present the product count per color in a tabular format. To do this, you need to import the Excel data first and then pivot columns by using aggregate functions. Follow the steps below to apply a pivot in Power BI.

## Step 1: Select the data source type

## Step 2: Import Excel data
Import the Excel data to add the Product-Color Model query to the Queries pane. 
Observe the 3 columns in the table: Product Name, Color and Model. 
Remove the Product Name column. 

## Step 3: Pivot columns
To pivot the table columns, select the Product-Color Model query on the left menu. 
Select the Transform ribbon tab, followed by Pivot Column.
On the Pivot Column window that displays, select the Color column in the query and keep the value in Values column dropdown list. 
Expand the Advanced options and select option Count (All) from the Aggregate Value Function dropdown list, and then select OK. 

## Step 4: Examine the changes
By applying the Pivot Column, you change the way the data is organized. All distinct color values are converted to the column headers. There is just one row in the table, where every column has a matching count of that category in the previous rows. You can use this data to visualize in reports or dashboards, primarily in pie chart reports.


