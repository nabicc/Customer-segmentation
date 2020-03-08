# E-commerce customers’ segmentation: Who are the golden clients? 
## Goal
The popularity of e-commerce has risen in recent years as demonstrated by its increased share of the total global retail sales from 7.4% in 2015 to 14.1% in 2019. For e-commerce businesses, this growing trend is accompanied by more competition. One strategy to remain in the marketplace for a retail store is understanding its current customers and trying to retain them by targeting them with special offers.  According to a study made by Bain & Company, increasing the customer retention by 5% can lead to an increase in profits of 25% – 95%.

In this project, I will use the "Online Retail Database" that contains customers’ transactions between 2010 and 2011 from an exclusively online retail based and registered in United Kingdom (UK). The main goal is to provide a market segmentation of the clients, and provide valuable insights of their profile that can be used by the marketing department in order to better target its clients.
During this project, I will describe the data cleansing, explore the dataset and develop a cohort analysis and recency frequency model (RFM) model. 

## Dataset Information
The data provided by the UCLI ML repo contains 541,909 rows and eight variables, described as follows:  
“- InvoiceNo: Invoice number. Nominal. A 6-digit integral number uniquely assigned to each transaction. If this code starts with the letter 'c', it indicates a cancellation.
- StockCode: Product (item) code. Nominal. A 5-digit integral number uniquely assigned to each distinct product.
- Description: Product (item) name. Nominal.
- Quantity: The quantities of each product (item) per transaction. Numeric.
- InvoiceDate: Invoice date and time. Numeric. The day and time when a transaction was generated.
- UnitPrice: Unit price. Numeric. Product price per unit in pounds sterling (£).
- CustomerID: Customer number. Nominal. A 5-digit integral number uniquely assigned to each customer.
- Country: Country name. Nominal. The name of the country where a customer resides.”

## Libraries used
•	Python 3
•	Pandas
•	Numpy
•	Seaborn
•	Matplotlib
•	Geopandas

## Methodology
1) Data Preparation – Involves dropping missing and duplicate values. Identification of outliers, and construction of variables for the analysis such as monetary value and the distance of each country to the UK in kilometres. 
2) Exploratory Data Analysis – Manipulation of data to calculate and visualize business (i.e. e-commerce sales and growth rates, trends in the number of transactions and customers over time) and customers’ insights (i.e. demographics and days when they are more likely to purchase). 
3) Market segmentation-  A monthly cohort analysis has been built in order to calculate and visualize the following metrics: retention rates, average quantities purchased and monetary value per customer.  An RFM model has been conducted to classify customers as golden, silver or bronze. For each category, I provided summary statistics related to the number of purchases, days since the last transaction, monetary value, country of residence and monthly cohort.  

## Summary of results
The market segmentation reveals that 43% of the customers belong to the category "silver" and they represent only 15% of the total of purchases made during 2011. 38% of the clients are considered “golden” and they represent 83% of the sales made in 2011. Among them, 88% live in United Kingdom and 12% did the first transaction in December 2010. 

[Follow this Link for codes to show](https://github.com/nabicc/Customer-segmentation/blob/master/Project_customer%20segmentation%20via%20cohort%20analysis%20and%20RFM%20model.ipynb)

