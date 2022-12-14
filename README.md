
# Cryptocurrencies

# Overview of Project

The purpose of this project is to use unsupervised machine learning to analyze a database of cryptocurrencies and create a report including the traded cryptocurrencies classified by group according to their features.

This classification report could be used by an investment bank to propose a new cryptocurrency investment portfolio to its clients.
We use the following methods for the analysis:

- preprocessing the database,
- reducing the data dimension using Principal Component Analysis,
- clustering cryptocurrencies using K-Means,
- visualizing classification results with 2D and 3D scatter plots.

# Resources

- Data Source: crypto_data.csv

- Software: Python 3.7.7, Jupyter Notebook 6.0.3

# Results

### Clustering Cryptocurrencies using K-Means - Elbow Curve

We don't know what would be the output of the analysis so we are using unsupervised machine learning to identify clusters of the cryptocurrencies.

We produced the elbow curve below using the K-Means method iterating on k values from 1 to 10.

![Elbow_curve](https://user-images.githubusercontent.com/96400887/184929157-8d2b3d54-5f2e-4a22-813f-5e0ce7c06f71.png)

The best k value appears to be 4 so we would conclude on an output of 4 clusters to categorize the crytocurrencies.

### Visualizing Cryptocurrencies Results

3D-Scatter plot with clusters

![D4_3DPLOT](https://user-images.githubusercontent.com/96400887/184929428-36656df1-65cf-4bbf-9f35-b3490d5199d4.png)

This 3-D scatter plot was obtained using the PCA algorithm to reduce the crytocurrencies dimensions to three principal components.

2D-Scatter plot with clusters

![D4_HVPLOT](https://user-images.githubusercontent.com/96400887/184929545-bae6e35e-89a3-499e-97df-f0382ada7d48.png)

This 2-D scatter plot was obtained using the PCA algorithm to reduce the crytocurrencies dimensions to two principal components.

Both these scatter plots show the distribution and the four clusters of cryptocurrencies.
We can identify the outliers like the unique cryptocurrency in the class #2.

### Tradable Cryptocurrencies Table

![D4_TABLE](https://user-images.githubusercontent.com/96400887/184929982-71481d42-9c21-4be9-bca0-178137a397e8.png)


# Summary

We have identified the classification of 532 cryptocurrencies based on similarities of their features.

Particularities of each group need to be analyzed to determined their performance and potential interest for the investment bank's clients.































