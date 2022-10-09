# Cryptocurrencies
I am using Principal Component Analysis to consolidate data and K-Means Clustering to segment Crypto currencies

## Purpose
The purpose is to practice using unsupervised Machine Learning to segment and predict bitcoins that will be profitable.

## Methods

### Process
First I processed the data by:

•	getting rid of null values

•	removing variables, I cannot use to predict

•	selecting crypto that is still operating

•	selecting crypto that produces coin

•	 and scaling the cleaned data


### Deciding the Number of Clusters (k)
Before clustering, I condensed the remaining features into (3) principal component's. Once I had the new variables, I created an Elbow curve to help me decide how many clusters to use. The elbow curve showed a kink at 4 clusters.
(PCA)
![Alt text](https://github.com/thegreatkeej/Cryptocurrencies/blob/main/images/Picture1.png)
(Elbow Curve)
![Alt text](https://github.com/thegreatkeej/Cryptocurrencies/blob/main/images/Picture2.png)

### K-Means
I created a model, fit the model, transformed the fitted model and made predictions.
(K-Means model)
![Alt text](https://github.com/thegreatkeej/Cryptocurrencies/blob/main/images/Picture3.png)

## Results
After which, I used 3-D and scatter plot to visualize the results. The outliers are easy to spot. In the scatter plot, note the class 3 and class 2 bitcoins in the upper right and left corners.
(3-D of PCA)
![Alt text](https://github.com/thegreatkeej/Cryptocurrencies/blob/main/images/Picture4.png)
(Scatter plot of coins mined and coin supply by class)
![Alt text](https://github.com/thegreatkeej/Cryptocurrencies/blob/main/images/Picture5.png)
