# ALS
北航2020数据挖掘导论：Clustering for Amyotrophic Lateral Sclerosis (ALS)


This case-study examines the patterns, symmetries, associations and causality in a rare but devastating disease, amyotrophic lateral sclerosis (ALS). ALS demands conducting clinical trials and collecting big, multi-source and heterogeneous datasets that can be interrogated to derive potential biomarkers. Overcoming many scientific, technical and infrastructure barriers is required to establish complete, efficient, and reproducible protocols (pipelines/workflows) starting with acquiring raw data, preprocessing, aggregation, harmonization, analysis, visualization and result interpretation. The dataset is in the folder clustering.


The clinical data shows that the rate of ALS progression varies significantly among patients. Majority of the patients die within 3 to 5 years after ALS onset, however, a few are able survive for over 10 years. This heterogeneity of disease course hinders demonstration of its biological mechanism and development of effective treatment. We need to develop reliable predictive models of ALS progression to understand the pathophysiology of the disease. Now perform the clustering analysis according to the following procedures for the ALS dataset.
+ Load and prepare the data.
+ Perform summary and preliminary visualization.
+ Train a K-Means model on the data, select an appropriate K by using the Elbow method. (Please refer to the following procedures: 
1. Compute clustering algorithm (e.g., K-means clustering) for different values of k. For instance, by varying k from 1 to 10 clusters. 
2. For each k, calculate the total within-cluster sum of squared errors (SSE). 
3. Plot the curve of SSE according to the number of clusters k. The location of a bend (knee) in the plot is generally considered as an indicator of the appropriate number of clusters. )
+ Evaluating the model performance by report the center of clusters and explain details. You can also interpret the clustering results by inspecting the data near the center.


Reference: Tang, M., Gao, C, Goutman, SA, Kalinin, A, Mukherjee, B, Guan, Y, and Dinov, ID. (2018) Model-Based and Model-Free Techniques for Amyotrophic Lateral Sclerosis Diagnostic Prediction and Patient Clustering, Neuroinformatics, 1-15, DOI: 10.1007/s12021-018-9406-9.


Using the dataset to perform an association rules analysis, and comment on the results. Your discussion should provide interpretations the meanings of the various output statistics (lift ratio, confidence, and support) and include a very rough estimate of the extent to which this will help Exeter make an informed choice about which catalog to cross-promote to a purchaser.
