# Literature Network Graph

## Overview
This repository contains R code to create a network graph visualizing keywords extracted from academic literature. The network graph provides an overview of key concepts in the literature related to a specific topic.

## Code
The R code in this repository utilizes`igraph`, `bibliometrix`, `ggraph`, `ggplot2`, `tidygraph`, `dplyr`, and `oaqc`. These packages are used to load, analyze, and visualize the literature data.

## Data
The data used for this analysis is sourced from Web of Science search results. The plain text files are converted into a structured data frame for analysis.

## Network Graph
The network graph is created using the `igraph` package. Keywords from the literature are extracted and organized into a network, where nodes represent keywords and edges indicate co-occurrence relationships.

## Clustering
The network is clustered to group related keywords together. Louvain clustering is applied to color-code nodes by their clusters, and node size represents their degree of importance in the network.
