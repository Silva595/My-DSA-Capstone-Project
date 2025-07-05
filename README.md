# My_DSA_Capstone_Project

This is the beginning of my portfolio building towards a success tech journey after my classes with the incubator hub
I have been task with three diffeent aspect of the project, Excel, SQL and Powerbi. I choose to do the Excel and SQL section of the project.
Started with the Excel project where I had to cleaned and structure the data.
I also went on to create new columns while applng severl excel functions

## Project Topic: Amazon Product Review Analysis

### Project Overview
This is a Data Analysis project of RetailTech Insights, a company that provides e-commerce analytics solutions to sellers on platforms like Amazon and as a Junior Data Analyst at the company, Amazon product review data was analyzed. Involving data collection, data cleaning and processing, exploration of analysis and Visualizations.

The aim is to analyze products and customer review data to generate insight that can guide product improvement, marketing strategies, and customer engagement. Also to identify trends in pricing, discounts, engagements through the rating and rating counts by products and category to support data-driven decision-making. Using Microsoft Excel, the project delivers key performance metrics and visualizations to highlight product performance and customer behavior while further creating new columns and applng several excel functions. 

### Data Sources
The primary source of Data here is Amazon Case Study.xlsx which was provided by the facilitators of the Incubator hub for educational purpose.

### Tools Used
- Ms Excel for data cleaning
  1. data collection
  2. data cleaning
  3. data preparation
 - Github for portfolio building.
    
  ### Data Collection, Cleaning and Preparation
  During this phase we perform the following
  1. Data loading and inspection
  2. Look out for missing varables and duplicated values 
  3. Data cleaning and formatting
  4. Several new columns were created using multiple excel functions namely TEXT,LEFT,IF,AND,FIND,SUM.
  5. Data type was changed where necessary
  6. Currency signs were added where it involves money
  7. Bar charts where added for visualizaion
     
  ### Exploratory Data Analysis
  
  This process involves the use of functions, pivot tables and charts to answer some question such as; 
  - What is the average discount percentage by product category?
  - How many products are listed under each category?
  - What is the total number of reviews per category?
  - Which products have the highest number of reviews?
  - What is the average actual price vs the discounted price by category?
  - Which categories have products with the highest discounts?
 
    ### Data Analysis
    
  Functions were used in the process of this analysis
  - Discount range bucket =IF(K2>=50%,"50% or More","<50%")
  - Discount range =[@[Discount_percentage]]<=40%,"31-40%",IF([@[Discount_percentage]]<=50%,"41-50%",IF([@[Discount_percentage]]<=60%,"51-60%",IF([@[Discount_percentage]]<=70%,"61-70%",IF([@[Discount_percentage]]<=80%,"71-80%",IF([@[Discount_percentage]]<=90%,"81-90%","91-100%")))))))))
  -  Average discount pecentage by product =([@[Actual_price]]-[@[Discounted_price]])/[@[Actual_price]]*100


