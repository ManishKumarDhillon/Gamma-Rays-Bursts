# Gamma-Ray Burst Dataset Analysis

This repository contains code and documentation for analyzing the Gamma-Ray Burst (GRB) dataset obtained from NASA's FERMI Satellite. The analysis aims to determine the total number of distinct classes present within the dataset and uncover underlying structures using Gaussian Mixture Models (GMM).

## Overview

The analysis encompasses:

- **Dataset Description**: Details regarding the GRB dataset sourced from NASA's FERMI Satellite.
- **Dataset Link**: https://heasarc.gsfc.nasa.gov/w3browse/fermi/fermigbrst.html
- **Objective**: To identify and understand the different classes within the GRB dataset.
- **Methodology**: Utilization of GMM for clustering and uncovering underlying structures.
- **Results**: Insights gained into the underlying structures and patterns present in the Gamma-Ray Burst data.

## Analysis Steps

1. **Data Exploration**: Understanding the characteristics and attributes of the GRB dataset.
2. **Histogram Analysis**: Computed GMM on the histogram of the T-90 data.
3. **Combined Analysis**: Computed GMM on the T-90 and T-50 data.
4. **Interpretation**: Analysis and interpretation of the clustered classes and their significance within the GRB dataset.

## Repository Structure

- `code/`: Contains the scripts and notebooks used for data analysis.
  - `histogram.ipynb`: Python notebook for computing GMM on the histogram of T-90 data.
  - `scatter.py`: Python script for computing GMM on the combined T-90 and T-50 data.
- `data/`: Holds the Gamma-Ray Burst dataset used in the analysis.
- `results/`: Includes visualizations, summaries, or any output generated during the analysis.

## Getting Started

To replicate the analysis:

1. Clone this repository.
2. Navigate to the respective directories (`code/histogram.ipynb` or `code/scatter.py`).
3. Execute the scripts or notebooks in a Python environment with necessary dependencies installed.

## Contribution Guidelines

Contributions are welcome! If you wish to contribute to this analysis or improve the codebase, please follow the guidelines outlined in CONTRIBUTING.md.
