# Netflix_Movies_and_TV_Shows_Clustering

![WhatsApp Image 2023-08-31 at 12 07 26](https://github.com/ShriyaChouhan/Netflix_Movies_and_TV_Shows_Clustering/assets/128309746/1dd6d65c-464c-401d-83f4-f2e810fd0591)


## Introduction:
_____________________________________________________________________________
With more than 83 million subscribers and presence in more than 190 countries, Netflix is the most popular Internet television network in the world. Its users watch more than 125 million hours of TV and movie content daily, including original series, documentaries, and feature films. On almost any screen that is linked to the Internet, members can watch as much as they want, whenever and wherever. Without interruptions or obligations, members can play, pause, and resume watching at any time.

## Problem Statement
_________________________________________________________
* Netflix is the world's largest online streaming service provider, with over 220 million subscribers as of 2022-Q2. It is crucial that they effectively cluster the shows that are hosted on their platform in order to enhance the user experience, thereby preventing subscriber churn.
* We will be able to understand the shows that are similar to and different from one another by creating clusters, which may be leveraged to offer the consumers personalized show suggestions depending on their preferences.
* The goal of this project is to classify/group the Netflix shows into certain clusters such that the shows within a cluster are similar to each other and the shows in different clusters are dissimilar to each other.

## Dataset Description
_______________________________________________________
The dataset "Netflix Movies and TV Shows Clustering" comprises 12 columns, with only one column having an integer data type. It does not contain any duplicate values, but it does have null values in five columns: director, cast, country, date_added, and rating.

This dataset provides a valuable resource for exploring trends in the range of movies and TV shows available on Netflix. Additionally, it can be utilized for developing clustering models to categorize similar titles together based on shared attributes such as genre, country of origin, and rating.

## Project Summary
______________________________________________________
Dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.

In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

In this project, we worked on a text clustering problem where we had to classify/group the Netflix movie/shows into certain clusters such that the shows within a cluster are similar to each other and the shows in different clusters are dissimilar to each other.

## The project follows a step-by-step process, as outlined below:---
## 1. Handling Missing Values:
      Address any null or missing values present in the dataset.
## 2. Dealing with Nested Columns:
      Process nested columns such as director, cast, listed_in, and country to facilitate clear visualization and analysis.
## 3. Rating Binning:
      Categorize ratings into appropriate categories, including adult, children's, family-friendly, and not rated content.
## 4. Exploratory Data Analysis (EDA):
      Perform in-depth EDA on various attributes, uncovering valuable findings to aid in churn prevention.
## 5. Cluster Creation: 
      Create clusters using attributes such as director, cast, country, genre, rating, and description. Tokenize, preprocess, and vectorize the attribute values using TF-IDF vectorizer.
## 6. Clustering Algorithms: 
      Employ K-Means Clustering and Agglomerative Hierarchical Clustering algorithms to construct two distinct types of clusters. Determine the optimal number of clusters using methods like the Elbow method and Dendrogram.
____________________________________________________


## Input Files:
_________________________
NETFLIX MOVIES AND TV SHOW CLUSTERING.csv

## Variables Description
__________________________________________________
The variable description of the Netflix Movies and TV Shows Clustering Dataset is as follows:
1. **show_id**: Unique identifier for each movie/show.
2. 2. **type**: Indicates whether the entry is a movie or a TV show.
3. **title**: Name of the movie or TV show.
4. **director**: Name of the director(s) of the movie or TV show.
5. **cast**: Names of the actors and actresses featured in the movie or TV show.
6. **country**: Country or countries where the movie or TV show was produced.
7. **date_added**: Date when the movie or TV show was added to Netflix.
8. **release_year**: Year when the movie or TV show was released.
9. **rating**: TV rating or movie rating of the movie or TV show.
10. **duration**: Length of the movie or TV show in minutes or seasons.
11. **listed_in**: Categories or genres of the movie or TV show.
12. **description**: Brief synopsis or summary of the movie or TV show.

## Project Structure
________________________________________________________
├── README.md

├── Dataset 

├── NETFLIX MOVIES AND TV SHOWS CLUSTERING.csv

├── EDA

│    ├── Numeric & Categoric features

│          ├── Univariate Analysis

│          ├── Bivariate Analysis

│          ├── Multivariate Analysis

├── Data Cleaning

│       ├── Duplicated values

│       ├── NaN/Missing values

│       ├── Treating Skewness

│       ├── Treating Outlier 

│
├── Textual Data Preprocessing

│         ├── Clustering Attributes

|         ├── Removing Stopwords

|         ├── Lowercasing words

|         ├── Removing Punctuation

|         ├── Stemming

│         ├── Snowball Stemmer

|         ├── Word Vectorization

|         ├── TF-IDF (Term Frequency - Inverse Document Frequency)
 
├── Dimenssionality Reduction
 
|         ├── PCA (Principle Component Analysis)

│
├── Model Building

|         ├── Clustering Implemention

|         ├── K-Means Clustering

|         ├── Elbow Method

|         ├── Silhoutte Score Analysis

|         ├── Agglomerative Hierarchical Clustering

|              ├── Dendogram

├── Content Based Recommendation System

│   
├── Report

├── Presentation

├── Result

└── Reference


## Conclusion
___________________________________________________
