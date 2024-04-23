# Analyzing and Classifying COVID-19 News Using TF-IDF

This Jupyter notebook explores the application of Term Frequency-Inverse Document Frequency (TF-IDF) to analyze and classify news articles about COVID-19 as real or fake. During the pandemic, the spread of misinformation has been rampant. This project aims to leverage natural language processing (NLP) to tackle this issue, providing a method to sift through the noise and identify reliable information.

## Introduction

The COVID-19 pandemic has been accompanied by a 'pandemic of misinformation'. This notebook addresses the challenge of identifying and classifying misinformation using advanced NLP techniques. We focus on using TF-IDF, a statistical measure used to evaluate the importance of a word to a document in a collection or corpus.

## Features

- **TF-IDF Analysis**: Implementation of TF-IDF to highlight significant features in texts.
- **Machine Learning Models**: Comparison of models like XGBoost and SVM to classify news effectively.
- **Linguistic Feature Analysis**: Enhanced analysis of the linguistic features that determine the model's judgment.

## Dataset

The dataset used in this study was taken from the kaggle web-site and its original purpose was to serve as a subtask for CON-STRAINT-2021. This data was obtained from several different social media including Twitter, Facebook, Instagram, etc. The dataset is split into two parts. The first one is the train set and the second one is testing set. The dataset is divided into three columns, which are id, tweet and label, where id is the news id (primary key), tweet is the content of the news and label is the classification of the news (fake or real). Considering that each news item has been labeled, this dataset can be used for this study. According to the description of the data source, the train set as well as the test set of the dataset are random sampling, so no further resampling is needed. 

## Getting Started

### Prerequisites

Before running this notebook, you need to have Python installed along with the following libraries:
- `numpy`
- `pandas`
- `sklearn`
- `matplotlib`
- `nltk`

You can install these packages using pip:
```bash
pip install numpy pandas sklearn matplotlib nltk
