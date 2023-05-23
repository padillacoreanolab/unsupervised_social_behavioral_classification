# Social Competition Assay Behaviour Classification

This repository contains the code, data and notebooks necessary for classifying behaviour in various social competition assay using pose estimation from SLEAP, trial-based annotation (win/lose) and electrophysiology data.

## Overview
The aim of this project is to apply unsupervised machine learning techniques to classify behaviour based on multiple data streams including pose tracking, trial-based annotation and electrophysiology data. These data streams are gathered from a trial-based social competition assay. It's important to note that these data streams have different sampling rates.

## Repository Structure
The repository is organized as follows:
```
- notebooks
    - 01_data_preprocessing.ipynb
    - ...
- data
    - raw
    - interim
    - processed
- scripts
    - ...
- models
- figures
- docs
- README.md
- .gitignore
- environment.yml
- LICENSE
```

## Data
The data is stored in the data folder, divided into raw, interim and processed subfolders. The data includes pose estimation from SLEAP, trial-based annotation (win/lose) and electrophysiology data from a trial-based social competition assay.

## Notebooks
The notebooks folder contains Jupyter notebooks for different stages of the project, including data preprocessing and model training. The notebooks should be run in the order indicated by their numbering.

## Scripts
The scripts folder contains Python scripts that are used in this project.

## Models
The models folder will contain the trained machine learning models.

## Installation and Usage
First, clone this repository to your local machine using git clone.

Then, create a new conda environment and install the required dependencies using the following command:

```
conda env create -f environment.yml
```





