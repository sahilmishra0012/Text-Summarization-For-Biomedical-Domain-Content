# text-summarization-for-biomedical-domain-content

Biomedical information in the form of scientific articles and electronic medical
records is increasing at an alarmingly fast pace. The output of publications in
the biomedical domain is estimated to double every 5-10 years, currently with
more than 3000 new articles published per day. There is clear utility in having
systems that can automatically handle various natural language processing (NLP)
tasks, such as text summarization. Summarization is the task of distilling longer
text to a shorter version that retains the key information from the original text.
The objective of this project is to apply NLP machine learning models for text
summarization that perform well on general language text summarization datasets
and further modify/adapt for biomedical domain specific text summarization. I
evaluate and compare the performance on general language (CNN-DailyMail)
versus biomedical-specific (BioASQ) datasets, and analyze results to leverage
general language models for biomedical domain-specific application. The results
demonstrate that models trained on general language achieve comparable results
on a biomedical test set, outperforming the general language test set in one model.

Summarization is the task of automatically condensing a piece of text to a shorter version while
retaining key information content and overall meaning. This is an important topic for NLP research
because of the increasing demand for various information access applications. There are two main
paradigms to summarization: extractive and abstractive. Extractive approaches form summaries
by extracting and concatenating the most important spans from the source text, while abstractive
methods generate candidate summaries that contain novel words and phrases not featured in the
source text, usually requiring additional rewriting operations. An extractive method has the benefit of
maintaining reasonable levels of grammaticality and accuracy. Conversely, the ability to generalize,
paraphrase, and introduce additional knowledge are key features in an abstractive framework.
While there have been significant strides in improving language tasks for general language, addressing
domain-specific contexts still remains challenging. In the scientific biomedical field, the output of
publications is estimated to double every 5-10 years, currently with more than 3000 new articles
published per day. However, in contrast to general language tasks, it is challenging to generate a
biomedical domain-specific dataset comparable in scale.
