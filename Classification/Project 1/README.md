# Sentiment-analysis-of-amazon-products

It is a logistic regression to classify positive reviews from negative reviews.

Libaries used: numpy, pandas, matplotlib.pyplot, sklearn.linear_model, sklearn.feature_extraction.text, string, json, math

Tools used: Jupyter Notebook

I have trained 2 different models.

* model 1: feature vector is a word vector of all possible word in the reviews of training data
* model 2: In this word vector is of selected words such as love, great, waste, return etc.

I have compared the accuracy of both models with the accuracy of majority class prediction model.

Result: model 2 is equivalent to majority class prediction model i.e. it is underfit. With model 1 accuracy improved significantly.

[Other Machine Learning Projects](https://github.com/gov-vj/Machine-Learning-Projects)