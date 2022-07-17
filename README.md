# Tech vs Entertainment: Predicting News Articles

This was a group project I did in my university course, where I compare different machine learning techniques to predict the class of a news article, out of two possible classes. The algorithms used were *Logistic Regression, Naive Bayes, SVM and Neural Network.*

More details on implementation/findings/thought-processes are in the .ipynb file.

# Dataset
The datasets consists of 534 BBC news articles on either tech or entertainment news. The two csv files "test.csv" and "train.csv" have three columns each:
- ArticleID, a unique identifier
- Text, the words present in the article separated by a space
- Category, class of the article (tech or entertainment)

There are 5 main sections:
- Data exploration: analysed the data we have, using graphs to better understand the distributions of the two classes, and the frequency of most used words in the articles
- Training our models: implemented the 4 algorithms with considerations of specific tuning parameters, obtaining different testing and training accuracies
- Classification Quality Evaluation: experimented on different training set sizes, see how the accuracy is affect. Differences were measured using F1 score.
- 5-fold Cross-Validation: assess model performance when key hyperparameters are changed
- Final Conclusions
