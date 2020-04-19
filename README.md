CREDIT CARD CUSTOMER SEGMENTATION BY DATA MINING ALGORITHMS

1.Importance, Purpose And Scope Of The Subject

In banking sector Customer Relationship Management (CRM) customers and the acquisition of the data for different contact points with customers in line with these data, identification of customers, customer classification (according to the type of purchase or demographics) and what is their target market and customer group for each section, which is a determination that will serve profitability analysis, customer priorities, and identify those priorities to the customers and accordingly design the appropriate marketing mix management. Thus, banks provide better service to customers by estimating which product or service the existing customers choose, with a personalized marketing approach.  
In this thesis, a customer segmentation will be developed to define marketing strategy. The dataset to be used in the study outlines the use behavior of approximately 9000 active credit card holders over the past 6 months. The dataset contains 18 behavior variables. Credit card transactions will be examined, from which to create a profile for each customer targeted. Thus, it is aimed that banks develop marketing strategies appropriate to each profile and increase customer satisfaction. Due to the scarcity of research on this subject, he will contribute to the literature.

2. General Information of the Data

CUST_ID : Identification of Credit Card holder (Categorical)

BALANCE : Balance amount left in their account to make purchases (

BALANCE_FREQUENCY : How frequently the Balance is updated, score between 0 and 1 (1 = frequently updated, 0 = not frequently updated)

PURCHASES : Amount of purchases made from account

ONEOFF_PURCHASES : Maximum purchase amount done in one-go

INSTALLMENTS_PURCHASES : Amount of purchase done in installment

CASH_ADVANCE : Cash in advance given by the user

PURCHASES_FREQUENCY : How frequently the Purchases are being made, score between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased)

ONEOFFPURCHASESFREQUENCY : How frequently Purchases are happening in one-go (1 = frequently purchased, 0 = not frequently purchased)

PURCHASESINSTALLMENTSFREQUENCY : How frequently purchases in installments are being done (1 = frequently done, 0 = not frequently done)

CASHADVANCEFREQUENCY : How frequently the cash in advance being paid

CASHADVANCETRX : Number of Transactions made with "Cash in Advanced"

PURCHASES_TRX : Numbe of purchase transactions made

CREDIT_LIMIT : Limit of Credit Card for user

PAYMENTS : Amount of Payment done by user

MINIMUM_PAYMENTS : Minimum amount of payments made by user

PRCFULLPAYMENT : Percent of full payment paid by user

TENURE : Tenure of credit card service for user

3.Applied Methods

K-means, DBSCAN and Hierarchical clustering methods have been applied for customer segmentation. The most suitable of these methods was chosen as K-means. With K-means, 4, 6 and 8 clusters were examined. As a result, customers are segmented into 8 clusters.
