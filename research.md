---
title: "Research"
summary: "Description of research projects with links to papers/reports/slides/code"
date: 2016-04-13
layout: default
---

### Deep learning applied to NLP and Vision

<!-- #### Opinion summary generation from Twitter
*Guide: Prof. Ashish Anand, Dept. of CSE, IIT Guwahati*

* Developing an end-to-end system to generate topic summaries by clustering tweets related to a topic
* Proposed a novel retrofitting approach to integrate meta information from Retweet graphs into the tweet embedding. -->

#### Waldo: A system for optical character recognition
*Contributor in ongoing project under Daniel Povey*

* Wrote visualization and compression utilities for segmentation mask overlayed on image
* Modified training script for ICDAR 2015 incidental text data
* System consists of a UNet as described [here](https://arxiv.org/abs/1505.04597)

[Code](https://github.com/waldo-seg/waldo/pulls?utf8=%E2%9C%93&q=is%3Apr+author%3Adesh2608+)

#### Irony detection in tweets
*Personal project (SemEval 2018 Task 3)*

* Objective is two-fold: to recognize whether a tweet contains irony, and to classify the type of irony.
* Used holographic embeddings to model semantic interaction within a tweet, and transfer learning for world knowledge about irony in text.

[Blog](https://medium.com/explorations-in-language-and-learning/irony-detection-in-tweets-6220f480cc60)&emsp;
[Code](https://github.com/desh2608/tweet-irony-detection)

#### Relation classification for biomedical text
*Bachelor Thesis Project under Prof. Ashish Anand, Dept. of CSE, IIT Guwahati*

* Devised and implemented a novel Convolutional Recurrent Neural Network (CRNN) model to learn long and short term dependencies
* Evaluated an attentive pooling strategy in comparison with conventional pooling methods
* Achieved state-of-the-art performance on two benchmark datasets (i2b2 and DDI) without any need for manual feature engineering

[**CoNLL'17**](http://www.aclweb.org/anthology/K/K17/K17-1032.pdf)&emsp;
[Poster](assets/conll_poster.pdf)&emsp;
[Code](https://github.com/desh2608/crnn-relation-classification)

<!-- #### Identifying semantically equivalent questions
*Guide: Prof. Ashish Anand, Dept. of CSE, IIT Guwahati*

* Working on a novel technique to identify duplicate questions using a joint representation and a template-based approach
* Comparing with baselines involving feature-based classifiers, kernel-based pair-wise ranking, soft cosine similarity, and adversarial training
* Evaluation on the Quora dataset and a StackOverflow dataset -->

#### Text readability analysis using language modeling
*Guide: Prof. Ashish Anand, Dept. of CSE, IIT Guwahati*

* Developed an unsupervised approach for predicting text readability scores using different language models
* Implemented statistical and deep-learning models, for comparing results with vocabulary-based and syntactic approaches

[Report](assets/entropy_report.pdf)&emsp;
[Slides](assets/entropy_ppt.pdf)

#### Spatial transformer networks
*Guide: Prof. Arijit Sur, Dept. of CSE, IIT Guwahati*

* Used the STN module from [Jaderberg et al.](https://papers.nips.cc/paper/5854-spatial-transformer-networks.pdf) (NIPS 2015) for object recognition and activity prediction from egocentric images
* Worked with GTEA and Intel Egocentric Vision data sets on Tensorflow

[Report](assets/stn_report.pdf)&emsp;
[Slides](assets/stn_ppt.pdf)&emsp;
[Code](https://github.com/desh2608/CS574-CVML)

***

### Artificial intelligence, pattern recognition, and fuzzy theory

#### Monitoring production line performance to reduce failures
*Guide: Prof. Rashmi Dutta Baruah, Dept. of CSE, IIT Guwahati*

* The objective was to model fault recognition as a classification problem consisting of very high-dimensional data containing thousands of instances
* Worked on feature selection using Gradient Boosting, and representation of categorical features by a single numeric feature using STG and RDA methods
* Also proposed a meta-optimization of the evaluation metric using Bayesian optimization, as a post-classification step

[Report](assets/bosch_report.pdf)&emsp;
[Slides](assets/bosch_ppt.pdf)

#### Similarity analysis on multidimensional fuzzy sets
*Guide: Prof. Frank Chung-Hoon Rhee, Dept. of ECE, Hanyang University, Korea*

* Analyzed various multidimensional fuzzy membership functions and compared similarity of data sets using Wilcoxons nonparametric tests
* Established guidelines for selecting appropriate MFs based on data set and application requirements
* Recently extended the proposed method for high-dimensional data using dimensionality reduction approaches like PCA, kernel PCA, probabilistic PCA, and t-SNE

[**IEEE TFS**](assets/tfs_preprint.pdf)&emsp;
[**FUZZ-IEEE 16**](assets/fuzzieee16_preprint.pdf)&emsp;
[**IFSA 17**](assets/ifsa17_preprint.pdf)

#### Fuzzy adaptive resonance theory (ART) clustering
*Guide: Prof. Frank Chung-Hoon Rhee, Dept. of ECE, Hanyang University, Korea*

* Worked on improving clustering performance of fuzzy ART algorithm by integrating Interval Type-2 approach into vigilance parameter computation
* Obtained 5-10% better classification results compared to other methods

[Paper](https://authors.elsevier.com/c/1Vr7A4ZQDoMXI)

#### Survey on probabilistic databases
*Guide: Prof. Amit Awekar, Dept. of CSE, IIT Guwahati, India*

* Reviewed existing work on probabilistic DBs, categorized into 5 major sections, namely algebra, query evaluation, conditioning, scaling and implementation
* Through a reevaluation of performance parameters, we showed that query evaluation is indeed the
bottleneck in efficient development and implementation of the probabilistic DBMS model

[Report](assets/dbms_survey_paper.pdf)&emsp;
[Slides](assets/dbms_ppt.pdf)
