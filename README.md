Module 10 Challenge

In this program I used unsupervised machine learning to find clusters in market data of different crypto currencies by running the KMeans algorithm. I also used Principal Component Data to optimize the data and find clusters using the PCA data.

Details:

First the data for the cryptos was imported

![screenshot1](https://github.com/nahinhayat/Module10Challenge/blob/main/Module10StarterCode/Module10Screenshots/Screen%20Shot%202023-04-26%20at%2011.26.29%20PM.png)

Then the data was normalized using the StandardScaler Module

![screenshot2](https://github.com/nahinhayat/Module10Challenge/blob/main/Module10StarterCode/Module10Screenshots/Screen%20Shot%202023-04-26%20at%2011.28.28%20PM.png)

The best value for K was then found using the elbow method

![screenshot3](https://github.com/nahinhayat/Module10Challenge/blob/main/Module10StarterCode/Module10Screenshots/Screen%20Shot%202023-04-26%20at%2011.29.49%20PM.png)

Next the cryptos were clustered using the original data

![screenshot4](https://github.com/nahinhayat/Module10Challenge/blob/main/Module10StarterCode/Module10Screenshots/Screen%20Shot%202023-04-26%20at%2011.31.03%20PM.png)

Using PCA data, three new components were created from the original data

![screenshot5](https://github.com/nahinhayat/Module10Challenge/blob/main/Module10StarterCode/Module10Screenshots/Screen%20Shot%202023-04-26%20at%2011.33.20%20PM.png)

After this the process of finding clusters with the original data was done again using the PCA components and these visualizations were composited to compare.


Author: Nahin Hayat https://www.linkedin.com/in/nahinhayat/