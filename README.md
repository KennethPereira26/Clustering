# Clustering
Implementation of K-Means Clustering 
I have implemented K-means clustering on the "Mall_Customers.csv" dataset. 

The csv file contains basic data about  customers such as Customer ID, age, gender, annual income and spending score.
Spending Score is something you assign to the customer based on your defined parameters like customer behavior and purchasing data.

K-Means clustering is used to easily determine target customers. Customers are grouped together based on their spending score and their Annual income. This can be useful in devising a good marketing strategy. 

I followed the following approach in my python code:

Step 1:
Identify the number of clusters one would require for a data Assuming number of clusters (k)

Step 2:
Randomly select k points. (assuming they belong to three differet clusters)

Step 3:
With respect to these 3 points, we calculate distance between individual points and these Cluster Centroids
