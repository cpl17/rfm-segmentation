Data: The original dataset is historical purchase data for an E-Commerce site. 


Repo Includes: 

* __Segmentation__

	* _RFM_Segmentation_ : In this notebook, I built a Recency, Frequency, and Monetary Value DataFrame and segmented according to the sum of bucketed scores for each. Then I produced a projected 
2d visualization using tsne, to ensure the segments were built correctly.

	* _K-Means_: Here I compared the clusters determined by K-Means to those using the bucket scores. Additionally, I derived attribute importances in both the k=3,5 clusters to determine what was driving 
the grouping. 


* __Predict Purchase Volume__ - Here I used lagged purchase volume and RFM stats to predict how much a customer would purchase in the following month. 

  

* __Cohort Analysis and CLV__ - In this notebook, grouped customers into cohorts based on the month of their first purchase. Then, after pivoting along month, I compared retention rates and purchasing
statistics for each cohort across the year. Then, I used the Basic, Granular, and Traditional methods of predicting CLVs and visualized the distribution of each.
