# Credit-Card-Marketing-Segmentation-Using-K-Means-Clustering-and-
This project leverages K-means clustering and Principal Component Analysis algorithms to group credit card customers for the purpose of marketing segmentation. Please navigate to the Jupyter notebook to view the entire project.

## Acknowledgements
Special thanks to Arjun Bhasin for providing the dataset. The dataset was accessed in November 2020, and it can be downloaded here: https://www.kaggle.com/arjunbhasin2013/ccdata

## Dependencies and Libraries
Python 3, Pandas, NumPy, Seaborn, Matplotlib, and Scikit-learn.

## Business Case
A bank wants to organize their credit card customers into several groups of customers with shared features to assist them in developing targeted marketing advertisement campaigns. The bank wants to sort customers by specific behaviors and dispositions like spending, repaying balances, making cash advance transactions, and tenure (i.e., the amount of time a customer has had an active credit card with the bank). The groups that are of primary interest are the following:

1. A lucrative group composed of customers who make numerous cash advance transactions and who have large balances (these customers pay a lot of interest and bring in more revenue).
2. A conservative group composed of customers with low balances and who make a small number of cash advance transactions.
3. A top-tier group composed of customers who have the biggest lines of credit and who also frequently pay off their balances.
4. A developing group composed of new members or customers who have a low tenure.

## The Main Problem
We need to gather, clean, and process data containing information about the bank's credit card customers to leverage machine learning algorithms that will assist us in the development of marketing segmentation. We need to group the customers into several clusters and identify those clusters composed of (1) lucrative customers, (2) conservative customers, (3) top-tier customers, and (4) developing customers.

## The Strategy
I will employ an unsupervised machine learning algorithm called "K-Means clustering" to segment the credit card customers into distinct groups with shared features. From those groups, I will attempt to identify the 4 customer groups of primary interest: the lucrative group, the conservative group, the top-tier group, and the developing group.

## The Methodology
1. Import librariers and data.
2. Perform initial exploratory data analysis and visualizations.
3. Clean and process the data for further analysis and the application of the K-means clustering algorithm.
4. Determine the optimal number of clusters using the elbow method.
5. Train and implement the K-means clustering algorithm.
6. Locate and identify the clusters that contain the groups of primary interest.
7. Use the machine learning algorithm referred to as "Principal Component Analysis" to perform dimensionality reduction.
8. Visualize the clusters.
9. Summarize the project and the results.
