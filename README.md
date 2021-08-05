# Summary


Amazing Prime is a company that's subdivision, Amazing Prime Video, hosts a variety of movies and shows. The company has a plan to build an algorithm to predict which low-budget movies being released will become popular so they can buy the streaming rights. To do this, they have decided to sponsor a hackathon, which includes providing a clean dataset of movies and asking the participants to predict the movies that will be a success.

To create the clean dataset, we were provided with a scrape of Wikipedia data on movies released since 1990, and rating data provided from the MovieLens website. From there, we combine the two datasets and transform the data.

After this was done, we were then tasked with having this dataset be refactored to be used again on a daily basis by way of ETL functioning. The codes in this repository function like so, and are able to be exported into a SQL database and read accordingly.
Below are examples of the ratings data and movie data being exported and read back as a query.


![movies](https://github.com/BrieonaT/Movies-ETL/blob/main/Resources/movies_query.png)
![ratings](https://github.com/BrieonaT/Movies-ETL/blob/main/Resources/ratings_query.png)
