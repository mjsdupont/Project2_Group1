# Project2_Group1 Group Members: Maria Jose Dupont, Ali Khan, Keerthy Reddy
## This mini project involves extracting and transforming data from Excel files to create several data frames and ultimately a crowdfunding database. Here's a breakdown of the tasks:

## Create the Category and Subcategory DataFrames:

-Extract data from the "crowdfunding.xlsx" file to create a category DataFrame containing sequential category IDs and corresponding category titles.
-Export this DataFrame as "category.csv".
-Similarly, extract data to create a subcategory DataFrame with sequential subcategory IDs and titles, and export it as "subcategory.csv".

## Create the Campaign DataFrame:

-Extract and transform data from "crowdfunding.xlsx" to create a campaign DataFrame with various columns including campaign ID, contact ID, company name, description, goal, pledged amount, outcome, backers count, country, currency, launch date, end date, category ID, and subcategory ID.
-Export this DataFrame as "campaign.csv".


## Create the Contacts DataFrame:

Choose between two options:
-Option 1: Use Python dictionary methods.
-Option 2: Use regular expressions.

Option 1: Import "contacts.xlsx" into a DataFrame, convert each row to a dictionary, extract values, split names into first and last names, and export the DataFrame as "contacts.csv".

Option 2: Import "contacts.xlsx" into a DataFrame, extract specific columns using regular expressions, convert contact IDs to integers, split names, and export the DataFrame as "contacts.csv".


## Additional Notes:
-To split category and subcategory columns, use str.split() function.
-To create unique category and subcategory IDs, use NumPy arrays and list comprehensions.
-Convert specific columns to float data type using astype() method.
-Convert UTC times to datetime format.
-Use DataFrame merging to add category and subcategory IDs to the campaign DataFrame.

By following these instructions, you can successfully create and export the necessary data frames required to build the crowdfunding database.

This summary provides a comprehensive overview of the tasks involved in the mini project. Follow the provided instructions for each subsection to complete the project successfully.

## Resources
Contained within this document are all outputs generated from the source code
## crowdfunding_db
Contained within this directory are all the screenshots of the database we have constructed
## ETL_Mini_Project_MJDupont_AKhan_KKota.ipynb
Within this file, you will find the source code. 
