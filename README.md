# CryptoClustering

This project involves clustering cryptocurrencies using K-Means algorithm on both original and Principal Component Analysis (PCA) transformed data. The goal is to compare the results and understand the impact of using fewer features for clustering.

**Standard Scaler**<br>
Using Standard Scaler, I scaled the dataframe and created the below eblow curve, determining the best K value was 4. 

<div style="text-align:center">
    <img src="https://github.com/mgtaylor119/CryptoClustering/blob/main/Images/Standard%20elbow%20curve.png?raw=true" alt="Standard Elbow">
</div>

Once an optimal K value was determined, The K-Value model was initialized, and the below cluster plot was generated

<div style="text-align:center">
    <img src="https://github.com/mgtaylor119/CryptoClustering/assets/132225207/0b993e13-609f-4ece-bce5-07ba7edcad3b" alt="Standard Cluster">
</div>

<br><br>

**Principal Component Analysis**<br>
Using the scaled data from the first part of the assignemnt, I peformed a PCA and generated a database with those results. I created another elbow curve, and deteremined the best K value was again 4. 

<div style="text-align:center">
    <img src="https://github.com/mgtaylor119/CryptoClustering/blob/main/Images/PCA%20elbow%20curve.png?raw=true" alt="PCA Elbow">
</div>

Using the K value of 4 again, I created another cluster plot for the PCA data. 

<div style="text-align:center">
    <img src="https://github.com/mgtaylor119/CryptoClustering/blob/main/Images/PCA%20Scatter.png?raw=true" alt="PCA Cluster">
</div>
