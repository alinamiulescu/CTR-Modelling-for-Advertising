# Click Rate Modelling (CTR Modelling)

Avazu is a global mobile advertising platform. It links advertisers and publishers. CTR modelling is one of its main unique selling points to attract customers (both advertisers and publishers). In its search for a new CTR prediction model, Avazu has provided a free for use CTR dataset for a Kaggle competition, https://www.kaggle.com/c/avazu-ctr-prediction hosts the train dataset (the “train.gz”, not the smaller “test.gz”). 

This dataset contains approximately 40 million impressions over a 10 day period. Each impression has a click/no-click indicator and a number attributes (such as website and time). The objectiveof is to predict whether an impression will turn into a click or not, by appling both the Naïve Bayes model and Logistic Regression with parameters estimated with Stochastic Gradient Descent.
