# SMS-Classification-Project

SMS Spam Classification
This is a machine learning project for classifying SMS messages as spam or non-spam. The project uses two different vectorization techniques: CountVectorizer and TF-IDF Vectorizer, and compares their performance using K-Nearest Neighbors (KNN) classifier.

Dataset
The dataset can be obtained from here, which contains a collection of SMS with labels indicating whether they are spam or not spam.

Methodology
Firstly, the raw text messages were preprocessed. The preprocessing involved removing punctuation, stop words, and converting all text to lowercase. The goal of this step was to transform the raw text messages into a format that can be used for machine learning. The preprocessed text messages were then transformed into numerical feature vectors using two different vectorization techniques: CountVectorizer and TF-IDF Vectorizer. These techniques were used to convert the text data into a format that can be used by machine learning algorithms. K-Nearest Neighbors (KNN) classifier was chosen as the model for the SMS spam classification task. This model was selected because it is a simple and effective algorithm for classification tasks. The models were trained and evaluated using the accuracy metric on both the training and test sets.

Finally, the performance of the models was compared based on their accuracy on the training and test sets. The CountVectorizer with KNN classifier outperformed the TF-IDF Vectorizer with KNN classifier in terms of accuracy. The CountVectorizer with KNN model achieved an accuracy of 0.973 on the training set and 0.968 on the test set, compared to an accuracy of 0.920 on the training set and 0.916 on the test set achieved by the TF-IDF Vectorizer with KNN. Based on the results, it was concluded that the CountVectorizer with KNN classifier is more reliable and accurate in predicting the outcome of the given dataset.

Results
The results show that the CountVectorizer with KNN classifier outperforms the TF-IDF Vectorizer with KNN classifier. The model achieved an accuracy of 0.973 on the training set and 0.968 on the test set, compared to an accuracy of 0.920 on the training set and 0.916 on the test set achieved by the TF-IDF Vectorizer with KNN.

Conclusions
Based on the results, it can be concluded that using CountVectorizer with KNN classifier is more reliable and accurate in predicting the outcome of the given dataset. This project can be extended further by exploring other vectorization techniques and machine learning algorithms.

Dependencies
matplotlib
scikit-learn
pandas
seaborn
