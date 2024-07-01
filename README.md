
# Spoiler Detection Model



## Introduction

In this Repository you will find this file as well as [the data cleaning notebook](https://github.com/vaniasmithh/Spoiler-Detection-Model-2/blob/main/Spoiler_Detection_Data_Cleaning.ipynb) and [the feature extraction and model traning notebook]. A link to the dataset has been provided below.

### Motive

Movie reviews have been an integral part of the movie-watching experience, offering audiences a chance to share their thoughts, critiques, and commentary on the latest releases. Platforms like IMDb, Rotten Tomatoes, and other movie review blogs have become essential spaces for movie lovers to exchange views and discover new films. However, one significant issue that disrupts the enjoyment of these platforms is the prevalence of spoilers in reviews. Spoilers can reveal critical plot points, surprise twists, or the fate of characters, potentially ruining the experience of watching a film without prior knowledge of its key details. This project’s goal is to develop a robust spoiler detection model to filter out unwanted spoilers in movie reviews. Using the [IMDB spoiler dataset](https://www.kaggle.com/rmisra/imdb-spoiler-dataset) found on Kaggle, the model will apply text mining and sentiment analysis techniques to classify reviews. It will help create and improve user experience for those who seek to enjoy films without encountering spoilers in online reviews.

### Data Preprocessing

The dataset contains two files: one with movie details and one the the review details, so the first step is to join them on the common field `movie_id`. Then, data cleaning to remove punctuation, special characters, numbers, etc. was applied to the `review_text` column. The cleaned text column, now called `cleaned_review`, was then used to apply traditional text preprocessing techniques such as lowercasing, stop word removal and lemmatization. With that, the dataset was ready for feature extraction. 

## Feature Extraction

### TF-IDF 

TF-IDF or Term Frequency-Inverse Document Frequency is a feature extraction technique that can be used to evaluate the importance of a specific word in a document, relative to the collection of documents. It is implemented using Python's `scikit-learn` library.

### Bag of Words

Bag of Words is a technique used in text mining and NLP projects to represent data by converting text into numeric feature vectors to be used in machine learning algorithms. It is implemented using Python's `scikit-learn` library.







## Model Training and Evaluation

Four Machine Learning models will be trained and evaluated for this project.

### Logistic Regression

### Support Vector Machine

### Random Forest

### Bi-LTSM
