# IntroToML FinalProj - Misinformation Classifiers

Benjamin Ayala & Ryan Coops

In this notebook we will take a look at a couple different classifiers, their capability of disseminating real from fake news information, and how the vectorization vs. transformation of our data will change them. Starting with 3 distinct datasets, essentially 2 of them, with one of them being split into Fake & True individual sets, we will go about sanatizing the text, vectorizing/transforming, and running all the data through our classifiers.

To start our (WELFake) is a dataset of 72,134 news articles with 35,028 real and 37,106 fake news. For this, authors merged four popular news datasets (i.e. Kaggle, McIntire, Reuters, BuzzFeed Political) to prevent over-fitting of classifiers and to provide more text data for better ML training.

Published in: IEEE Transactions on Computational Social Systems: pp. 1-13 (doi: 10.1109/TCSS.2021.3068519).

Our secondary dataset is from Kaggle, and the associated project can be found here (https://www.kaggle.com/code/therealsampat/fake-news-detection). This latter set is not nearly as rigorously defined as the WELFake dataset and so further research would include validation of all data before any form of classification. For the purposes of this class and final project, we will take it on good faith that the set is well labeled
