# Movie Recommendations

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ConnorJamesRice/PCA-Movie-Recommendations/blob/main/matrix_completion_and_recommendation_systems.ipynb)

This is a trained movie recommendation model using the 100k MovieLens dataset, which is available at [MovieLens](https://grouplens.org/datasets/movielens/100k/) or can be uploaded as 'u.data'. The dataset is in the format of 'user', 'movie', 'ranking', and 'time', but we focus on the first three columns, ignoring the time.

## Estimator Approaches
Inside the notebook, you will find four different estimator approaches, all based on PCA models:

1. **Mean Rating Estimator:** This approach calculates the mean of movie rankings, but it may not provide highly useful recommendations.

2. **SVD Decomposition:** This method uses Singular Value Decomposition with rank-d approximations. While SVD is valuable for tasks like image compression, it might not be the best choice for movie recommendations due to its high error.

3. **Alternating Estimator:** This model uses an alternating approach with fixed hyperparameters, potentially providing more accurate recommendations. It iterates through the same amount of demensions as SVD.

4. **K-Nearest Neighbors (K-NN):** The K-NN approach uses a full hyperparameter grid search to make movie recommendations, offering another useful option.

## Notebook Details
Inside the notebook, you will find detailed explanations of each section, including how the models work and their performance.

Feel free to explore the notebook to gain a deeper understanding of the movie recommendation system and its various approaches.

