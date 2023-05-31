# Diwali_Sales_Analysis-using-Python
![image](https://github.com/shubham250298/Diwali_Sales_Analysis-using-Python/assets/108235140/4a497ad9-25a8-4837-a708-9d819f603cd3)
# Diwali Sales Analysis: Exploratory Data Analysis using Python
## Description
This project focuses on analyzing Diwali sales data to gain insights and perform exploratory data analysis (EDA) using Python. The analysis aims to understand sales patterns, trends, and correlations in the dataset.
## Table of Contents
- [Importing Dependencies](#Importing-Dependencies)
- [Data Description](#data-description)
- [Data Cleaning](#data-cleaning)
- [EDA Steps](#eda-steps)
- [Results and Findings](#results-and-findings)
- [Technologies Used](#technologies-used)

## Importing Dependencies
we have imported following python Libraries
Numpy, Pandas, Matplotlib, Seaborn

## Data Description
The dataset used for this analysis contains Diwali sales data for a specific period. The data is provided in CSV format and includes the following columns:
- User_ID  :   The Id of person
- Cust_name  :   Customer Name
- Product_ID  :   Id of each product
- Gender :   Gender of each person
- Age Group  :   Age range for person
- Age :   age of each person
- Marital_Status :   Married person was represented by 1 and unmarried by 0
- State :   State from which person belongs
- Zone :   In which zone person belongs
- Occupation  :   Occupation of each person
- 	Product_Category : different category of products
- 	Orders :  Number of orders
- 	Amount :   Amount spend by customer
- 	Status  :  Blank column
- 	unnamed1  :  Blank column 


In the dataset there are 11251 rows and 15 columns.

## Data Cleaning
In our Dataset there are 2 columns which are blank columns named 'Status' and 'unnamed1', so firstly we remove both the columns.
Now we check for null values in dataset and remove these null values.


##  EDA Steps
- We create Bar chart with the help of seaborn library between Gender and count and another one between Gender and Amount 
We can see that most of the buyers are females and even the purchasing power of men are lesser than female
-Now we create barplot between Age group and count  and another between Total Amount and age group.
From  graphs we can see that most of the buyers are of age group between 26-35 yrs female







