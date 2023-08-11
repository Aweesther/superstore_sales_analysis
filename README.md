# Superstore Sales Analysis and Visualization
## Introduction
This presentation focuses on the data, analysis and interpretation of the Dataset “BamBam Superstores”. 

BamBam Superstores is a retail establishment that specializes in selling furniture, office supplies, technology products, and consumer products.

![image](https://github.com/Aweesther/superstore_sales_analysis/assets/140074432/2cc2cfc5-f860-42e6-99b8-67ffee5bb0ff)

The analysis and presentation of the data from the field was based on the objective of the study which included, sales, profits, customer ID, Segments, category, Ship modes, ship dates also including 9,801 customers.

Our project aims to analyze sales and customer data from the Bambam superstore sales database, with the sole intent of identifying trends and patterns that can inform business strategy and decision making.

The tool used to perform this is _Microsoft Excel_.

## STEPS TAKEN TO ANALYSE THE DATASET
**Data Cleaning Stage**

To begin, I took the essential step of cleaning up the data. To do this, I focused on the data in columns A to R, covering everything from the first row to the last. My goal was to spot and fix any duplicated entries and correct any typing mistakes. I also carried out a range of other data cleaning procedures to make sure that I had a polished dataset that I could use to create my dashboard.
  
After carefully addressing each quality issue, I confirmed that the data was now in great shape and ready for analysis.

- A new column was created for **_Month_** and **_Year_**

  ![image](https://github.com/Aweesther/superstore_sales_analysis/assets/140074432/69cfd2c1-6469-4757-8264-fb76690432dc)

**Answer Data Questions**
The aim was to answer the questions below
- Find the total Revenue generated:

The **“SUM”** function was used to generate results **_=SUM(W2:W9801)_** for  which **_$2,261,536.78_** was gotten.

- Find the highest Revenue generated:
The **“MAX”** function was used to generate results **_=MAX(W2:W9801)_** for which **_$ 2,263,848_**.

- Find the Lowest Revenue Generated:
**“MIN”** function was used to generate results **_= MIN(W2:W9801)_** in which **_$0.44_** was gotten.

- Total number of sales made:
The **“COUNT”** function was used to generate results **_=COUNT(W2:W9801)_** for which **_9801_** was gotten as the value.

- Number of cities where Business is Located:
**COUNTA** with the **UNIQUE** functions were used to generate results **_=“COUNTA”(UNIQUE(O2:O9801)_** which gave use **_529_** as the value.

- Determine the Customer responsible for Highest and Lowest Sales Generated by company:
The **“LOOKUP”** function was used here **_=XLOOKUP(A5,W2:W9801, L2:L9801, “NotFound”,0)_** the highest customer was **_Sean Miller_** while Lowest was **_=XLOOKUP(A6, W2:W9081,L2:L9801)_**.

- What is the total Revenue Generated in Kentucky:
The **“SUMIF”** function was used here **_=SUM(P2:P9801, “Kentucky”, W2:W9801)_**

![image](https://github.com/Aweesther/superstore_sales_analysis/assets/140074432/a3d65e59-e3ee-4ce3-afa1-dbdb3a1457cf)

**Pivot Table**
A pivot table is a table of grouped values that aggregates the individual items of a more extensive table within one or more discrete categories. 

A pivot table was used in this project to visualize some of the values.
- _Sales By Category_

  ![image](https://github.com/Aweesther/superstore_sales_analysis/assets/140074432/8d8377ff-6143-49b5-819d-e7cce3db05d7)

- _Sales by State_
  
  ![image](https://github.com/Aweesther/superstore_sales_analysis/assets/140074432/0a44315e-ae2e-48f8-b3c5-e8d34332e290)

- _Sales by Region_

  ![image](https://github.com/Aweesther/superstore_sales_analysis/assets/140074432/6bf2df21-1754-4293-987b-340bae552139)

- _Ship Modes and their Preference by Customers_

  ![image](https://github.com/Aweesther/superstore_sales_analysis/assets/140074432/195c120c-e71c-4230-9426-587ba4d08ae7)

- _Order of sales by Month_

  ![image](https://github.com/Aweesther/superstore_sales_analysis/assets/140074432/8550585e-b3b1-4662-98c2-e027286b6bec)

## DATA VISUALIZATION
The collected data were analyzed and presented using bar graphs, frequency table, column chart, Line chart and Doughnut chart. 

Also, l added two slicers for the dynamic part-one for the Month and the Year.

![image](https://github.com/Aweesther/superstore_sales_analysis/assets/140074432/0de187f4-8039-4362-9e25-965443035bd8)

## CONCLUSION
Visualization and Analysis of Various use case in the BamBam Superstore

1. We got some insight how ship modes varies by customers that can be used to improve the future

2. We also figured customers with the highest and lowest sales generated

3. We observed tendencies in the Month-and Year order placement

4. Generated where Business is located

## RECOMMENDATION
1. Phones, Chairs, Storage, Tables and Blinders should not be out of stock

2. Discount should be made available for the least performing products

3. California sales technique should be applied to other states in other to increase competition

4. Discount should be made available during the holiday season

5. Products like Technology and Furniture should be made Available.

_Thank you for taking your time to read this analysis, I’m open to corrections you can also contact me via [Linkedln](https://www.linkedin.com/in/oluwayemisi-awe-68a016213)._

Dataset credit to [Promise Chinonso](https://medium.com/u/abe7d3b593f?source=post_page-----7ccb709d90fa--------------------------------).

