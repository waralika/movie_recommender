# movie_recommender

##Overview

This is the code for building a movie recommender System . The code uses the lightfm recommender system library to train a hybrid content-based + collaborative algorithm that uses the WARP loss function on the movielens dataset. The movielens dataset contains movies and ratings from over 1700 users. Once trained, the script prints out recommended movies for whatever users from the dataset that one chooses to terminal.

##Dependencies

numpy (http://www.numpy.org/)

scipy (https://www.scipy.org/)

lightfm (https://github.com/lyst/lightfm)
