This repository contains the code, data samples, and results for my Master's thesis project.

## 1. Project Overview
This project implements a recommendation system featuring:
* Baseline: Collaborative Filtering (5-core dense subset)
* Feature Extraction: BERT for textual data
* Fusion: Attention mechanism for multi-modal feature integration

## 2. Directory Structure
* `dataset/`: Contains complete dataset.
* `notebooks/`: Jupyter notebooks runnable in Google Colab.
* `results/`: Output charts, evaluation metrics, and performance comparisons.

## 3. How to Reproduce the Results
To ensure reproducibility, please follow these steps:

1. **Environment Setup**:
   Install the required dependencies

2. **Data Preparation**:
   The code is designed to read from local files to avoid hardcoding. Place the raw dataset into the `/dataset` folder. (Link to full dataset: Amazon Reviews'23)

3. **Execution**:
   Upload the scripts in `/notebooks` to Google Colab and run them sequentially.

## 4. Key Results
Can be seen in `/results`.