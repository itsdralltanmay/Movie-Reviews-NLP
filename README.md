
# Movie Reviews analysis in NLTK

In this project, we have used the movie reviews dataset present in NLTK to make a classifier which can predict if the given review is Positive or Negative.

We created a list of tuples containing the words from review and their categories.

Then we created a collection of Stopwords and Punctuations to get the clean data.

Afterwards, we spilt the data for Training (75%) and Testing (25%).

We used Naive Bayes classifier to train the model, and got 80% accuracy.

We got the list of most informative features which tells the influence of each word in the final result.

Then we used the SVC and got 76% accuracy.

So far, the train-test data was manually split, now we used the CountVectorizer for better feature selection and applying SVC again generated 83% accuracy.
