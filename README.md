# Supervised Learning with scikit-learn to Predict User Rating on Anime

# Overview
This is the final project of the course MSDS 699 Machine learning laboratory.

Using the machine learning library scikit learn and supervised learning, this project’ll predict a user’s rating on a new anime based on the previous rating or and the features of the anime such as genre, number of episodes, and how popular or well-known this anime is. One promising business application of this model is to make it part of the recommendation engine. By recommending more anime that this user is truly interested in, we are able to increase the engagement and loyalty of the anime streaming website. 

# Data Source
Anime Recommendations Database (https://www.kaggle.com/CooperUnion/anime-recommendations-database)

# Algorithms Used
### 1.Multiclass Classification Approach:
1. Logistics Regression
2. Random Forest Classfier
3. Extra Tree Classifier
### 2.Ordinal Regression Approach (https://pythonhosted.org/mord/)

# Findings
The accuracy scores for these two models are very low. It suggests that the features and the target is likely not to strongly correlate with each other given the randomness and nuance of user behavior. So I think in order to build a recommendation system that really captures the user behavior and user preferences, more data should be collected, a more granular and contextual analysis should be done. In addition, other kinds of machine learning algorithms can be considered, like unsupervised learning, KNN clustering across data from multiple users, and assigning users to segments where they share similar patterns and preferences.


