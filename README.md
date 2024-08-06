The model is able to classify corpus into 16 different languages over a precision of 0.978 and an accuracy of 0.980.
The algorithm used for the model is Gaussian Naive Bayes Classifier. The dataset contained 10337 records and data preprocessing was performed using the NLTK library.
The dataset was first word tokenized, then converted to lowercase.  Then each word was stemmed.
The resulting corpus was then tfidf vectorized and then model training was done. The project is currently done, but I plan to deploy the model in future.
