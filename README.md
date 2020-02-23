# Movie_rating_prediction

The two main methods of collaborating systems is by using either content based
filtering or collaborative filtering. Content based filtering recommends the user
based on the content whereas collaborative filtering takes into account about how
the user has rated an item (whether he likes or dislikes it). And is based on the
assumption that if ‘n number of users who have given a positive response to a
movie ,will like the similar movies in future.’ And will start recommending the
movie based on the assumption.
In this, I have used a model based on collaborative filtering to predict
the user ratings. The dataset used to train our model is provided by movielens.

With the user awareness of information - security and privacy, the data becomes
less available or the standard of the data reduces which encourages us to use
Singular Value Decomposition or the extended version of it, which is a commonmatrix factorisation method used in the collaborative filtering and is realised by
using algaeberic feature extraction.
The more advanced of SVD ,ie SVD++ achieves a better prediction accuracy as
tested on the provided dataset since it adds implicit feedback information. Which
encouraged us to use SVD++ for our model.
I further pre-processed the given dataset according to a few sets of parameters
which have enabled us to represent the dataset in a better form. The filtered dataset
discards the abnormal entries which have too few rating counts, that we found
difficult to fit in the training dataset.

On the basis of RMSE values, I found that SVD++ model of the surprise package
to be the best model for our training set.

