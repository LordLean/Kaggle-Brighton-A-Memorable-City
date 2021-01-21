# Kaggle-Brighton-A-Memorable-City

**Kaggle competition** - [Brighton, a Memorable City!](https://www.kaggle.com/c/brighton-a-memorable-city)

Memorable vs. not memorable binary classification task. Provided is:
* 247 labelled training data (209 of memorable scenes and 38 of not memorable scenes)
* 2219 labelled incomplete training data - sporadically missing feature values.
* 11874 of test data, which are not labelled.
* Confidence label for all training data.
* Proportion of positive/negative data points in the test set.

Each data instance is represented as a 4608 dimensional feature vector. This vector is a concatenation of 4096 dimensional deep Convolutional Neural Networks (CNNs) features extracted from the fc7 activation layer of CaffeNet and 512 dimensional GIST features.

This was an inclass competition for undergrad module G6061 and postgraduate module 934G5 for the University of Sussex. Final leaderboard score: 24/387.

Training data was collected in brighton whereas test data was collected in London.
![](https://raw.githubusercontent.com/LordLean/Kaggle-Brighton-A-Memorable-City/main/Images/domain-adaptation.png)
