### Project Name:
#### Predictive Analysis of Online News Article Share Volume

![Shareability.](https://github.com/winni50927/postpopularity_ml_prediction/blob/main/social-media-shareability.png)

### Introduction
In the rapidly evolving landscape of digital journalism, the measure of an article's shareability
has emerged as a pivotal metric for publishers. Understanding the determinants of online news
article vitality and shareability has thus become imperative. This project is driven by the pressing
need to delve into the underlying factors influencing the share volume of online news articles.
The primary objective of this study is to construct a predictive model capable of anticipating the
share volume of articles based on a myriad of features including content attributes, article length,
and publication timing. In pursuit of this objective, the following research questions will be
addressed:
1. What specific attributes of online news articles exhibit the strongest predictive power for
achieving high share volumes?
2. To what extent does the timing of article publication influence its shareability?
3. Can machine learning algorithms effectively forecast the share volume of an article prior to its
publication?
By rigorously examining these questions, this research aims to contribute valuable insights into
the dynamics of online news article shareability, thereby aiding publishers in optimizing their
content strategies and enhancing audience engagement.

### Result and Futurework
In this project, I leveraged a comprehensive set of skills encompassing data preprocessing, model
selection, evaluation, and fine-tuning to develop a reliable machine learning model aimed at
predicting the shareability of posts. For model selection, I utilized a variety of algorithms known
for their robust performance in classification tasks, including Random Forest, AdaBoost, SVM
with an RBF kernel, K-Nearest Neighbors, and Naive Bayes.

The analysis revealed that the Random Forest model outperformed others in terms of prediction
accuracy. Key findings also indicated that the popularity of keywords in the articles and their
relevance to the media platform's trending topics significantly influenced shareability.
One of the most time-consuming aspects was comprehending the significance of each data
column and executing data preprocessing. Specifically, the logarithmic transformation applied to
independent variables presented challenges in addressing data skewness, requiring extensive
testing to determine the most effective method.

Looking ahead, I plan to incorporate SHAP values to further evaluate the impact of the features
used by the machine learning models. This will enable a clearer understanding of how each
feature contributes to the model’s predictions, highlighting both their positive and negative
influences on the outcome.
