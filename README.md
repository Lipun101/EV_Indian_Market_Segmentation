Electric Vehicle (EV) Clustering and Analysis
 ----------------------------------------------------------------------
This repository contains an in-depth analysis of electric vehicle (EV) data, focusing on clustering and segmentation to identify key market segments. The aim is to provide insights into the type of EV the company should produce based on various characteristics such as price, top speed, and range.

Project Overview
--------------------------------------------------------------------------
The project involves several key steps:

Data Preprocessing:  
Standardization of numeric features: Price (Inr), TopSpeed (KmH), Range (Km).

Clustering Analysis:   
K-Means Clustering: Applied to the standardized data to identify distinct segments.  
Cluster Means Calculation: Mean values of Price (Inr), TopSpeed (KmH), and Range (Km) for each cluster.

Segment Profile Visualization:  
Segment Profile Plot: Visual representation of cluster means to understand the characteristics of each segment  

Principal Component Analysis (PCA):  
Segment Separation Plot: Visualizes the separation of clusters in a 2D space defined by the first two principal components.  

Categorical Analysis:  
TopSpeed Category: Categorized vehicles into bins based on top speed and analyzed the distribution across clusters using a mosaic plot.   

Decision Tree Classifier:  
Trained to predict cluster membership and visualized to interpret the decision rules.    

Bubble Plot Analysis  
Bubble Plot: Shows the relationship between range, top speed, and the financial contribution of each cluster.  

Key Findings
--------------------------------------------------    
Cluster Analysis:    
Cluster 1 (Premium High-Performance EVs):  
Characteristics: High price, high top speed, high range.
Target Market: Affluent consumers seeking superior performance and long range.   

Cluster 2 (Mid-Range EVs):  
Characteristics: Moderate price, moderate top speed, moderate range.
Target Market: Consumers seeking a balance between cost and performance.   

Cluster 3 (Affordable Entry-Level EVs):  
Characteristics: Lower price, lower top speed, moderate range.
Target Market: Price-sensitive consumers and urban commuters.  

Recommendations:
------------------------------  
Based on the analysis, it is recommended that the company primarily focus on producing Mid-Range EVs that offer a balance between price, performance, and range. This strategy ensures:    
Broad Market Appeal: Catering to a wide range of consumers.
Financial Stability: Maintaining profitability with moderate production costs.
Scalability and Flexibility: Easier adaptation to market changes and customer preferences.     
By targeting the mid-range segment, the company can establish a strong market presence while also exploring niche segments for premium and entry-level models as supplementary products.    

Visualization Examples  
-------------------------------------------------------    
Segment Profile Plot: Visualizes the mean values of key features for each cluster.
PCA Biplot: Shows the separation of clusters in the PCA space.
Mosaic Plot: Displays the distribution of top speed categories across clusters.
Decision Tree Plot: Interprets the decision rules for predicting cluster membership.
Bubble Plot: Illustrates the financial contribution of each cluster relative to range and top speed.    

Conclusion  
---------------------------------------  
This analysis provides valuable insights into the EV market, helping to inform strategic decisions on the type of EVs to produce. By focusing on mid-range EVs, the company can effectively cater to a broad audience while maintaining financial stability and market flexibility.




  
