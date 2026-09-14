# Excel_data_exploration

**Introduction**

This project demonstrates the use of fundamental Excel functions for data analysis on a product dataset. The dataset contains information such as Product ID, Product Name, Brand, Price, Quantity, and Category.The objective was to perform basic statistical analysis, categorize products based on price, analyze products by category, and extract useful information from Product IDs using Excel formulas.The analysis focuses on commonly used Excel functions including SUM, COUNT, AVERAGE, MIN, MAX, IF, SUMIF, COUNTIF, LEFT, RIGHT, and MID. 

**Dataset Overview**

The dataset consists of 34 product records with the following fields:

Product ID: Unique identifier containing day, month, and country information

Product Name:	Name of the product

Brand Name:	Product's brand

Price ($):	Price of the product

Quantity: Available quantity

Category:	Product category

Price Range:	Classification based on product price

Day:	Day extracted from Product ID

Country Code:	Country code extracted from Product ID

Month: Month extracted from Product ID

**Analysis Performed**

1.Price Statistics

The first part of the analysis calculates basic statistics for the product prices. The SUM function is used to calculate the total price of all products.
The COUNT function was used to determine the number of products.
The AVERAGE function was used to calculate the average product price.

2.Minimum and Maximum Price

The MIN and MAX functions are used to identify the lowest and highest prices in the dataset.

3.Price Classification Using IF

An additional Price Range column was created to classify products based on their prices. The IF function was used with the formula =IF(D2>=500,"High Price","Standard Price"). Products priced at $500 or above are classified as High Price, while products below $500 are classified as Standard Price.

4.Category Analysis Using SUMIF

The SUMIF function was used to analyze the Electronics category. 

Price Analysis Using COUNTIF

The COUNTIF function was used to identify the number of products priced below $100. 

5.Product ID Text Extraction

The Product ID contains multiple pieces of information separated by hyphens. Text functions were used to extract these values into separate columns.
The LEFT function extracts the day from the beginning of the Product ID.
The RIGHT function extracts the country code from the end of the Product ID. 
The MID function extracts the month from the middle of the Product ID.

**Key Results**

The dataset contains 34 products with a total listed price of $10,100.
The average product price is approximately $297.06, with the minimum price being $30 and the maximum price being $1,000.
Products in the Electronics category have a combined price of $8050, while 11 products are priced below $100.

**Insights**

1. Wide Price Variation
   
Product prices range from $30 to $1,000, showing significant variation across the dataset. The average price of $297.06 is considerably lower than the maximum price because several products are priced below $200.

2. Electronics Have High Price Contribution
   
Electronics account for $8050 of the total listed product prices, making them the largest contributor among the categories in terms of summed product prices.

3. Affordable Products

There are 11 products priced below $100, indicating that a meaningful portion of the dataset consists of relatively low-priced products.

4. Product IDs Contain Useful Information

The Product ID is not just an identifier. It contains day, month, and country information, which can be separated using Excel text functions. This demonstrates how structured text data can be transformed into individual analytical fields.

**Conclusion**

This project demonstrates how basic Excel functions can be used to transform a raw product dataset into meaningful information. Statistical functions provided an overview of product pricing, conditional functions enabled price classification, SUMIF and COUNTIF supported category and price-based analysis, while text functions converted Product IDs into useful individual attributes.

The exercise provides a practical foundation for Excel-based data analysis, data cleaning, and business reporting.
