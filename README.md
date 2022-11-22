# Netflix Movies and TVShows Clustering
![start slide](https://www.theclick.gg/wp-content/uploads/2021/08/netflix-gaming-tests.jpg)

# 📖PROBLEM STATEMENT

Netflix The firm was founded in 1999 and is now recognized as one of the largest international firms in this field. It has over 6.3 million subscribers and over 100,000 DVD titles in order for the customer to choose from. Netflix has maintained a competitive strategy by having a business model based upon fast delivery, a no late-fees policy, and a very useful return in the mail system.
 	This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.  In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.  Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.
-----------------------------------------------------
# 📖ALGORITHMS USED:
1.	## KMEANS-SILHOUTTE SCORE, ELBOW METHOD
2.	## HIERARCHICAL CLUSTERING-AGGLOMERATIVE
3.	## PCA
-----------------------------------------------------
# 📖Dataset features
Show id: Unique ID for every Movie / TV Show
type – Identifier - A Movie or TV Show
title – Title of the Movie / TV Show
director-director of the content
cast –Actors involved in the movie / show
country – Country where the movie / show was produced
date_added – Date it was added on Netflix
release_year – Actual Release year of the movie / show
rating – TV Rating of the movie / show
duration – Total Duration - in minutes or number of seasons
listed_in – genre
description – The Summary description

-----------------------------------------------------
# 📖CONCLUSION:

•	In EDA part we observed that

i.	Netflix has 69% of its content as movies, so movies are  more popular on Netflix than TV shows.

ii.	United States has the most number of movies and shows followed by India and United Kingdom.

iii.	United States has the most number of movies and shows followed by India and United Kingdom.

iv.	TV-MA rated content is maximum in number in the dataset. This rating indicates that the content is for mature and adult audience above the age of 17.

v.	There is an exponential raise in the number of TV shows and movies distributed by Netflix in the recent years.

•	Text cleaning and vectorization was done on the combined features of the dataset which includes origin country, leading cast member, rating type, content type and description for clustering analysis.

•	Optimal number of clusters were found out to be 5 with silhouette coefficient value of 0.36

•	Principal component analysis was performed in order to reduce the higher dimensionality which improved the silhouette coefficient to 0.35. Even though there's improvement in the silhouette score, these cannot be compared as these are two different method of pre processing is involved.

•	Recommendation based on cosine similarity is also done on the same transformed data.
-----------------------------------------------------
# 📋 Execution Instruction
The given IPython Notebook can be either downloaded to be run on your local Jupyter Notebook or can be directly run on Google Colab.

# 📜 Credits
Mahima Phalkey | Data Scientist | Machine Learning Engineer | Data Science enthusiast

Special thanks to AlmaBetter

Contact me for Data Science Project Collaborations

[![image](https://user-images.githubusercontent.com/95841292/202914376-d5a83f3d-110a-4476-896e-1da078b185dc.png)](https://www.linkedin.com/in/mahima-phalkey/) [![image](https://user-images.githubusercontent.com/95841292/202914715-787f6ae3-d9f6-491c-9cae-c717131ddebd.png)](https://github.com/Mahima2208) [![image](https://user-images.githubusercontent.com/95841292/202914883-bce71634-6c2b-4305-8020-4b240cb76e41.png)](https://medium.com/@mahimaphalkey) [![image](https://user-images.githubusercontent.com/95841292/202914940-5d5eba71-e45d-4e95-8dfe-65e45d255aec.png)](https://drive.google.com/file/d/1Xi9oBrCjMc3QPGAhFdfO5rnMUssLa7Hw/view?usp=sharing)


#📚 References

https://towardsdatascience.com/netflix-recommender-system-a-big-data-case-study-19cfa6d56ff5

https://medium.com/analytics-vidhya/netflix-movies-and-tvshows-exploratory-data-analysis-eda-and-visualization-using-python-80753fcfcf7

https://www.kaggle.com/datasets/satpreetmakhija/netflix-movies-and-tv-shows-2021

