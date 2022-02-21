# Cryptocurrencies

## Overview 
A Prominent Investment bank willing to dive into cryporocyrrency investment portfoloio for it's customer, This project is to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

## Resource
  **Data Source** : crypto_data.csv
  
  **Data Tools** : Python and its Libraries like Pandas, hvplot, plotly, sklearm
  
  **Software** : Microsft Visual Code, Github.
  
  ## Visualization Results
  **Elow Curve** : By using unsupervised machine learning, we can categorize active cryptocurrencies in 5 groups on the market. Using elbow method, it allowed us to identify clusters with diminishing return.
  
  ![elnow_curve](https://user-images.githubusercontent.com/91766890/154875626-1f39e473-6576-4543-91b0-2c3392bf5ac0.png)

  **3D Scatter Plot** : By using a 3d scatter plot we visualized the classifictions of the cryptocurrencies.

  ![3dScatter](https://user-images.githubusercontent.com/91766890/154875669-6315cfb2-3531-4ccb-a99b-3c1ec6583dfa.png)
  
  **hvPlot Table** : By sorting on Class column we get a sense of cluster sizes. Most of the cryptocurrencies are in Class 0 and 1, with only BitTorrent in Class 4.

  ![HvplotTable](https://user-images.githubusercontent.com/91766890/154875720-a8349615-b2e4-4119-b28e-528ff7aecfe1.png)

**hvplot** : If we limit our axis and avoid the extreme outliers, we have the final plot.

  ![hvplot](https://user-images.githubusercontent.com/91766890/154875821-f3f91d61-6d90-4235-ac43-8d134eb4b190.png)

## Summary

We demonstrated that cryptocurrencies can be clustered by using unsupervised machine learning. While there are differences between all cryptocurrencies, there are definitive categorizations by our finding. We not only have found clustering patterns, but also identified outliers. Our finding will definetly help to new customer who wants to invest  in crypocurrencies further explore the world of cryptocurrencies.
