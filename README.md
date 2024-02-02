# SMS-Classification-Project

This is a **Python** project for classifying SMS messages as spam or non-spam. The project use a vectorization techniques name TF-IDF Vectorizer.

## Dataset
The dataset can be obtained from my repo, which contains a collection of SMS with labels indicating whether they are spam or not spam represented by ham.

## Methodology
Firstly, the raw text messages were preprocessed. The preprocessing involved removing punctuation, stop words, and converting all text to lowercase. The goal of this step was to transform the raw text messages into a format that can be used for machine learning. The preprocessed text messages were then transformed into numerical feature vectors using vectorization techniques: TF-IDF Vectorizer. This technique is used to convert the text data into a format that can be used by machine learning algorithms. Gaussian Navie Bayes, Bernoulli Navie Bayes, Multinomial Navie Bayes classifier were chosen as the models and we check which one is good for the SMS spam classification task. This Bernoulli Navie Bayes Model was selected because it is a simple and effective algorithm for classification tasks. The models were trained and evaluated using the accuracy metric on both the training and test sets.

Finally, the performance of the models was compared based on their accuracy on the training and test sets. Based on the results, it was concluded that the TF-IDF Vectorizer with Bernoulli Navie Bayes classifier is more reliable and accurate in predicting the outcome of the given dataset.

## Results
The results show that the TF-IDF vectorizer with Bernoulli Navie Bayes classifier outperforms the other models. The Bernoulli Navive Bayes model achieved an accuracy of **0.988394584139265** and the precision score is **1.0**, compared to an accuracy of **0.9748549323017408** and precision score of **1.0** of Multinomial Navie Bayes and accuracy of **0.8781431334622823** and precision score of **0.5267857142857143** of Gaussian Navie Bayes achieved by the TF-IDF Vectorizer.

## Conclusions
Based on the results, it can be concluded that using TF-IDF with Bernoulli Navive Bayes classifier is more reliable and accurate in predicting the outcome of the given dataset. This project can be extended further by exploring other vectorization techniques and machine learning algorithms.

## Dependencies

+ matplotlib
+ scikit-learn
+ pandas
+ seaborn
+ nltk
+ numpy
+ string
+ wordcloud
+ collections
+ pickle
+ streamlit
