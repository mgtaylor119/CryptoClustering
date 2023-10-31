# CryptoClustering

This project involves clustering cryptocurrencies using K-Means algorithm on both original and Principal Component Analysis (PCA) transformed data. The goal is to compare the results and understand the impact of using fewer features for clustering.

**Standard Scaler**<br>
Using Standard Scaler, I scaled the dataframe and created the below eblow curve, determining the best K value was 4. 

<center>![Standard Elbow Curve] </center>

Once an optimal K value was determined, The K-Value model was initialized, and the below cluster plot was generated

<center>![Standard Scatter](https://github.com/mgtaylor119/CryptoClustering/blob/main/Images/1st%20scatter.png?raw=true)</center>

**Principal Component Analysis**<br>
Using the scaled data from the first part of the assignemnt, I peformed a PCA and generated a database with those results. I created another elbow curve, and deteremined the best K value was again 4. 

<center>![PCA Elbow Curve] </center>

Using the K value of 4 again, I created another cluster plot for the PCA data. 

<center>![PCA Elbow Curve] </center>
