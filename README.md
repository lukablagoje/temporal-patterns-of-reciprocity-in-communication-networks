# Research Overview

This project expands upon my published research "Temporal Patterns of Reciprocity in Communication Networks", featured in EPJ-Data Science. The study delves into the dynamics of human communication within various social settings, from intimate groups to global online platforms, focusing on the reciprocal exchange of information as a cornerstone for social stability, cohesion, and cooperation. My contributions were to develop the research ideas, write the article, and to technically develop a median-based hypothesis test, to understand how reciprocity and memory arise in human communication.
![image](https://github.com/lukablagoje/temporal-patterns-of-reciprocity-in-communication-networks/assets/52599010/5091a5e1-6925-443f-8134-477127126424)

For further details, check out these links:
- [EPJ-Data Science article link](https://epjds.epj.org/articles/epjdata/abs/2023/01/13688_2023_Article_382/13688_2023_Article_382.html)
- [arXiv preprint link](https://arxiv.org/abs/2207.03910)

# Technical Project Overview
The project comprises several Jupyter notebooks, each dedicated to a distinct phase of the research:

1. **shuffling_resampling_null_model_functions.ipynb**: Scripts to generate shuffled (resampled) networks (graphs) based on different hypotheses.
2. **median_based_hypothesis_test.ipynb**: Describes how the median-based hypothesis test is performed on the Calls dataset.

# Data:
Intermediate data used is uploaded in the pickle (.pkl) format. Measures are computed in the shuffled datasets - **shuffled_calls_measures.pkl**  and the original empirical datasets - **original_results.pkl**.

To access the  full data used in the research (SMS, calls, e-mails, Twitter), please refer to this [GitHub repository](https://github.com/dynamicalsystemsceu/data)
