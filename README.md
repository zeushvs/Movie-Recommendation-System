This project implements a Movie Recommendation System using collaborative filtering techniques powered by Singular Value Decomposition (SVD) and Principal Component Analysis (PCA).
Collaborative filtering works by analyzing user-item interactions, in this case, movie ratings, to identify patterns of preferences and predict what movies a user is likely to enjoy.
By factorizing the user–movie rating matrix with SVD, the system learns latent factors that capture hidden relationships between users and movies, allowing it to predict ratings for 
unseen items. Similarly, PCA is applied to reduce dimensionality and extract key components of user behavior, which helps in reconstructing preferences and generating recommendations.

The project provides functionality to train models on a dataset of movie ratings, evaluate their performance using metrics like RMSE, and generate top-N movie recommendations for any user.
It highlights the trade-offs between SVD and PCA approaches, while also showcasing how linear algebra techniques can be effectively used in real-world recommendation systems. This 
repository is useful for students, researchers, and developers interested in understanding the foundations of recommender systems and experimenting with classic machine learning 
techniques before moving on to deep learning or hybrid recommendation methods.
