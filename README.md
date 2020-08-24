# Predicting-Subreddit-Based-On-The-Titles

# ![](pictures/pic.jpg)Project3: What is the best model to use for predicting subreddits.

### Two subreddits:
The two subreddits I chose for this project are:
Relationships subreddit:<br>
The relationships subreddit is a platform for people to post their relationship issues and ask people for advice.
JUSTNOMIL subreddit: <br>
Justnomil is a similar subreddit but specifically for issues regarding people’s difficult mother in laws.

##### model 1 (pipeline model using TfidfVectorizer with MultinomialNB):
Accuracy: 0.888
Specificity: 0.928
Sensitivity: 0.848
AUC: 0.96

##### model 2 (pipeline model using CountVectorizer with Logistic Regression):
I used gridsearch to find out the best logistic regression is with Ridge
The best model
Accuracy: 0.904
Specificity: 0.892
Sensitivity: 0.916
AUC: 0.97

##### model 3: (pipeline model using CountVectorizer with RandomForest):
Accuracy: 0.9
Specificity: 0.88
Sensitivity: 0.912
AUC: 0.97

##### model 4: (pipeline model using CountVectorizer with Bagging Classifier):
Specificity: 0.884
Sensitivity: 0.916
AUC: 0.96
