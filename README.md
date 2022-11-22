# ONLINE-RETAIL-RFM
Here i do Unsupervised Learning, RFM Model Building, Clustering, EDA, and Predictive Model Building Using Machine Learning.

## CONTEXT
E-commerce has become a new channel to support businesses development. Through e-commerce, businesses can get access and establish a wider market presence by providing cheaper and more efficient distribution channels for their products or services. E-commerce has also changed the way people shop and consume products and services. Many people are turning to their computers or smart devices to order goods, which can easily be delivered to their homes.

## CONTENT
This is a sales transaction data set of UK-based e-commerce (online retail) for one year. This London-based shop has been selling gifts and homewares for adults and children through the website since 2007. Their customers come from all over the world and usually make direct purchases for themselves. There are also small businesses that buy in bulk and sell to other customers through retail outlet channels.

The data set contains 500K rows and 8 columns. The following is the description of each column.

TransactionNo (categorical): a six-digit unique number that defines each transaction. The letter “C” in the code indicates a cancellation.<br>
Date (numeric): the date when each transaction was generated.<br>
ProductNo (categorical): a five or six-digit unique character used to identify a specific product.<br>
Product (categorical): product/item name.<br>
Price (numeric): the price of each product per unit in pound sterling (£).<br>
Quantity (numeric): the quantity of each product per transaction. Negative values related to cancelled transactions.<br>
CustomerNo (categorical): a five-digit unique number that defines each customer.<br>
Country (categorical): name of the country where the customer resides.<br>

## GOAL
Gather useful intrinsic information by combining RFM model and some unsupervised learning model

For each segments, analyze the data, and try to answer the following questions:

What is the percentage of cancellations?<br>
How was the sales trend over the months?<br>
What are the most frequent purchased products?<br>
How many products does the customer purchase in each transaction?<br>
How does each cluster/group contribute to the company's revenue?<br>
What are the interval date between transactions?<br>
Based on your findings, what strategy could you recommend to the business to gain more profit?<br>

Also, there is a small percentage of order cancellation in the data set. Most of these cancellations were due to out-of-stock conditions on some products. Under this situation, customers tend to cancel an order as they want all products delivered all at once.

Therefore, try to build a supervised learning model to solve this problem.

Source from UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/online+retail
