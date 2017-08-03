# content based recommendation system

[![Datmo Model](https://datmo.io/shabazp/content-based-recommendation-system/badge.svg)](https://datmo.io/shabazp/content-based-recommendation-system)

In this example, we'll build an implicit feedback recommender using the Movielens 100k dataset (http://grouplens.org/datasets/movielens/100k/).
The code behind this example is available as a Jupyter notebook
LightFM includes functions for getting and processing this dataset, so obtaining it is quite easy.

In particular, it prepares the sparse user-item matrices, containing positive entries where a user interacted with a item, and zeros otherwise. We have two such matrices, a training and a testing set. Both have around 1000 users and 1700 items. We'll train the model on the train matrix but test it on the test matrix.
