# Amazon_Vine_Analysis

## Overview: 
Analyzed Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. In Google Colaboratory, PySpark was used to perform the ETL process of extracting, transforming and loading the dataset from the Amazon Vine program. The analyzed dataset in Google Colaboratory was then connected  to an AWS RDS instance and the data was loaded into pgAdmin.

## Results:

**Vine Reviews:** 7

![ScreenShot](https://github.com/dmyrick/Amazon_Vine_Analysis/blob/main/Images/Paid.png)


**Non-Vine Reviews:** 105,979

![ScreenShot](https://github.com/dmyrick/Amazon_Vine_Analysis/blob/main/Images/Unpaid.png)


**5-star Vine Reviews:** 0
**Percentage of 5-star Vine Reviews:** 0.00%

![ScreenShot](https://github.com/dmyrick/Amazon_Vine_Analysis/blob/main/Images/5-star-paid.png)


**5-star non-Vine Reviews:** 67,580
**Percentage of 5-star non-Vine Reviews:** 63.77%

![ScreenShot](https://github.com/dmyrick/Amazon_Vine_Analysis/blob/main/Images/5-star-unpaid.png)


## Summary: 
The star-rating mean of the paid Vine program customers was 3.57 and 4.20 for the non-Vine customers. Also, the non-Vine customers had a percentage rating of approximately 64%. In contrast, the paid Vine program customers did not have one 5-star rating. The dataset suggests positivity bias towards non-Vine customers providing a substantial number of 5-star ratings for the purchased music products.
An additional analysis of the dataset that could be performed is to determine which product the non-Vine customers reviewed the most with a 5-star rating.



