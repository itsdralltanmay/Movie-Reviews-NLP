
# Movie Reviews analysis in NLTK

In this project, we have used the movie reviews dataset present in NLTK to make a classifier which can predict if the given review is Positive or Negative.

We created a list of tuples containing the words from review and their categories.

Then we created a collection of Stopwords and Punctuations to get the clean data.

Afterwards, we spilt the data for Training (75%) and Testing (25%).

We used Naive Bayes classifier to train the model, and got 80% accuracy.

Later, we got the list of most informative features which tells the influence of each word in the final result.