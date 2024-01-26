# Turkish Sentiment Analysis - Hotel and Movie Reviews
Turkish Sentiment Analysis for Hotel&amp;Movie Review Datasets

Today, comments can be made on many topics on web platforms with the development of the internet. Analyzing the data of these comments is essential for companies and data
scientists. There are many methods for analyzing data. Recently, language models have also been used in many studies for sentiment analysis (SA) or text classification. 
In this study, Turkish sentiment analysis is performed using language models on hotel and movie review datasets. The language models are chosen because they are rarely 
used in Turkish literature. The pre-trained BERT, ALBERT, ELECTRA, DistilBERT models for the Turkish language are trained and tested with these datasets. In addition, a 
text filtering method (TFM), which removes the words that can provide the opposition sentiment in the positive or negative labelled text, is proposed for sentiment analysis 
(With the TFM method, the top "k" (5, 10, 15) most frequently words, which can express opposition or neutrality, in positive-negative labeled texts for SA are detected. 
Then, these words are removed from other labeled texts.). These datasets obtained by this method are also retrained with language models and the accuracy values of their 
models are measured. The results of this study are compared with previous studies using the same datasets. As a result of the analysis, the accuracy values obtain 
state-of-art results with language models compared to previous studies. The best performance has been achieved by training the ELECTRA language model using the proposed 
TFM. All models were uploaded in https://huggingface.co/anilguven

Turkish Sentiment Analysis Result for Language Models:
![image](https://user-images.githubusercontent.com/17703776/208764199-1f1f2685-567c-45fa-a775-1df4da2b2934.png)

Comparison language models with previous machine learning studies:
![fig_7_chart](https://user-images.githubusercontent.com/17703776/208764385-e3e7c7ca-0a21-4b6b-b931-3a1c3c9b6c41.png)

!!! Please citation this paper: 
```
@article{10.1145/3557892,
author = {Guven, Zekeriya Anil},
title = {The Comparison of Language Models with a Novel Text Filtering Approach for Turkish Sentiment Analysis},
year = {2022},
issue_date = {February 2023},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
volume = {22},
number = {2},
issn = {2375-4699},
url = {https://doi.org/10.1145/3557892},
doi = {10.1145/3557892},
abstract = {Today, comments can be made on many topics on web platforms with the development of the internet. Analyzing the data of these comments is essential for companies and data scientists. There are many methods for analyzing data. Recently, language models have also been used in many studies for sentiment analysis or text classification. In this study, Turkish sentiment analysis is performed using language models on hotel and movie review datasets. The language models are chosen because they are rarely used in Turkish literature. The pre-trained BERT, ALBERT, ELECTRA, and DistilBERT models for the Turkish language are trained and tested with these datasets. In addition, a text filtering method, which removes the words that can provide the opposition sentiment in the positive or negative labeled text, is proposed for sentiment analysis. These datasets obtained by this method are also retrained with language models and the accuracy values of their models are measured. The results of this study are compared with previous studies using the same datasets. As a result of the analysis, the accuracy values obtain state-of-the-art results with language models compared to previous studies. The best performance has been achieved by training the ELECTRA language model using the proposed text filtering method.},
journal = {ACM Trans. Asian Low-Resour. Lang. Inf. Process.},
month = {dec},
articleno = {55},
numpages = {16},
keywords = {Language model, sentiment analysis, social network, natural language processing, text classification, data analysis}
}
```
```
Guven, Z. A. (2022). The Comparison of Language Models with a Novel Text Filtering Approach for Turkish Sentiment Analysis. ACM Transactions on Asian and Low-Resource Language Information Processing, 22(2), 1-16.
```
