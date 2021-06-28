#Problem Description

In this project, our task is to identify major customer segments on a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

Data Description: 


Attribute Information:


•	InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.

•	StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.

•	Description: Product (item) name. Nominal.

•	Quantity: The quantities of each product (item) per transaction. Numeric.

•	InvoiceDate: Invoice Date and time. Numeric, the day and time when each transaction was generated.

•	UnitPrice: Unit price. Numeric, Product price per unit in sterling.

•	CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.

•	Country: Country name. Nominal, the name of the country where each customer resides.

Conclusion:
That's it! We reached the end of our exercise.
Starting with loading the data so far we have done EDA , null values treatment, feature selection and then model building.
In our model our optimum value of k was 4 because at 4 we saw the error is decreasing as K increases. For values of k at 4 or 5 slope of the curve is decreasing very fast this means errors do not decrease much faster as the increase in number of clusters.


for Cluster  =0:-
we observe the RFM Interpretation as Least purchase long ago, Least Monetary Spending, Least no of transaction and hence the Type of Customer is Churned

for Cluster  =1:-
we observe the RFM Interpretation as Recent Transaction, Most Frequent Transaction, Highest Monetary Spending and hence the Type of Customer is Targeted Customer

for Cluster  =2:-
we observe the RFM Interpretation as Recent Transaction, Low Frequent Transaction, Low Monetary Spending and hence the Type of Customer is New

for Cluster  =3:-
we observe the RFM Interpretation as Last Purchase While ago, Low Frequent Transaction,Low Monetary Spending and hence the Type of Customer is At Risk
