<B><I>Sentiment Analysis</I></B> refers to identifying as well as classifying the sentiments that are expressed in the text source. Tweets are often useful in generating a vast amount of sentiment data upon analysis. These data are useful in understanding the opinion of the people about a variety of topics.

In this project, we analyze a dataset of twitter tweets and try to classify the tweets into two categories- tweets showing signs of depression and all other tweets. The dataset is taken from kaggle (https://www.kaggle.com/datasets/gargmanas/sentimental-analysis-for-tweets).

<B>Features of the dataset:</B>
1. Original Shape: (10314, 3)
2. The dataset contains index, the tweets and a label associated with each tweet. The label is either 1(depression) or 0(not depression)

Since it has twitter tweets, the tweets may contain usernames, links and other undesirable characteristics. Hence we will clean and preprocess the dataset.
