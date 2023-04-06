# CodeClause_Fake-News-Detection
Fake news is false information and hoaxes spread through social media and other online media to achieve a political agenda.

In this project, we have used various machine learning algorithms to classify fake news articles using sci-kit libraries from python.

Data set used:

the data set contains :

column 1: id

column 2: title

column 3: text

column 4: label

The dataset used for this project were in csv format named news.csv.

File Description:

news.csv:

This file contains all the pre processing functions needed to process all input documents and texts. First we read the train, test and validation data files then performed some pre processing like tokenizing, stemming etc. There are some exploratory data analysis is performed like response variable distribution and data quality checks like null or missing values etc.The news folder is compressed so that it can be uploaded in the github.


jupyter source file:

Here we have build all the classifiers for predicting the fake news detection. The extracted features are fed into different classifiers. We have used PassiveAggressiveClassifier from sklearn. Each of the extracted features were used in all of the classifiers. Once fitting the model, we compared the f1 score and checked the confusion matrix. Selected model was used for fake news detection with the probability of truth. In Addition to this, We have also extracted the top 50 features from our term-frequency tfidf vectorizer to see what words are most and important in each of the classes.
As we can see that our best performing model had an f1 score in the range of 80's. This is due to less number of data that we have used for training purposes and simplicity of our models.
