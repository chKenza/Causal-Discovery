## Causal Discovery for fairness

# Project overview

This project conducts empirical analysis of the impact of the outcome variable binarization thresholds on the Causal Graph. The analysis is carried out using synthetic, benchmark, and real-world datasets. The primary objective is to understand the relationship between binarization thresholds and the inferred causal relationships within the data.

# Data
- Datasets
Synthetic, Benchmark (Adult) and real-world (Fragrances) datasets.
- Plots
Visualizations of statistical disparity versus binarization thresholds across the synthetic, Adult, and Fragrances datasets.
- causal_graphs
Causal graphs generated for a range of outcome variable binarization thresholds (e.g., 10%, 20%, ..., 90%) for the synthetic, Adult, and Fragrances datasets.

# Code
- results
Implements causal discovery algorithms (PC and GES) and defines functions for generating causal matrices and causal graphs. It processes the datasets and produces causal graphs for each threshold, as well as the statistical disparity plots.
- gcastle_debug
Implements the PC algorithm with an extension for orienting undirected edges in the skeleton to form a Completed Partially Directed Acyclic Graph.
- pink_tax_preprocessing
Preprocesses the Fragrances dataset.

# Run the code

To run this code and get the same results that are in the Plots and Causal Graphs sections:
- Ensure that the datasets are stored in the Data directory.
- Run results.py from the Code directory.
This will generate the causal graphs for each dataset and threshold and the statistical disparity plots.
