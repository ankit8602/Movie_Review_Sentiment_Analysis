# Movie Review Sentiment Analysis
## Objective 
Sentiment analysis on a set of movie reviews given by reviewers and try to understand what was the overall reaction of reviewers i.e. whether it is positive or negative.

## About Dataset
The dataset contains 2000 rows and 2 columns 'Review' and 'Sentiment' and there are only two classes 'pos'(i.e. positive) and 'neg'(i.e. negative). The frequency of each class is 1000.

## Steps involved in sentiment analysis
1. Data Preprocessing
2. TF-IDF Vectorization
3. Multinomial Naive Bayes classification model

## Classification Report
|    |precision | recall | f1-score | support|
| --- | --- | ---| --- | --- |

| 0   |   0.85 |     0.79  |    0.82      | 201 |
| 1   |    0.80 |     0.86   |   0.83    |   199 |

|accuracy |     |    |   0.82   |    400|
| macro avg  |     0.82 |     0.82  |    0.82    |   400 |
|weighted avg |       0.82  |    0.82  |    0.82  |     400 |
