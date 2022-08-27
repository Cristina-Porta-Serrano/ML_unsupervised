# ML_unsupervised
M08 T01



## State of art

The 'Facebook Live Sellers in Thailand' is a dataset curated in UCI Machine Learning Datasets. The data contains 7050 observations and twelve attributes. The data is about live selling feature on the Facebook platform. Each record consists of information about the time live information of sale is posted to Facebook and engagements in the data. The engagements are regular Facebook interactions such as share and emotion rection. Details and academic publications relating to the data is available from the source https://archive.ics.uci.edu/ml/datasets/Facebook+Live+Sellers+in+Thailand.

* *Attributes (explanatory variables):*

*status_id: id of the status published.


*status_type: this refers to the type of facebook element to analyse: photo, video, status or link.


*status_published month/day/year and hour the status was published.


*num_reactions: number of reactions that the status got: it is the addition of the likes, loves, wows, hahas, sads and angrys.


*num_comments: number of comments that the status got.


*num_shares: number of shares that the status got.


*num_likes: number of likes that the status got.


*num_loves: number of loves that the status got.


*num_wows: number of wows that the status got.


*num_hahas: number of hahas that the status got.


*num_sads: number of sads that the status got.


*num_angrys: number of angrys that the status got.


*Column1/2/3/4: this columns have no data or info. 


## Conclusions

We have used two different clustering models for our data: K-means and Hierarchical clustering. The conclusions are the following:

- K-means is not a good model for our data. We achieve a relatively high accuracy of 65% with k = 2 but the inertia is very high.

- Otherwise, with agglomerative clustering we have the same number of clusters and a very high silhouette score (0'9) which means that this model performs better with our data.

## Requirements

This notebook requires a Python 3.6 or newer version.

To run this notebook you must have installed the following libraries:

    pip install pandas
    pip install numpy
    pip install matplotlib
    pip install seaborn
  
