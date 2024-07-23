# CryptoClustering
 Module 19: Unsupervised Learning

 **Overview:**

 The code in _Crypto_Clustering.ipynb_ utilizes the Cryptocurrency price change data from _crypto_market_data.csv_.  The original data is plotted on the graph below.

 
![Screenshot 2024-07-22 232524](https://github.com/user-attachments/assets/6bbb7fcd-0a78-4741-b636-b06de94b616f)


Please note the two Cryptocurrencies that are outliers (Ethlend & Celsius-Degree-Token).  The original data was scaled and the Elbow Method was used with the original scaled data and the scaled data using the Principal Component Analysis.


**Results:**

Both Elbow Methods produced the best number of clusters to be 4.  Please see the graphs below.

![Screenshot 2024-07-22 233855](https://github.com/user-attachments/assets/ad7e8fd9-8a9d-4216-851b-d0496c405d72)

As illustrated from the scatter plots below, the optimized clusters using the Principal Component Analysis (PCA) gives the better cluster set.  Please note that the red cluser (1) is Ethlend and the yellow cluster (2) is Celsius-Degree-Token.  These are the oputliers in the original dataset.  If there where less clusters, the data would have been over-simplified.

![Screenshot 2024-07-22 234127](https://github.com/user-attachments/assets/47701d40-f743-4e25-a69c-fc5acb09d6d9)


