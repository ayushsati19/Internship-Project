## Problem Statement:
Sales management has gained importance to meet increasing competition and the need for improved methods of distribution to reduce cost and to increase profits. Sales management today is the most important function in a commercial and business enterprise.

ETL process.

Do ETL : Extract-Transform-Load some Amazon dataset and find for me
Sales-trend -> month wise , year wise , yearly_month wise

Find key metrics and factors and show the meaningful relationships between attributes.
Do your own research and come up with your findings.


## Data Description:
The Dataset consists of following columns:

1. Region: Region where countries belong.
2. Country
3. Item Type: Type of item that was sold.	
4. Sales Channel:	medium through which item was sold (Online/Offline).
5. Order Priority: Priority given for the order.
6. Order Date: Date on which item was ordered.
7. Order ID: Id of the item that was sold.
8. Ship Date:	Date on which item was shipped.
9. Units Sold: Total units of items that were sold on that day.
10. Unit Price:	Selling Price of one unit of the item.
11. Unit Cost: Cost price of that item.
12. Total Revenue:	Total selling price of the items sold. 
13. Total Cost: Total cost price of the no. of items that were sold on that day.
14. Total Profit: Total profit on selling the items(Total revenues-Total Cost).

## Tools Used:
**1. Programming Language: Python**

**2. Python Libraries: Numpy, Pandas,Seaborn,Matplotlib**

**3. Business Intelligence Tools: Excel, Tableau**

## Project Steps
**Data Import & Data Cleaning**

The dataset was initially stored in a CSV file, and to ensure its cleanliness and readiness for further analysis, it was checked using the Pandas library in Python. Specifically, the dataset was assessed for missing data, duplicate records, and incorrect data types.

Upon inspection, it was found that the dataset was complete, with no missing data or duplicate records. Additionally, there were no incorrect data types detected, meaning that the data was structured correctly and in the appropriate formats. Overall, the dataset was deemed to be clean and suitable for further analysis.

**Data Importing in Tableau**

In Tableau, we have options to connect to our dataset via various options such as SQL Server, MYSQL, excel or CSV files. We have our clean data in a CSV file. We will import it in Tableau with the import data option and start working with it.
