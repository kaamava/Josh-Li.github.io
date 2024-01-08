---
layout: essay
type: essay
title: "[IJCAI2024] An LDA Model Augmented with BERT for Aspect Level Sentiment Analysis"
# All dates must be YYYY-MM-DD format!
date: 2024-01-06
published: true
labels:
  - Paper
  - LDA
  - BERT
  - NLP
---
Aspect level sentiment analysis is a fine-grained task in affective analysis. It extracts aspects and their corresponding emotional polarities from opinionated texts. The first sub task of identifying the aspects with comments is called aspect extraction, which is the focus of the work. Social media platform is a huge untagged data resource. However, data annotation for fine-grained tasks is very expensive and laborious. Therefore, the unsupervised model is highly appreciated. The proposed model is an unsupervised aspect extraction method, a guided potential Dirichlet assignment (LDA) model, which uses the smallest aspect seed words from each aspect category to guide the model to identify hidden topics of interest to users. The LDA model is enhanced by using regular expressions that guide input based on language rules. The model is further enhanced through a variety of filtering strategies, including a BERT-based semantic filter, which integrates semantics to strengthen the situation where co-occurrence statistics may not be able to be used as a distinguishing factor. The threshold values of these semantic filters are estimated using Particle Swarm Optimization strategy. The proposed models are expected to overcome the shortcomings of the basic LDA models, which cannot distinguish overlapping topics representing each aspect category.
