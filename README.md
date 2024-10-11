# THEORY:

## 1. What is Apriori Algorithm?
Apriori Algorithm is a Machine Learning algorithm which is used to gain insight into the structured relationships between different items involved. The most prominent practical application of the algorithm is to recommend products based on the products already present in the user’s cart. Walmart especially has made great use of the algorithm in suggesting products to it’s users.. 
For example, the items customers but at a Big Bazar.
Apriori algorithm helps the customers to buy their products with ease and increases the sales performance of the particular store.

## 2. Components of Apriori algorithm
The given three components comprise the apriori algorithm.
1.	Support
2.	Confidence
3.	Lift

Let's take an example to understand this concept.
We have already discussed above; you need a huge database containing a large no of transactions. Suppose you have 4000 customers transactions in a Big Bazar. You have to calculate the Support, Confidence, and Lift for two products, and you may say Biscuits and Chocolate. This is because customers frequently buy these two items together.
Out of 4000 transactions, 400 contain Biscuits, whereas 600 contain Chocolate, and these 600 transactions include a 200 that includes Biscuits and chocolates. Using this data, we will find out the support, confidence, and lift.


## Support
Support refers to the default popularity of any product. You find the support as a quotient of the division of the number of transactions comprising that product by the total number of transactions. Hence, we get
Support (Biscuits) = (Transactions relating biscuits) / (Total transactions)
= 400/4000 = 10 percent.

## Confidence
Confidence refers to the possibility that the customers bought both biscuits and chocolates together. So, you need to divide the number of transactions that comprise both biscuits and chocolates by the total number of transactions to get the confidence.
Hence,
Confidence = (Transactions relating both biscuits and Chocolate) / (Total transactions involving Biscuits)
= 200/400
= 50 percent.
It means that 50 percent of customers who bought biscuits bought chocolates also.

## Lift
Consider the above example; lift refers to the increase in the ratio of the sale of chocolates when you sell biscuits. The mathematical equations of lift are given below.
Lift = (Confidence (Biscuits - chocolates)/ (Support (Biscuits)
= 50/10 = 5
It means that the probability of people buying both biscuits and chocolates together is five times more than that of purchasing the biscuits alone. If the lift value is below one, it requires that the people are unlikely to buy both the items together. Larger the value, the better is the combination
