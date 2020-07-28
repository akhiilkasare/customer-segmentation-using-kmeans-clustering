# Customer segmentation using K-means clustering

![customer segmentation](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/07/R-project-customer-segmentation.png)

#### What is customer segmentation ?

- You’ve often heard a saying that customer is the king. In today’s world customer is indeed the king  and hence its not only important to retain our loyal customers but also to win back one’s who are on the verge of churning out.

**Customer segmentation** is the one method to check who are loyal customers and who are the ones who visit the platform or our e-commerce website infrequently or the ones who just visit the website just for the sake of reediming some coupons or getting some discounts or we can also say them as the one time visitor 

In this we will see how to perform customer segmentation using machine learning

We well aslo create clusters according to the customers spending behaviour. We will also create clusters of most loyal customers and the customers who are on the verge of churning out

What is customer segmentation ?

-Its a methodology with which we can  divide our customers base into group of individuals who are similar in the terms of gender/ spending behaviour/ frequency to visit/ age or other demographics. 

- Customer segmentation allows the company to precisely target the customers who has specific needs and desires. In this way companies can targetted campaings to the right groups or audience. It may also be the case that during the creation of this groups/ clusters companies can identify new group or segments on which companies can focus more as it might be more lucrative.

- Using customer segmentation companies can identify groups that requires extreme attention such that people in that group are on the verge of churning out. There might be a group/ segment who can have highest potential or value

**To Segment Customers we need to calculate :**  

1. RFM(Recency Frequency Monetary) score of each customer.
2. Create cluster using K-means.

Now you must be wondering what are the different groups/ segments that can be created based on RFM scoring and k-mean clustering 

***For example:***

According to the business requirement a company can create 3 segments like : 

**HIGH** :  Group who buys often, spends more and visited the platform frequently.

**MEDIUM** : Group which spends less than high group and is not that much frequent to visit the 				platform.

**LOW** : Group which is on the verge of churning out.

To calculate the RFM score we will be using the Online Retail Dataset which can be downloaded from the UCI Machine Learning Repository. 

This dataset contains 541909 x 8 columns namely :
InvoiceNo
StockCode
Description 
Quantity
InvoiceDate 
UnitPrice
CustomerID
Country

## After applying the unsupervised k-means clustering algorithm
![Customer Segmentation](https://github.com/akhiilkasare/customer-segmentation-using-kmeans-clustering/blob/master/customer_segmentation_plot.png)

## Motivation
## The right approach to segmentation analysis is to segment customers into groups based on predictions regarding their total future value to the company, with the goal of addressing each group (or individual) in the way most likely to maximize that future, or lifetime, value.
