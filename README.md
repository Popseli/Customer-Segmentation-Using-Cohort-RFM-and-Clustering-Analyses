## Project Overview
Customer segmentation is the practice of grouping customers based on common characteristics. These customer segments are beneficial in marketing campaigns, in identifying potentially profitable customers, and in developing customer loyalty. A business might segment customers according to a wide range of factors including demographics (e.g age, gender, location), behaviour (e.g previous orders, responses to messaging), psychographics (e.g values, interests, lifestyles) etc. In this project, we perform customer segmentation of a retail business, based on their purchasing behaviours, to guide the business in developing targeted marketing strategies. Three segmentation analyses are applied: cohort retention rate, RFM and clustering analyses 
#### Cohort Retention Rate Analysis
Cohort analysis answers a business question about how a specific group or segment of users has interacted with a product, or is expected to interact with a product, based on their prior behaviors. Cohorts are groups of users that share specific characteristics and usage patterns over a period of time. Cohorts are useful because they help you segment your user base and collect data about the way they interact with your product throughout their lifecycle. By analyzing different cohorts of users, businesses can track lifetime value, measure long-term engagement, and identify patterns that might help in tailoring personalized marketing campaigns and product improvements. In this project, we perform cohort retention rate analysis. While acquiring new customers is crucial, it’s important not to neglect the ones you already have. Considering that retaining existing customers (and reducing churn) costs a fraction of customer acquisition cost, analyzing customer retention is important for any business. By analyzing customer retention patterns for different user segments, cohort tools reveal patterns in drop-offs. With this insight, strategies can be molded to prevent churn.
#### RFM Analysis
RFM stands for recency, frequency, and monetary. This analysis methodology involves evaluating customer behavior based on their transaction recency, frequency, and monetary value. The primary aim is to understand and categorize customers based on their recent purchases, transaction frequency, and overall spending, allowing businesses to implement effective marketing strategies. RFM analysis allows marketers to target specific clusters of customers with communications that are much more relevant for their particular behavior and thus generate much higher rates of response in addition to increased loyalty and customer lifetime value.
#### Clustering Analysis
Cluster analysis is a type of unsupervised learning, which means that it does not require predefined labels or categories for the data. Instead, it uses mathematical algorithms to find natural clusters or groups of data points that are similar to each other and different from other groups. The output of cluster analysis is a set of clusters, each with a centroid (the average or representative point of the cluster) and a boundary (the range or distance that defines the cluster). Cluster analysis can help you segment your customers based on their characteristics, preferences, behaviors, or needs; thus, allowing you to better understand your customer base and tailor your marketing efforts accordingly. For example, you can use cluster analysis to identify your most valuable customers and target them with personalized offers or rewards. Additionally, it can help you discover new or niche segments that have unmet needs or untapped potential so that you can create new products, services, or campaigns to satisfy them. Furthermore, it can be used to test different marketing strategies or messages for different segments and measure their effectiveness and response.
## Data
This project uses an e-commerce sales data of a particular online retail store selling items to customers in various countries. 541,909 transactions recorded in this dataset are those made between 1 December 2010 and 9 December 2011. The data has the following attributes:
* InvoiceNo: Invoice number. Nominal. A 6-digit integral number uniquely assigned to each transaction. If this code starts with the letter 'c', it indicates a cancellation.
* StockCode: Product (item) code. Nominal. A 5-digit integral number uniquely assigned to each distinct product.
* Description: Product (item) name. Nominal
* Quantity: The quantities of each product (item) per transaction. Numeric.
* InvoiceDate: Invice date and time. Numeric. The day and time when a transaction was generated.
* UnitPrice: Unit price. Numeric. Product price per unit.Numeric.
* CustomerID: Customer number. Nominal. A 5-digit integral number uniquely assigned to each customer.
* Country: Country name. Nominal. The name of the country where a customer resides.
## Methodology





