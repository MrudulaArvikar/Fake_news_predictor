# Fake_news_predictor
**Project Overview**
This project aims to classify news articles as real or fake using Machine Learning and Natural Language Processing (NLP) techniques. The model utilizes a Logistic Regression classifier, and the text data is processed using TF-IDF vectorization and stemming. This predictor can help in identifying misinformation and enhancing the reliability of news sources.

**Dataset**
The dataset consists of news articles with the following columns:

Dataset
The dataset consists of news articles with the following columns:

Column	Description
id	Unique ID for a news article
title	Title of the news article
author	Author of the news article
text	Text of the article (may be incomplete)
label	Label indicating whether the news article is real or fake: <br> 1: Fake news <br> 0: Real news


Dependencies

The following Python libraries are required for this project:

numpy
pandas
re
nltk
sklearn
matplotlib
seaborn

You can install the required libraries using pip:

pip install numpy pandas nltk scikit-learn matplotlib seaborn

import nltk
nltk.download('stopwords')
Run the Script

Execute the script to preprocess the data, train the model, and evaluate its performance.

**Results:**
Accuracy Score: Shows the percentage of correctly classified articles.
Confusion Matrix: Visual representation of true vs. predicted labels.
Classification Report: Includes precision, recall, and F1-score metrics.
.
**License**
This project is licensed under the Apache License 2.0. See the LICENSE file for more details.

