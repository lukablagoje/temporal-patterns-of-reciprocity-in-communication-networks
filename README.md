# Temporal Patterns of Reciprocity in Communication Networks
This project expands on the technical details of my research contributions for "Temporal Patterns of Reciprocity in Communication Networks", featured in EPJ-Data Science. 
# Research Overview
The study delves into the dynamics of human communication within various social settings, from intimate groups to global online platforms, focusing on the reciprocal exchange of information as a cornerstone for social stability, cohesion, and cooperation. My contributions were to develop the research ideas, write the article, and individually develop median-based hypothesis tests, to understand how reciprocity and memory arise in human communication. Below are the illustrations of measures we used in our research:
![image](https://github.com/lukablagoje/temporal-patterns-of-reciprocity-in-communication-networks/assets/52599010/5091a5e1-6925-443f-8134-477127126424)

For further details, check out these links:
- [EPJ-Data Science article link](https://epjds.epj.org/articles/epjdata/abs/2023/01/13688_2023_Article_382/13688_2023_Article_382.html)
- [arXiv preprint link](https://arxiv.org/abs/2207.03910)

# Technical Project Overview
The project comprises several Jupyter notebooks, each dedicated to a distinct phase of the research:

1. Shuffling functions: Scripts to generate shuffled (resampled) networks (graphs) based on different hypotheses- [**shuffling_resampling_null_model_functions.ipynb**](https://github.com/lukablagoje/temporal-patterns-of-reciprocity-in-communication-networks/blob/main/shuffling_resampling_null_model_functions.ipynb).
2. Median-based hypothesis test:  Describes how the median-based hypothesis test is performed on the Calls dataset - [**median_based_hypothesis_test.ipynb**](https://github.com/lukablagoje/temporal-patterns-of-reciprocity-in-communication-networks/blob/main/median_based_hypothesis_test.ipynb).

# Data:
Intermediate data used is uploaded in the pickle (.pkl) format. Measures are computed in the shuffled datasets - **shuffled_calls_measures.pkl**  and the original empirical datasets - **original_results.pkl**.

To access the  full data used in the research (SMS, calls, e-mails, Twitter), please refer to this [GitHub repository](https://github.com/dynamicalsystemsceu/data)
