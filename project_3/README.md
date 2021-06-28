# Project 3: Web APIs & Classification

### Problem Statement

Natural Language Processing (NLP) is a hyponym of computer science and artificial intelligence that focus on the interactions between computers and natural human languages like English, for example. Ultimately the purpose of NLP is to read, understand and decipher human languages in a way that it is valuable.

In this project, we will be using NLP to distinguish posts from two subreddit posts i.e. r/datascience and r/SoftwareEngineering. To solve this binary classfication problem will also be looking at mulitple supervised machine learning models to help us distinguish our posts. However, with numerous machine learning models, how do we decide which model is the best to help us in our task?

Problem Statement: Which classfication model can best distinguish which subreddit a post belongs to?

We will be looking at various evaluation metrics for classifications models, such as the train and test accuracy scores, precision and recall scores, f1-score, and the ROC AUC score to evaluate the performances of our models and both the train and test data and pick the best model that caters to our task.

This project will be split into two notebooks:

Part 1 - Data Scraping, Cleaning and EDA

Part 2 - Modelling and Evaluation

---

### Conclusion and Recommendations

In summary, we have made effective use of Natural Language Processing to distinguish posts between subreddits through multiple machine learning models. From our model training we found two models:  Multinomial Naive Bayes with TFIDF Vectorizer and Support Vector Classifier with TFIDF Vectorizer to achieve the highest test accuracy scores. Using classification evaluation metrics, such as Confusion Matrix, ROC-AUC Curve and Feature Importance, we have identified Multinomial Naive Bayes with the TFIDF Vectorizer to be the best model.

However, this was build upon certain limitations. As we were required to use Reddit's API for this project, we are restricted to retrieving 25 posts each time and hence 1000 posts a day. This hinders the amount of data we can collect and hence implement on our models. This is why we see multiple models showing signs of overfitting with higher training scores then testing scores. This can be combated with a larger amount of data compared to what we have presently.

Additionally, there were a limited number of models used for our investigation. This investigation can be enhanced by tapping into other Vectorizers such as Hashing Vectorizer as well as other hyperparameter optimisation techniques such as RandomisedCV. We can also look at boosting and bagging models to enhance our model performance further.

Another way to approach this problem is looking into sentiment analysis and seeing if we can classify our posts better using postive and negative posts.


This research can be beneficial to stakeholders who are interested in the 'data science' and 'software engineering' themes to look at what users are interested in these days and the type of content they engage in or reach out for in these subreddits. Feature importance, as identified earlier, can aid these stakeholders in understanding the kind of content users engage in the respective subreddits.

---

