## Sentiment Analysis of Bangla News Comments Using Machine Learning: Project Overview
- Developed a machine learning model that can classify the sentimental category (**`positive, negative and neutral`**) of a news comment written in Bangla Text.
- For the implementation a publicly available [dataset](https://data.mendeley.com/datasets/n53xt69gnf/3) of **`12k`** news comments have been used. 
- To create the system TF-idf feature extraction technique with n-gram features have been used.
- Analysed the performance of different machine learning algorithms for n-gram feature by using various evaluation metrics such as **`accuracy, precision, recall and f1-score`**.


## Dataset Distribution
The dataset consists of `12K` news comments of five sentiment categories. For the ease of implementation converted this five categories into 3 categories. 


![data_dist](/images/data_distribution.PNG)

**Dataset Summary-** includes total number of words and unique words in each class.

![data_dist](/images/data_summary.PNG)

## Model Evaluation
Differnet Machine learning classifers are taken to train and evaluate the system efficacy. The experiment is done for N-gram features and measuers the performance using various evaluation metrics.

**`Performance on Unigram feature:`**

![unigram](/images/unigram_performance.PNG)

**`Performance on Bigram feature:`**

![bigram](/images/bigram_performance.PNG)

**`Performance on Tri-gram feature:`**

![trigram](/images/trigram_performance.PNG)

**From the above analysis, it is observed that for trigram feature `Multinomial Naive Bayes` shows good performance in all evaluation metrices.**

**`Accuracy and F1-score Plot:`**

![plot](/images/comparison_plot.PNG)


## References:
1. [Dataset Link](https://data.mendeley.com/datasets/n53xt69gnf/3)

## Resources Used
- **Python Version:** 3.7
- **Packages:** Scikit Learn, Numpy, Pandas, Matplotlib, Seaborn 
