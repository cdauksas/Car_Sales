# Car_Sales
## Exploratory Data Analysis of Car Sales data set
## Utilzed the RFM technique (Recency, Frequency, Monetary) marketing technique used to quantitatively rank and group customers based on the recency, frequency and monetary total of their recent transactions to identify the best customers and perform targeted marketing campaigns.
### Answered the following Questions
 - What products are frequently sold together?
 - Who is the best customer using RFM technique?
 - Total revenue by Product Line, Month, Country?
 
 ### I began by inspecting the data. Here is an overview of the data. It contains 2,823 rows of sales data consiting of order numbers, quantities, dates, sales, and products.
 
 ![](https://github.com/cdauksas/PortfolioProjects/blob/main/images/Overview.png)
 
 ### I then pulled the distinct values to inspect the data
 
  ![](https://github.com/cdauksas/PortfolioProjects/blob/main/images/InspectDistincts.png)
  
 ### Let’s look at the total sales by product line

 ![](https://github.com/cdauksas/PortfolioProjects/blob/main/images/SalesProductLine.png)

### Let’s look at the total sales by year

 ![](https://github.com/cdauksas/PortfolioProjects/blob/main/images/SalesYear.png)
 
- 2005 seems to be small. Lets look at the total months that was included in 2005

![](https://github.com/cdauksas/PortfolioProjects/blob/main/images/Sales2005.png)

- Only the first 5 months of are captured in year 2005, this can explain why total sales is lower compared to other years.

### Next we will look at at total sales by Deal Size

![](https://github.com/cdauksas/PortfolioProjects/blob/main/images/SalesDealSize.png)


### What was the best month for sales in a specific year? How much was earned that month?

![](https://github.com/cdauksas/PortfolioProjects/blob/main/images/SalesMonth.png)

- Month 11 (November) has the highest revenue for years 2003 and 2004. I wonder if this is related to the holiday season with folks shopping at that time?

### Let’s further inspect the month of November for each year and look at the total revenue by product line and the count of orders

![](https://github.com/cdauksas/PortfolioProjects/blob/main/images/Sales11.png)


### Now we want to use the RFM technique to look at who is the best customer.

### RM is Recency-Frequency-Monetary. It is an indexing technique that uses past purchase behavior to segment its customers. An RM report is a way of segmenting customers using 3 key metrics:
 - Recency (how long ago was their last purchase)
 - Frequency (how often they purchase)
 - Monetary Value (how much they spent)

![](https://github.com/cdauksas/PortfolioProjects/blob/main/images/RFM1.png)

![](https://github.com/cdauksas/PortfolioProjects/blob/main/images/RFM2.png)

![](https://github.com/cdauksas/PortfolioProjects/blob/main/images/rfm3.png)


### What products are most often sold together?

![](https://github.com/cdauksas/PortfolioProjects/blob/main/images/ProductsSoldTogether.png)











 
 
 
