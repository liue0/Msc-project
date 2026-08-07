This repository contains the code, data samples, and results for my Master's thesis project.

## 1. Project Overview
This project implements a recommendation system featuring:
* Baseline: Collaborative Filtering (5-core dense subset)
* Feature Extraction: BERT for textual data
* Fusion: Attention mechanism for multi-modal feature integration

## 2. Directory Structure
* `dataset/`: Placeholder directory for the dataset files (downloaded from Google Drive).
* `models/`: Placeholder directory for the pre-trained model and checkpoint files(downloaded from Google Drive).
* `notebooks/`: Jupyter notebooks runnable in Google Colab.
* `results/`: Output charts, evaluation metrics, and performance comparisons.

## 3. Data & Model Access
Due to file size limitations, the complete dataset and model files are hosted on Google Drive.
* **Google Drive Link**:https://drive.google.com/drive/folders/14Nm7rt95aNtuxT4Zicrsc0ibZs8IACad?usp=sharing
* **Original Dataset Reference**:https://amazon-reviews-2023.github.io/index.html#introduction

## 4. How to Reproduce the Results
To ensure reproducibility, please follow these steps:

1. **Environment Setup**:
   Install the required dependencies.

2. **Data & Model Preparation**:
   The code is designed to read from local files to avoid hardcoding. Download the dataset and model files from the Google Drive link provided above. Place the dataset files into the `/dataset` folder and the model files into the `/models` folder.

3. **Execution**:
   Upload the scripts in `/notebooks` to Google Colab and run them sequentially.

## 5. Key Results
Can be seen in `/results`.
