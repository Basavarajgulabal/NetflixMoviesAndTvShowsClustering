
![image](https://github.com/Basavarajgulabal/NetflixMoviesAndTvShowsClustering/assets/121421909/d2bb2baf-b4a8-4d9d-bd7a-f430c79d27c8)





Netflix Movies And Tv Shows Clustering


Problem Statement


The problem at hand involves exploring the Netflix dataset to gain insights into the content available on the platform. The dataset provides information about movies and TV shows, their attributes, and their availability in different countries. By integrating this dataset with external sources such as IMDB ratings and Rotten Tomatoes, we can extract further valuable information.

The specific tasks to be performed in this project include:


1-Exploratory Data Analysis (EDA): Cleaned the data, unnested the Netflix content and tackled the null/missing values and conduct a thorough analysis of the dataset to uncover trends, patterns, and correlations among different attributes.

2-Understanding Content Availability: Determine the types of content available in different countries and identify any variations or preferences.

3-Analyzing Netflix's Focus: Investigate whether Netflix has been increasingly focusing on TV shows rather than movies in recent years.

4-Clustering Similar Content: Utilize text-based features to cluster similar content, enabling the development of a content-based recommender system.



Project Summary

The aim of this project is to analyze the Netflix dataset, which includes information on movies and TV shows available on the platform until 2019. With over 220 million subscribers, Netflix is the world's largest online streaming service provider. By analyzing and clustering the content, we can enhance the user experience through a personalized recommendation system, potentially reducing subscriber churn.

The project follows a step-by-step process, as outlined below:

1-Handling Missing Values: Address any null or missing values present in the dataset.

2-Dealing with Nested Columns: Process nested columns such as director, cast, listed_in, and country to facilitate clear visualization and analysis.

3-Rating Binning: Categorize ratings into appropriate categories, including adult, children's, family-friendly, and not rated content.

4-Exploratory Data Analysis (EDA): Perform in-depth EDA on various attributes, uncovering valuable findings to aid in churn prevention.

Cluster Creation: Create clusters using attributes such as director, cast, country, genre, rating, and description. Tokenize, preprocess, and vectorize the attribute values using TF-IDF vectorizer.

5-Dimensionality Reduction: Reduce the dimensionality of the dataset using Principal Component Analysis (PCA) to improve performance.

6-Clustering Algorithms: Employ K-Means Clustering and Agglomerative Hierarchical Clustering algorithms to construct two distinct types of clusters. Determine the optimal number of clusters using methods like the Elbow method, Silhouette score, and Dendrogram.

