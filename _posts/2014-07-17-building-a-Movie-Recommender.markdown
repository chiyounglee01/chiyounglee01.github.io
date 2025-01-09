---
layout: default
modal-id: 4
date: 2023-08-09
img: recommender.png
alt: image-alt
project-date: Jan 2025
client: Movie Lens
category: Collaborative Filtering/Content Filtering
description: In this project, I explored two types of recommender systems, collaborative filtering, and content-based filtering. I built my own recommendation system using the <a href="https://github.com/topspinj/tmls-2020-recommender-workshop/tree/master/data" target="blank">MovieLens</a> dataset in Python. Click <a href="https://github.com/chiyounglee01/movie_recommender" target="blank">here</a> for the project's Github repository. <br></br><h1><b>Overview</b></h1><br></br><p>The goal of this project was to develop a model to predict 10 similar movies to a title in the system. The challenge was to build a two models that can predict 10 movies using Collaborative Filtering for the first model and Content Filtering on the second model. The project used <b>Python</b> code.</p><p>This project is based on this <a href="https://www.youtube.com/watch?v=XfAe-HLysOM" target="blank">tutorial</a> from Jill Cates (Data Scientist, Shopify).</p><p>The tools used include pandas (for data manipulating), scikit-learn (ecosystem for KNN models), scipy.sparse (to make sparse matrices for matrix factorization), sklearn.metrics.pairwise (to calculate cosine similarity), and Seaborn (for visualization). The KNN model with Cosine Similarity scores was used as the main metric for the Collaborative Filtering model. The 10 highest Cosine Similarity scores was used for the Content Filtering model.</p><br></br><p><b>With this project I wanted work with both collaborative filtering and content filtering and answer the following question:</b></p><p>*Can we get decent predictions to show the 10 movies that are most similar to Toy Story?</p><br></br><h1>General Summary</h1><br></br><p><b>Using collaborative filtering to generate recommendations for users.</b></p><br></br><p>Collaborative filtering is based on the premise that similar users will like similar movies. To make a model using this technique, we first need to transform our data into a user-item matrix. In this matrix, rows represent users and columns represent movies. There were 610 movies with 9724 movies in the dataset.  The image below describes the transformation of the dataset into a user-item matrix.</p><br></br><img src="https://raw.githubusercontent.com/chiyounglee01/images/main/collaborative_filtering.png"><p>Then we use the KNN (K-Nearest Neighbors) model with cosine similarity as the metric to find the 10 movies that have most similar use engagement vectors for movie i.</p><br></br><p>The recommendation system seems to be working well as it has recommended family friendly movies from the 90s.</p>




---
