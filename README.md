# Capstone Project: Using NLP to Summarize Contracts
Capstone Project Repository for General Assembly's DSI15 Machine Learning Course.

## Problem Statement 
Contracts can be long, dense and inaccessible, and a quick way to summarize the topics can give at least a good bird's eye view for legal stakeholders.

Can we use NLP models like Transformers or LDA (TBC) to summarize the topics of a contract's content? To measure success, we will use perplexity and coherence, which are topic modelling classification metrics.

Perplexity captures how surprised a model is of new data it has not seen before, and is measured as the normalized log-likelihood of a held-out test set - how well does the model represent or reproduce the statistics of the held-out data?

Topic Coherence measures score a single topic by measuring the degree of semantic similarity between high scoring words in the topic. These measurements help distinguish between topics that are semantically interpretable topics and topics that are artifacts of statistical inference. 

* Initial Code adapted from Oguejio for Chibueze's NLP modelling article:
https://towardsdatascience.com/nlp-for-topic-modeling-summarization-of-legal-documents-8c89393b1534
* Topic Modelling metrics explanation:
https://towardsdatascience.com/evaluate-topic-model-in-python-latent-dirichlet-allocation-lda-7d57484bb5d0