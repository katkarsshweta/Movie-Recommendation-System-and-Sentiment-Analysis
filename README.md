# Movie Recommendation System and Sentiment Analysis


### PROBLEM STATEMENT

The objective of this work is to use Machine Learning Algorithms to give users movie reccomendations and a garphical analysis of movie performance based on the feedbacks from the users. The system automatically predicts the sentiment of the feedback that helps in analysing the movies.

### INTRODUCTION

The movie industry has always been a popular source of entertainment for people around the world. With the advent of technology, movie streaming services and online movie databases 
have become more prevalent. However, with so many movies to choose from, it can be overwhelming for users to decide what to watch next. Our website aims to address this issue by providing movie recommendations to users based on their input. Additionally, the website asks users to provide a review for the recommended movies, which are then classified as positive or negative. This information is used to generate a chart that shows how many people liked the movie and how many did not. This allows users to make more informed decisions about what movies to watch next.

#### Dataset Information :

1. Data collection: Collect movie data such as title, genre, cast, crew, and ratings from datasets.
2. Data preprocessing: Clean and preprocess the data to remove duplicates, missing value and irrelevant information.
3. Feature engineering: Extract meaningful features such as genre, cast, director, and ratio from the movie data.
4. Algorithm selection: Choose a suitable algorithm for building the recommendation system, such as collaborative filtering content-based filtering, or hybrid filtering.

Movie recommendation system: 

https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset

Movie Review Sentiment Analysis:

https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

AIM: 
The objective of this is to use Machine Learning to give movie reccomendations and 
predict whether the review given by the user is positive or negative.

### MOVIE RECOMMENDER
Here are the steps involved in creating a movie recommendation system:
1. Data collection: Collect movie data such as title, genre, cast, crew, and ratings from datasets.
2. Data preprocessing: Clean and preprocess the data to remove duplicates, missing value and irrelevant information.
3. Feature engineering: Extract meaningful features such as genre, cast, director, and ratio from the movie data.
4. Algorithm selection: Choose a suitable algorithm for building the recommendation system, such as collaborative filtering, content-based filtering, or hybrid filtering.

### Data Cleaning
#### Stemming Words

Stemming is the process of reducing a word to its base or root form. The most common algorithm used for stemming is the Porter stemming algorithm. It removes the suffix from a word to produce the base form of the word, also known as the stem.For example, the word "running" can be stemmed to "run", "jogging" can be stemmed to "jog", and "swimming" can be stemmed to "swim". The idea behind stemming is to reduce the number of unique words in a dataset, 
making it easier to analyze and process the data.

#### Removing Stop Words
Stop words are words that do not carry any meaning on their own. Words in english such as - 'the', 'is', 'they, 'he' etc. do not really contribute to our review analysis and hence are removed. We can remove these stop words from the text in a given corpus to clean up the data, and identify words that are more rare and potentially more relevant to what we’re interested in.

### MOVIE REVIEW SENTIMENT ANALYSIS

Here are the steps involved in performing movie review sentiment analysis:
1. Data collection: Collect movie reviews from various datasets.
2. Data preprocessing: Clean and preprocess the data to remove stop words, punctuation, and special characters.
3. Feature extraction: Extract relevant features such as the frequency of words, word embeddings, or n-grams. 
4. Algorithm selection: Choose a suitable algorithm for performing sentiment analysis, such as Naive Bayes,Support Vector Machines.
5. Training and testing: Train the model on a dataset of labelled movie reviews and test its performance on a subset of the data.

#### Vectorizing
CountVectorizer is a preprocessing step used in natural language 
processing (NLP) that converts a collection of text documents to a 
matrix of token counts. It is a process of converting text data into a matrix of token counts. In other words, it is used to transform a given text into a vector on the basis of the frequency (count) of each word that occurs in the entire text.

##### Comparing accuracies of three Naive Bayes Models
1. Guasssian NB
2. Mulinomial NB
3. Bernaulli NB

### CONCLUSION
In  conclusion,  a  movie  recommendation  system  and  movie  review  sentiment  analysis can  greatly  benefit  a  movie  streaming  platform  by  providing  personalized  movie 
recommendations  to  users  and  analyzing  their  feedback.
The  recommendation  system  can  be  built  using  machine  learning  algorithms  to  analyze user  data  and  generate  personalized  movie  suggestions  based  on  their  viewing  history, ratings,  and  preferences.  Additionally,  the  sentiment  analysis  of  movie  reviews  can  help the  platform  understand  user  feedback  and  improve  their  movie  recommendations further.
Deploying  the  recommendation  system  and  sentiment  analysis  as  a  web  application  or API  will  provide  a  seamless  user  experience,  and  evaluating  the  performance  of  the system  using  metrics  such  as  precision,  recall,  and  F1  score  will  ensure  that  the platform  is  meeting  its  objectives.  By  implementing  these  techniques,  the  platform  can 
increase  user  engagement,  customer  satisfaction,  and  ultimately  drive  business  growth.

### REFERENCES:
1)    Kaggle
2)    Google
3)    YouTube
