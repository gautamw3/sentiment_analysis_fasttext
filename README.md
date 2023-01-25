# Sentiment Analysis using facebook's popular "fasttext" library

The data set used here is a collection of 40,000 tweets tagged with 13 different sentiments which I got from Kaggle.
The brief data summary are as:

      neutral       8638
      worry         8459
      happiness     5209
      sadness       5165
      love          3842
      surprise      2187
      fun           1776
      relief        1526
      hate          1323
      empty          827
      enthusiasm     759
      boredom        179
      anger          110
      
The attached notebook file reads the data from the .csv file, apply some preprocessing, perform training and testing and finally predicts the sentiment if an appropriate input in the form of a sentence(s) is provided to the classifier.
