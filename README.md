# algo-movie_recommendation

We live in a world which is full of data and everyday we encounter new data which is stored for processing and analysis. For analysing the data it is mostly grouped in clusters or categories and then processed. Even when it comes to learning a new label in the data, it is generally compared with the known labels based on similarity or dissimilarity. Thus, classification systems are generally either supervised or unsupervised, depending on whether a finite number of distinct supervised classes or unsupervised groups is allocated new inputs. 
A most important kind of unsupervised learning problem is clustering. It has been an emerging topic due to its variety of applications including image processing, economics and medicine. In simple terms, it is a process which partitions a given dataset into homogeneous groups based on given features such that similar objects are kept in a group whereas dissimilar objects are kept in different groups. It deals with finding structure in a collection of unlabeled data and there are two major types of clustering: partitioning and hierarchical clustering and we cover both of them in this paper.
In order to deeply understand these algorithms and compare them we have used a movie dataset to analyse the movie features and create a recommendation engine. Our goal is to figure out the best way to recommend movies to the users. So our ground truth will be comparing recommended movies to the user’s movie history. This will be measured by using RMSE, which measures the relative error analysis to the ground truth.
