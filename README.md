# Cryptocurrencies
# :anchor:Unsupervised Machine Learning:anchor: 

## Overview
Cryptocurrencies investment might get a great return, also might be a huge lost. Cryptocurrencies analysis can help us grasp the overall situation of cryptocurrencies. Upsupervised machine learning is an appropriate way to group the cryptocurrencies and visualize the results.
- Preprocessing tha Data for further analysis.
- Using PCA to reduce data dimensions.
- Using elbow curve to determine k value for KMeanss.
- Visualize the results with scatter plots and an interactive table.

## Results
1.  Data preparation

    Data frame was created from data source, then preprocessed by removing null values, selecting certain columns, and standardizing the data. 
    532 mined and being traded cryptocurrencies were retrieved.

2.  PCA 
   
    The data dimension was reduced to three pricipal components.

3.  Elbow Curve

  - The best cluster number(k=4) was chosen from elbow curve.
 
    ![Elbow Curve](https://user-images.githubusercontent.com/105877888/192126490-0dbc9d9f-d6a5-4ba0-91bb-55990372a1e2.png)

  - New data frame incluing predicted clusters and cryptocurrencies features.
  
    ![Clustered_df](https://user-images.githubusercontent.com/105877888/192126689-08986e81-65d8-4793-a8ff-437d44c5e6c8.png)

4.  Visualization
  - 3D scatter figure shows four clusters based on axes of three principal components.
  
    ![3D-Scatter](https://user-images.githubusercontent.com/105877888/192126710-26d725e5-6b2f-44da-bd67-9232bbba8071.png)

  - Interactive table (sortable and selectable) of tradable cyptocurrencies.
  
    ![Coin Table](https://user-images.githubusercontent.com/105877888/192126732-46bc4e56-eaae-4890-a287-ef2dbcbef856.png)

  - Scatter plot of TotalCoinSupply vs TotalCoinsMined
  
    ![Plot_df](https://user-images.githubusercontent.com/105877888/192126740-9de323c3-a3a4-4ffd-a9cb-46f52cd20c65.png)
 
## Summary
  - Compare to original data, only half of cryptocurrencies are tradable. These cryptocurrencies can be goruped into four clustered with unsupervised machine learning model. It is easy to check which coins belong to the same clusters.
  - Knowing the coin clusters, cryptocurrencies in the same cluster can be analyzed with supervised machince learning models and make predictions to see which coins are worth to make investment.
  - Take into account of risk, advisory service team may suggest clients to purchase cryptocurrencies from different groups, or completely opposite groups to make a better balance. So that even if the clients lost or got no intrest from one group, they will probably gain from another group.
