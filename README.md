# cryptocurrencies

## Analysis Overview
The purpose of this project is to use unsupervised machine learning to analyze a database of cryptocurrencies and create a report including the traded cryptocurrencies classified by group according to their features.
This classification report could be used by an investment bank to propose a new cryptocurrency investment portfolio to its clients.
We use the following methods for the analysis:

preprocessing the database,
reducing the data dimension using Principal Component Analysis,
clustering cryptocurrencies using K-Means,
visualizing classification results with 2D and 3D scatter plots.


## Results

Following the preprocessing and cleaning phase we have a total of 532 tradable cryptocurrencies.


Clustering Cryptocurrencies using K-Means - Elbow Curve
We don't know what would be the output of the analysis so we are using unsupervised machine learning to identify clusters of the cryptocurrencies.
We produced the elbow curve below using the K-Means method iterating on k values from 1 to 10.

<img width="1221" alt="Screen Shot 2022-07-18 at 9 26 17 PM" src="https://user-images.githubusercontent.com/100106554/179646285-f066b971-996a-4a3e-9cce-f44eba64f51c.png">
The best k value appears to be 4 so we would conclude on an output of 4 clusters to categorize the crytocurrencies.




## Visualizing Cryptocurrencies Results
# 3D-Scatter plot with clusters

<img width="1145" alt="Screen Shot 2022-07-18 at 9 26 40 PM" src="https://user-images.githubusercontent.com/100106554/179646313-e26f8646-6e45-44d2-90e2-a9f9683f2dad.png">

This 3-D scatter plot was obtained using the PCA algorithm to reduce the crytocurrencies dimensions to three principal components.

## 2D-Scatter plot with TotalCoinMined vs TotalCoinSupply


<img width="1262" alt="Screen Shot 2022-07-18 at 9 26 59 PM" src="https://user-images.githubusercontent.com/100106554/179646321-792ecbc0-6239-4309-863e-e270da160da4.png">



## Summary

We have identified the classification of 532 cryptocurrencies based on similarities of their features.
Particularities of each group need to be analyzed to determined their performance and potential interest for the investment bank's clients.
