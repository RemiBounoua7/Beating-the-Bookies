# Beating the bookies : a step further


In 2017, KAUNITZ Lisandro, ZHONG Shenjun and KREINER Javier published an article called "Beating the bookies with their own numbers-and how the online sports betting market is rigged" link: https://arxiv.org/pdf/1710.02824.pdf

In this article, they describe how online bookmakers have exceptionnal models to predict games outcomes before they are played, and that they use these models to select the odds they will provide to the public to bet on.
Their theory was that we, as sports gamblers, could take advantage of that, and the fact that different companies have different models, to find outliers in odd distribution and bet on those. I'll let you read the paper if you want more details.

So, in this notebook, we will try to go a step further. Their method is based on the closing odds given right before a game starts. But what if we could predict which games will have outliers in their odds distribution before the odds are even dealt ? What if we could accurately predict which game to bet on based on previous ones ?

Let's find out !
