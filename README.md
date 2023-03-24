# MAVEN MARKETING CAMPAIGN RESULTS 
![](https://github.com/OlasanmiEmiola/maven_marketing_campaign/blob/main/marketing-campaign.jpg)
##  INTRODUCTION
This is marketing campaign data of 2,240 customers of Maven Marketing, including customer profiles, product preferences, campaign successes/failures, and channel performance. The dataset was downaloaded from [Maven Analytics website ](https://www.mavenanalytics.io/data-playground?page=4&pageSize=5). It is a CSV file containing a single table with 2,240 rows and 28 Columns. [Click here to view the raw files](https://github.com/OlasanmiEmiola/maven_marketing_campaign/blob/main/marketing_data.csv) and [Dataset Dictionary](https://github.com/OlasanmiEmiola/maven_marketing_campaign/blob/main/marketing_data_dictionary.csv)

## AIM OF THE PROJECT
The aim of this analysis is to fully answer the business questions as regard to the data

##  OBJECTIVES OF THE PROJECT
1.  Import data to  Miscrosoft SQL studio 
2.  Clean the data in Microsoft SQL studio  
    * Check for duplicates 
    * Standardize the data format 
    * Check for Null or Mising Values     
3.  Import the clean data set into PowerBi 
4.  Visulaize the data 
5.  Make the necessary inferences from the visualizations 

## THE BUSINESS QUESTION 
1.  Are there any null values or outliers? How will you handle them?
2.  What factors are significantly related to the number of web purchases?
3.  Which marketing campaign was the most successful?
4.  What does the average customer look like?
5.  Which products are performing best?
6.  Which channels are underperforming?

##  PROJECT 
### Data Cleaning
The data was imported to the Microsoft SQL server. This is a ![Text File](https://github.com/OlasanmiEmiola/maven_marketing_campaign/blob/main/Marketing_Campaign_SQL.txt) containing the queries used to standardize the data set. The table contained no duplicates but was altered for standardization. Note, the data (income column) has 24 rows that are null values, it was not removed because the rows has contained other information that are vitals for the analysis. [View the Cleaned data](https://github.com/OlasanmiEmiola/maven_marketing_campaign/blob/main/MarketDataCleaned.csv)
### Data Visulaization 
PowerBi is the tool used to visualize the data
  From the visulaization, five campaigns has been conducted 
![The five Campaigns](https://github.com/OlasanmiEmiola/maven_marketing_campaign/blob/main/Campaign%20Results.png)

  The different product Catergories
***
![](https://github.com/OlasanmiEmiola/maven_marketing_campaign/blob/main/Product_Category.png) 

  The Channels of purchase
***
![](https://github.com/OlasanmiEmiola/maven_marketing_campaign/blob/main/Channel_of_Purchase.png)

  The WebVisits/Purchase
***
![](https://github.com/OlasanmiEmiola/maven_marketing_campaign/blob/main/WebVisit_purchase.png)

  The Customers Overview 
***
![](https://github.com/OlasanmiEmiola/maven_marketing_campaign/blob/main/Overview_customers.png)
![](https://github.com/OlasanmiEmiola/maven_marketing_campaign/blob/main/Over_of_customers2.png)

  The Number of Customers over the years 
  ![](https://github.com/OlasanmiEmiola/maven_marketing_campaign/blob/main/CustomePerYear.png) 

##  INSIGHTS
  * Five campaigns were conducted; none have been successful because more people have rejected than accepted each campaign. 
  * Six product categories (i.e. Wines, Gold products, Fish products, Fruits, Sweet products, and Meat products) were sold. Wines did well with 50% sales, followed   by meat products with sales of 28%. 
  * The Catalog, Web, Store, and Deals purchases were the different channels of purchase. The store purchase did well more than other channels, followed by web purchases.The deals and the catalogue purchases are underperforming.   
  * There was no significant changes in the number of customers over the period of years this data was collected. The  highest number customers recorded is 117 and 78 is the lowest.  
  * Web purchases are closely related to the number of web visits. The web visits/purchases show that not all web visits turned to a purchase. 
  * The average customer is Married, has no children(Kids and Teenagers), lives in Spain, is a first-degree holder, and is a Low middle-income ($34000-$170000)earner. 
         ***Note***, Income cannot be used as a  suitable variable factors because it has some Null values 
         
##  RECOMMENDATIONS
    No recomemndations can be made because of the limitation of information regarding the different campaigns done, how it done and when it is done. 




