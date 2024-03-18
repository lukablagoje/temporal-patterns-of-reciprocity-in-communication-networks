# Research Overview

This project expands upon my published research "Temporal Patterns of Reciprocity in Communication Networks", featured in EPJ-Data Science. The study delves into the dynamics of human communication within various social settings, from intimate groups to global online platforms, focusing on the reciprocal exchange of information as a cornerstone for social stability, cohesion, and cooperation. Unlike previous studies that primarily analyzed aggregated data, this research introduces temporal measures of reciprocity to scrutinize the timing and sequence of interactions across different communication channels, including calls, messaging, and social media.

By dissecting communication into reciprocal and non-reciprocal flows, we uncover consistent patterns that distinguish direct exchanges from broadcasted information. Employing a suite of null models to simulate communication behaviors, we pinpoint 'memory'—the propensity to re-engage with previous contacts—as a fundamental mechanism driving temporal reciprocity. Incorporating memory into an activity-driven model of dynamic networks allows us to replicate empirical levels of reciprocity observed in real-world data, providing new insights into the underlying processes that foster social norms and collective cooperation.

For further details, refer to the full article:
- EPJ-Data Science: (https://epjds.epj.org/articles/epjdata/abs/2023/01/13688_2023_Article_382/13688_2023_Article_382.html)

# Technical Project Overview

This repository hosts the codebase developed during my investigation into the temporal patterns of reciprocity within communication networks. The project comprises several Jupyter notebooks, each dedicated to a distinct phase of the research:

1. **shuffling_resampling_null_model_functions.ipynb**: Scripts to download and process neuron skeleton data into point clouds for further analysis.

# Data

The original neuron data can be accessed through the `neuprint-python` library, available at [PyPI neuprint-python](https://pypi.org/project/neuprint-python/). For an in-depth understanding of this library, visit the [neuprint-python documentation](https://connectome-neuprint.github.io/neuprint-python/docs/index.html).

The repository also includes datasets created at intermediate steps of the analysis:
- **neuron_regions_information**: Stores information about neurons within specific regions.
- **neuron_regions_points**: Contains point clouds representing neuron data.

# Folders Structure

- **neuron_regions_information**: Information about neurons in specified regions.
- **neuron_regions_points**: Point clouds data of neuron structures.

# From Research to Application

Building on the generalized meta-graph concept I developed, this project also explores the structural properties of three-dimensional networked systems, such as biological neural networks, through a Python implementation using point clouds and kd-trees. The approach is applied to analyze the physical interactions between neurons under varying conditions, revealing the compact nature of biological neural networks in contrast to other types of networks like mitochondrial, vascular, and plant root systems.

This multifaceted research not only enhances our theoretical understanding of communication patterns in social networks but also offers a novel methodology for studying the physicality of networked systems in biology and beyond.
