This repository contains the implementation of K-means clustering on the IMDB Movie Reviews dataset to cluster movie reviews based on ratings and analyze whether movies within the same rating clusters belong to the same genre.

Key Objectives:
Data Preprocessing and Feature Extraction:

Preprocess the dataset to categorize movies into three clusters based on ratings:

Top Rated: ≥ 8

Average Rated: 6 to 7

Low Rated: < 6

K-means Clustering from Scratch:

Implement K-means clustering using Numpy to group reviews based on rating scores.

Implement a convergence check to stop clustering when centroids no longer change.

Assign labels to each movie based on its cluster.

Genre Analysis and Model Evaluation:

Compare Genres Within Clusters: Evaluate if movies within the same cluster belong to the same genre.

Evaluation Metrics: Use a confusion matrix to compare the cluster ratings with the original ratings and assess the clustering model's accuracy.

Visualization:

Visualize the clusters, providing insights into how movies with different ratings are grouped.

Tasks and Deliverables:
Data Preprocessing and Feature Extraction:

Use the IMDB dataset to extract features such as rating, votes, revenue, and meta scores.

Classify movies based on their ratings into predefined clusters.

K-means Clustering Implementation:

Implement the K-means algorithm from scratch using Numpy.

Implement a convergence check to stop the clustering when centroids no longer change.

Assign labels to the clusters.

Evaluation and Genre Analysis:

Analyze whether movies within the same cluster belong to the same genre.

Evaluate the performance using confusion matrices.

Visualizations:

Use matplotlib or other suitable libraries to visualize the clusters and their relationship with movie genres and ratings.
