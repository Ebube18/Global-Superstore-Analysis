# Global-Superstore-Analysis

![Intro_image](https://github.com/user-attachments/assets/695aeb1d-e754-4377-94ff-887fad6dc329)


## Introductiom

This is a power BI project on sales analysis of an imaginary store called **Global Superstore**.
The aim of the project is to analyze and drive insight to answer crucial questions and help the store to make data driven decisions.

**_Disclaimer_**: _All dataset and report do not represent any company, institution or country, but just a dummy dataset to demonstrate capabilities of Power BI._

## Problem Statement

1. a) What are the three countries that generated the highest total profit for Global Superstore in 2014? b) For each of these three countries, find the three products with the highest total profit. Specifically, what are the products’ names and the total profit for each product?
2. Identify the 3 subcategories with the highest average shipping cost in the United States.
3. Assess Nigeria’s profitability (i.e., total profit) for 2014. How does it compare to other African countries? 
4. Identify the product subcategory that is the least profitable in Southeast Asia. Note: For this question, assume that Southeast Asia comprises Cambodia, Indonesia, Malaysia, Myanmar (Burma), the Philippines, Singapore, Thailand, and Vietnam.
5. Which city is the least profitable (in terms of average profit) in the United States? For this analysis, discard the cities with less than 10 Orders. 
6.  Which product subcategory has the highest average profit in Australia? 
7.  Who are the most valuable customers and what do they purchase?

## Skills and concepts demonstrated

The following power BI features were incorporated:
- Power query
- DAX
- Modelling
- Visualization

## Data Transformation and cleaning

Merged tables, Deleted column (80% empty), Created 3 dimension and fact table for easy data modelling, Changed data type.

## Data Modelling

![GS _ adjusted_data_model](https://github.com/user-attachments/assets/ccc78165-1c4d-451a-9f42-5a69de58e979)


Automatically derived relationships were adjusted and replaced with the required relationship.
There are 3 dimension and 1 fact tables and the dimension tables were joined to the fact table using the one-to-many relationship.

## Data Visualization and Analysis

![GS_a](https://github.com/user-attachments/assets/432337b8-05ec-4cc3-aed0-6ca610a3832f)

The slicers are filters to analyze the data by date, region, country or city. Using the Order date filter we can analyze he sales per year.

In 2014, United states generated the highest profit for global superstore, followed by India and then China.

1. In United States, the top 3 profitable products are
-	Canon Image Class2200 Advanced Copier at $15,679.95
-	Hewlett Packard LaserJet 3310 Copier at $3,632.93
-	GBC DocuBind TL300 Electric Binding System at $1,910.58

2. In India, the top 3 profitable products are
-	Sauder Classic Bookcase, Traditional at $2,419.65
-	Cisco Smart Phone, with Caller ID at $1,609.38
-	Hamilton Beach Refrigerator, Red at $1,440.24

3. In China, the top 3 profitable products are
-	Sauder Classic Bookcase, Metal at $1,463.07
-	Bush Classic Bookcase, Mobile at $1,220.52
-	HP Copy Machin, Color at $1,916.13

By filtering order date from 2011 to 2014 and country to United States, the top 3 sub-category with the highest average shipping cost are: Copiers, Machines and Tables.

Nigeria is the least profitable African country in 2014

The least sub-Category in southeast Asia is Tables

Least profitable city in United States by average profit is Lancaster

Sub-Category with the highest profit in Australia is Copier

Top 3 profitable customers are Tamara Chand (Canon Image Class2200 Advanced Copier) , Raymond Buch (Canon Image Class2200 Advanced Copier), Sanjit Chand (Tables).

## Conclusion/Recommendation

United States generated the highest profit.

Global superstore should reconsider offering products in Nigeria for now till proper measures are put in place to improve profitability, eg reducing average discounting and shipping cost.

Global superstore should stop offering tables to Indonesia, Thailand, Myanmar and Vietnam.

Thank you😊

![Conc_image](https://github.com/user-attachments/assets/ecca8d4a-8bcb-4d1c-80e6-e70c861f31b5)
