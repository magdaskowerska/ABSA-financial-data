# ABSA-financial-data

Aspect based sentiment analysis (ABSA) is a more fine-grained method to analyze the sentiment of a document. In fact, a document or even a
sentence can contain opinions related to different concepts.

In this project, we will
perform sentiment analysis and ABSA using **Born Classifier** on financial data, the algorithm is based on **quantum theory**.
Documents and the target variable (in this case the sentiment) are quantum object, Born
Rule is applied to compute the probability of a document to collapse in the target class.

Born Classifier was trained on labeled financial data with sentiment that can take
values: **negative, neutral, positive**. 
Its performance is measured also on human-annotated dataset of news
headlines with aspect sentiment annotations and it is compared with the **FinBERT model**.

The project explores
 **aspect extraction** with the pretrained **BERT Named Entity Recognition (NER)** model in combination with **Word2Vec** and
**K-means**. 
