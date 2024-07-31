# Automatic Review Analyzer

Implemented and compared three types of linear classifiers to use for sentiment analysis of Amazon product reviews.

The goal of this project is to design a classifier to use for sentiment analysis of product reviews. The training set consists of reviews written by Amazon customers for various food products. The reviews, originally given on a 5 point scale, have been adjusted to a +1 or -1 scale, representing a positive or negative review, respectively.

Below are two example entries from the dataset. Each entry consists of the review and its label. The two reviews were written by different customers describing their experience with a sugar-free candy.

| Review	| label|
|-------|-------|
|Nasty No flavor. The candy is just red, No flavor. Just plan and chewy. I would never buy them again|	−1|
|YUMMY! You would never guess that they're sugar-free and it's so great that you can eat them pretty much guilt free! i was so impressed that i've ordered some for myself (w dark chocolate) to take to the office. These are just EXCELLENT!	|1

In order to automatically analyze reviews, I did the following tasks:

Considered three classifiers: the perceptron algorithm, the average perceptron algorithm, and the Pegasos algorithm.
Use these classifiers on the food review dataset, using some simple text features.
Experiment with additional features and explore their impact on classifier performance.
Setup Details:
For this project, I used Python 3.6 with some additional libraries. 
