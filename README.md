# README

## Overview

This repository contains the code and data supporting the visualization
of urban morphology through network analysis and clustering. The project
explores how different cities can be compared by combining **graph-based
representations of street networks** with **dimensionality reduction
(UMAP)** and **clustering (HDBSCAN)**.

The outcome is a **set of color-coded maps**, where clusters derived
from abstract embeddings are visually confronted with the topographic
view of the cities.

## Theoretical Framework

The project builds on the idea that cities can be studied as networks,
where nodes and edges correspond to intersections and streets. By
applying **UMAP** (Uniform Manifold Approximation and Projection), the
high-dimensional structure of urban networks is reduced into two
dimensions. **HDBSCAN** is then applied to identify clusters, which are
interpreted as morphological zones of the city.

The colored maps allow for a confrontation between two perspectives: the
**abstract embedding of the city's structure** and its **geographic
form**.

## Outputs

All these results have also been published in **comparison.pdf**, which
is the main aggregated output of this work. The other files are
supporting materials that form part of the workflow.

-   **maps/**: color-coded maps of cities, showing clusters overlaid on
    street networks\
-   **clusters/**: UMAP embeddings of cities, color-coded by HDBSCAN
    cluster\
-   **taxonomy/**: visual classification of morphological types\
-   **embeddings/**: intermediate UMAP coordinates\
-   **graphs/**: GraphML files of city networks

## How to Use

1.  Install dependencies with `requirements.txt`.\
2.  Run `generator.ipynb` to reproduce maps and embeddings.\
3.  Outputs will appear in their respective folders.
