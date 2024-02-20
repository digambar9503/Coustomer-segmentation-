# behavior driven customer segmentation and k-means clustering comparison
# Introduction
RFM (Recency, Frequency, Monetary) analysis is a well-established technique designed for behaviour-driven customer segmentation. Specifically, RFM analysis evaluates customers' recency (how long ago they made a purchase), frequency (how often they make purchases), and monetary value (how much money they spend).

RFM helps divide customers into various segments to identify those more likely to respond to promotions.

We will perform RFM segmentation and compare the results with those obtained using the K-means clustering algorithm on the same data.Introduction RFM (Recency, Frequency, Monetary) analysis is a well-established technique designed for behaviour-driven customer segmentation. Specifically, RFM analysis evaluates customers' recency (how long ago they made a purchase), frequency (how often they make purchases), and monetary value (how much money they spend).

RFM helps divide customers into various segments to identify those more likely to respond to promotions.

# Objective
To perform RFM segmentation and compare the results with those obtained using the K-means clustering algorithm on the same data.

# Dataset
This dataset contains 8 variables that correspond to:

InvoiceNo : Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation. StockCode : Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product. Description : Product (item) name. Nominal. Quantity : The quantities of each product (item) per transaction. Numeric. InvoiceDate : Invoice date and time. UnitPrice : Unit price. Numeric, Product price per unit in sterling. CustomerID : Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer. Country : Country name. Nominal, the name of the country where each customer resides.

# Conclusion
RFM Segments are easy to interpret and provide recommendations for marketing strategies tailored to each customer segment. However, some segments are not as distinct as those created by K-means clustering.

K-Means clustering generates very distinct segments that may require interpretation.

Interestingly, the Champions segment almost matched in both methods
