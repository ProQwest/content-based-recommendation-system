# content based recommendation system

[![Datmo Model](https://datmo.com/shabazp/content-based-recommendation-system/badge.svg)](https://datmo.com/shabazp/content-based-recommendation-system)

In this example, we'll build an implicit feedback recommender using the Movielens 100k dataset (http://grouplens.org/datasets/movielens/100k/).
The code behind this example is available as a Jupyter notebook
LightFM includes functions for getting and processing this dataset, so obtaining it is quite easy.

In particular, it prepares the sparse user-item matrices, containing positive entries where a user interacted with a item, and zeros otherwise. We have two such matrices, a training and a testing set. Both have around 1000 users and 1700 items. We'll train the model on the train matrix but test it on the test matrix.

Clone this model on your local machine with the Datmo CLI

     $ datmo clone shabazp/content-based-recommendation-system

Now you can run the set of commands below to better understand the advantages of converting a repository to a Datmo Model. 

First you can check out all of the snapshots that have already been created by the user. This is equivalent to checking out the snapshots tab on Datmo except without the search and filter capabilities available on the GUI.

     $ datmo snapshot ls 

Once you have viewed all of the existing snapshots, you can start by running an experiment by simply running the notebook below which will run the Jupyter notebook and enable you to run piece of code to train the model.

     $ datmo task run "jupyter notebook" --port 888

After you're done, open another terminal or use the same one to create your first snapshot, by running the following command 

     $ datmo snapshot create -m "my first snapshot"
     
Congrats! You have created your first snapshot and are ready to continue building on top of it. Check out more commands on [our docs here](https://docs.datmo.com).

Happy Building :)

