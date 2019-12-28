# Apriori
Mining frequent item-sets from an e-commerce transactions containing vendor names in each transaction(order)

Market Basket Analysis is one of the key techniques used by large retailers to uncover associations between items. It works by looking for combinations of items that occur together frequently in transactions. To put it another way, it allows retailers to identify relationships between the items that people buy.
Association Rules are widely used to analyze retail basket or transaction data, and are intended to identify strong rules discovered in transaction data using measures of interestingness, based on the concept of strong rules.
An example of Association Rules
Assume there are 100 customers
10 of them bought milk, 8 bought butter and 6 bought both of them.
bought milk => bought butter
support = P(Milk & Butter) = 6/100 = 0.06
confidence = support/P(Butter) = 0.06/0.08 = 0.75
lift = confidence/P(Milk) = 0.75/0.10 = 7.5

The csv file used for this analysis is a transaction export for an online retailer, I am interested in knowing vendors whose products are frequently sold together to promote for their products together through social media, promos, and bundles.

We will make use of the following python libraries
1. Pandas for data wrangling
2. mlxtend* or ML extended will be used for apriori implementation and extracting association rules.
3. The master visualizer: matplotlib

*MLextend is a library providing from A to Z data science utilities and extensions, made easy.
