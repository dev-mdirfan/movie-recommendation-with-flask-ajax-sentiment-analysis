# Movie Recommendation using sentiment analysis of reviews with flask and ajax

**Features Used:**

- Machine Learning
- Flask
- TMDB API
- AJAX
- Web Scraping through BeautifulSoup
- Review Sentiment Analysis

## Introduction

This is a movie recommendation system based on the sentiment analysis of reviews. The system is built using flask and ajax. The dataset used is the IMDB dataset which is available on Kaggle. The dataset contains 50,000 reviews of movies. The dataset is divided into 25,000 reviews for training and 25,000 reviews for testing. The dataset is balanced in the sense that it contains equal number of positive and negative reviews. The dataset is preprocessed and the reviews are converted into vectors using the bag of words model. The vectors are then fed into a neural network which is trained to classify the reviews as positive or negative. The trained model is then used to predict the sentiment of the reviews. The reviews are then ranked based on the sentiment and the top 10 movies are recommended.

## Requirements

### Installation

- [requirements.txt](requirements.txt)

**Note:** If you fail to install any of the dependencies, try installing them individually using `pip install <dependency-name>`. Otherwise, you need to run `%pip install <dependency-name>` in the jupyter notebook cell.

### Dataset

<!-- - [IMDB Dataset](https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
- [GloVe](https://www.kaggle.com/thanakomsn/glove6b300dtxt) -->
- IMDB 5000 Movie Dataset - [movie_metadata.csv](https://www.kaggle.com/datasets/carolzhangdc/imdb-5000-movie-dataset?select=movie_metadata.csv)
- [credits.csv](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset?select=credits.csv)
- [movies_metadata.csv](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset?select=movies_metadata.csv)
- [reviews.txt](model/reviews.txt) for sentiment analysis

### API

- [TMDB](https://www.themoviedb.org/documentation/api)

## Steps

- [movie_metadata.csv](https://www.kaggle.com/datasets/carolzhangdc/imdb-5000-movie-dataset?select=movie_metadata.csv) Data Preprocessing into [new_movie_metadata.csv](model/new_movie_metadata.csv)
- [credits.csv](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset?select=credits.csv) Data Preprocessing into [new_credits.csv](model/new_credits.csv)


## References

- [youtube](https://www.youtube.com/live/A_78fGgQMjM)
