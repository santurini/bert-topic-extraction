# NLP with Python: Topic Modeling with BERT
In the following project it was attempted to extract the topics regarding the dataset of [Amazon Book's reviews](https://www.kaggle.com/datasets/mohamedbakhet/amazon-books-reviews). The main challenges were to handle correctly the large amount of data in order to apply a feasible pipeline.

## Baseline Methods

As a baseline methods were used mini-batch K-means and SVD and additionally also K-Means applied on the SVD dimensionality reduction of the TF-IDF matrix.
Here are the results obtained after the topic reduction:

![baseline](https://user-images.githubusercontent.com/91251307/212086606-7ceec068-a97c-4c22-aca9-dccaeb912f78.png)

## Sentence Transformers

For this part instead of the TF-IDF matrix were used Sentence Transformers
