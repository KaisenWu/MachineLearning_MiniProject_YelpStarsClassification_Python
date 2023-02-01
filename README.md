# MachineLearning_MiniProject_YelpStarsClassification_Python

Project Overview:
This NLP project attempts to classify Yelp Reviews into 1 star or 5 star categories based off the text content in the reviews.  

About The Dataset:
The dataset is from Kaggle, url: https://www.kaggle.com/c/yelp-recsys-2013. Each observation in this dataset is a review of a particular business by a particular user.
Features explaination:
  1. The "stars" column is the number of stars (1 through 5) assigned by the reviewer to the business. (Higher stars is better.) In other words, it is the rating of        the business by the person who wrote the review.
  2. The "cool" column is the number of "cool" votes this review received from other Yelp users.
  3. All reviews start with 0 "cool" votes, and there is no limit to how many "cool" votes a review can receive. In other words, it is a rating of the review itself,        not a rating of the business.
  4. The "useful" and "funny" columns are similar to the "cool" column.
  
 Main techs used:
  1. Seaborn data visualization.
  2. Text vectorizarion.
  3. Term frequency and inverse document frequency (TF-IDF) analyze.
  4. Pipeline implementation.
