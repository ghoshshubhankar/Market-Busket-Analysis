# Market-Busket-Analysis

Market Basket Analysis using Apriori Algorithm:
Market Basket Analysis is a data-driven technique used to uncover patterns and relationships within large transactional datasets, particularly in retail and e-commerce. It helps businesses understand which products or items are often purchased together, providing insights for optimizing product placement, marketing strategies, and promotions.

Data In Hand:

The dataset used in this project contains over 38K observations (rows) and 3 features (columns).

•	Member Number : Member no for each transaction

•	Date :             Date of the transaction

•	Item Description : what item is sold in each transaction

Analysis:

We began our analysis by exploring the dataset , how many observations are there, whether there are any missing values or not and what are the feature variables among which , which are the numerical and which are the character and we have seen Date and Item Descriptions are character and we sorted the data w.r.t. Member_no and then we Grouped all the items that were bought together by the same customer(same member_no) on the same date.

Then we removed member number and date column from the data and coverted the current data into basket format (which shows distribution of transactions with total no of duplicates).

Then we used Apriori algorithm, this algorithm generates the most relevant set of 
rules from a given transaction data. It also shows the support, confidence and lift 
of those rules. These three measure can be used to decide the relative strength of 
the rules.

Then providing different values of the parameter like support and confidence we 
generated different set of rules (more than 450 rules are made) and made some       plots like scatter plot, graph plot, parallel coordinate plot, bar plot on that and made
some conclusion on which are the most frequent products, which products sales are           related to each other.


Conclusion:

In conclusion, the Market Basket Analysis project has provided valuable insights into customer purchasing behaviour, enabling businesses to understand which products are frequently purchased together. By uncovering these associations, companies     can optimize their marketing strategies, enhance product placement, and 
personalize recommendations, ultimately leading to improved customer satisfaction,
increased sales and empowering businesses to make data-driven decisions and stay competitive in today's dynamic marketplace.

