# Topic-Modeling-Unsupervised-Learning-Project
Topic Modeling Unsupervised Learning Project

The goal of this project is to apply topic modeling to Amazon reviews of Nautica products to accurately categorize and analyze customer feedback. By identifying key themes and sentiments, we aim to uncover valuable marketing and product insights that can drive strategic decisions.

In a market saturated with a myriad of brands, materials, and colors, understanding customer preferences and pain points is crucial. Topic modeling helps in identifying specific attributes that customers appreciate or dislike, providing actionable insights that can enhance product development and marketing strategies.

This analysis is particularly important for differentiating Nautica products in a competitive landscape. Being able to highlight unique selling points and address common issues can significantly impact brand positioning and customer satisfaction. In an industry where standing out is essential for survival, leveraging these insights can provide Nautica with a critical advantage, leading to more informed business decisions and improved product offerings.

Topic modeling is an unsupervised machine learning technique within the field of Natural Language Processing (NLP). It involves employing a range of statistical and deep learning methods to uncover hidden semantic structures in collections of documents. The challenge lies in automatically extracting meaningful insights from these data sources without prior knowledge, a complex problem in unsupervised learning.

Given the intricacies involved, significant effort is required to experiment with various approaches until an effective model is found that generates relevant topic models from reviews. To address this, we will develop two topic modeling approaches:

Latent Dirichlet Allocation (LDA): A traditional and widely-used method for many years, LDA has established itself as a cornerstone in topic modeling. It works by assuming that each document is a mixture of topics and each topic is a mixture of words.

BERTopic: A more recent and advanced approach, BERTopic overcomes several limitations of traditional methods, such as the need to specify the number of topics in advance. It utilizes semantic embeddings and clustering techniques to automatically determine the optimal number of topics and produce more coherent and contextually meaningful results.

By comparing these methods, we aim to identify which approach best captures the underlying themes in the reviews and provides the most valuable insights.


You can download the datasets from here: https://www.kaggle.com/datasets/brittoh/amazon-product-data
Or you can download from the original site: https://jmcauley.ucsd.edu/data/amazon/index_2014.html. The site asks to fill out form, and then, they send an email with the datasets.

The project includes two files: a Jupyter notebook and a requirements file. I used Python 3.10.14, and I recommend installing the packages listed in the requirements file to avoid version-related issues.

