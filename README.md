# movie-recommendation-model
Movie Recommendation model
In this model I have tried implementing a few recommendation algorithms (content based, popularity based ad collabarative filtering)
I have tried to build a hybrid movie recommendation model that takes into account the metadata( genres,keywords,rating, cast and crew) and also the ratings given by  the user.
The dataset used has been taken from https://www.kaggle.com/rounakbanik/the-movies-dataset and Rounak's work has been inspiring and have learned the usage of several algorithms from his work.

Content of the dataset:
movies_metadata.csv: The main Movies Metadata file. Contains information on 45,000 movies featured in the Full MovieLens dataset. Features include posters, backdrops, budget, revenue, release dates, languages, production countries and companies.

keywords.csv: Contains the movie plot keywords for our MovieLens movies. Available in the form of a stringified JSON Object.

credits.csv: Consists of Cast and Crew Information for all our movies. Available in the form of a stringified JSON Object.

links.csv: The file that contains the TMDB and IMDB IDs of all the movies featured in the Full MovieLens dataset.

links_small.csv: Contains the TMDB and IMDB IDs of a small subset of 9,000 movies of the Full Dataset.

ratings_small.csv: The subset of 100,000 ratings from 700 users on 9,000 movies.

The Full MovieLens Dataset consisting of 26 million ratings and 750,000 tag applications from 270,000 users on all the 45,000 movies in this dataset can be accessed here.

Acnowledgements
The dataset has been taken fro Rounak's work on kaggle where he has collected data from different sources. https://www.kaggle.com/rounakbanik/the-movies-dataset

The dataset is collected from TMDB and GroupLens

Inspiration
Having jumped into data sceince and thinking of the problems that can be solved via various ML algorithms. Movie recommendation is something that came into my mind first while browsing Netflix which has by far the best recommendations. That is when I decided i should pick up this project to learn the techniques of browsing through data using python and use NLP to find similarity between movies and also use collabaritve filtering. The results have come out to be pretty interesting. Results for some of the movies can be seen below

