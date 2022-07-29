# Netflix_Movies_and_TVShows_Clustering
![start slide](https://www.theclick.gg/wp-content/uploads/2021/08/netflix-gaming-tests.jpg)

# PROBLEM STATEMENT

Netflix The firm was founded in 1999 and is now recognized as one of the largest international firms in this field. It has over 6.3 million subscribers and over 100,000 DVD titles in order for the customer to choose from. Netflix has maintained a competitive strategy by having a business model based upon fast delivery, a no late-fees policy, and a very useful return in the mail system.
 	This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.  In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.  Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.

# ALGORITHMS USED:
1.	## KMEANS-SILHOUTTE SCORE, ELBOW METHOD
2.	## DBSCAN
3.	## HIERARCHICAL CLUSTERING-AGGLOMERATIVE
4.	## PCA

# CONCLUSION:

•	In EDA part we observed that

i.	Netflix has 69% of its content as movies, so movies are  more popular on Netflix than TV shows.

ii.	United States has the most number of movies and shows followed by India and United Kingdom.

iii.	United States has the most number of movies and shows followed by India and United Kingdom.

iv.	TV-MA rated content is maximum in number in the dataset. This rating indicates that the content is for mature and adult audience above the age of 17.

v.	There is an exponential raise in the number of TV shows and movies distributed by Netflix in the recent years.

•	Text cleaning and vectorization was done on the combined features of the dataset which includes origin country, leading cast member, rating type, content type and description for clustering analysis.

•	Optimal number of clusters were found out to be 25 with silhouette coefficient value of 0.0279

•	Principal component analysis was performed in order to reduce the higher dimensionality which improved the silhouette coefficient to 0.35. Even though there's improvement in the silhouette score, these cannot be compared as these are two different method of pre processing is involved.

•	Recommendation based on cosine similarity is also done on the same transformed data.


