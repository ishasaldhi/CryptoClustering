# CryptoClustering

## Background
In this project, I used Cryptocurrency data. After normalizing the data, I found the optimal k value by plotting them against inertia values in an elbow plot. I used the optimal k value to make a K-means model and predict clusters to group the Cryptocurrencies. Then I performed a Principal Component Analysis on the original data, and I found the optimal k value for the PCA data. With the PCA data's k value, I created another K-Means model. After comparing the results of each method, I concluded that having less features resulted in a clearer prediction. 

## Features 
* Using sklearn with KMeans and PCA to cluster Cryptocurrencies
* Creating a Pandas DataFrame in Jupyter Notebook to represent demonstrate the predictions
* Analyze DataFrame to make charts for Elbow curve and Scatter plots for prediction clusters
* Compare visualizations to determine the impact of using fewer features

## Installation
1. Clone repository
2. Install sklearn
3. Install hvplot
4. Analyze and visualize data in Jupyter Notebook

## Built with
* Python
* Hvplot
* JupyterNotebook
* Sklearn
