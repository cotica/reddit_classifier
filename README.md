# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 3: Classifying Reddit Posts

### Problem statement

We are producing a trivia focused / Jeopardy or Who Wants to Be a Millionaire* style game show, where we want the audience to guess the source of the movie details. Everything is scrambled together! The task: figure out if the details came from good movie details, or whether the movie production team took a shorcut and landed in _Sh**ty Movie Details_!

*(trademarks of their appropiate productions) 


### Primary techniques

1. Using [Pushshift's](https://github.com/pushshift/api) API, we collect posts from two subreddits.
2. We use NLP to train a classifier on which subreddit a given post came from.


### Data sources

The following Reddits were scraped:

* [Movie Details](https://www.reddit.com/r/MovieDetails/)
* [Sh**ty Movie Details](https://www.reddit.com/r/shittymoviedetails/)

---

### Pre-processing, EDA and modeling flow

* We gather and prepare data using the `requests` library and PushShift API, collecting _X_ posts
* We use _count vectorizer_ to count up words in our resulting data sets
* We strip the data of ____
* We select the following features to train on: ______
* We model using Logistic Regression and KNN
* Grid search is used to improve parameters and performance, ultimately resulting in ____ being selected for the final model.
* We score the models using ____
  
---

### Key findings and recommendations

_Insert key findings_

---

### Presentation and report

_To be linked here_
