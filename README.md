# Sentiment Analysis on Amazon Reviews: VADER vs. Roberta Transformers

This repository contains a Jupyter notebook that showcases a comparison between two popular sentiment analysis methods on the Amazon customer reviews dataset. The methods include the VADER (Valence Aware Dictionary and sEntiment Reasoner) from the NLTK library and the RoBERTa (Robustly Optimized BERT) model from the Huggingface's Transformers library.

## Project Overview

Sentiment Analysis has become an essential tool in the world of Natural Language Processing (NLP). By classifying texts based on their sentiment, we can gain insights into user perceptions and feedback. This project aims to compare the performance and nuances of VADER, a lexicon-based approach, with the RoBERTa Transformers, a state-of-the-art deep learning model.

## Table of Contents
1. [Installation & Requirements](#installation-requirements)
2. [Dataset](#dataset)
3. [Quick EDA](#quick-eda)
4. [VADER Sentiment Scoring](#vader-sentiment-scoring)
5. [RoBERTa Pretrained Model](#roberta-pretrained-model)
6. [Comparison & Visualization](#comparison-visualization)
7. [Extra: Transformers Pipeline](#extra-transformers-pipeline)

## Installation & Requirements

Before running the Jupyter notebook, ensure you have the following libraries and tools installed:

- Python 3.x
- NLTK
- Huggingface Transformers
- Pandas
- Seaborn
- Matplotlib
- Torch

You can install the required libraries using pip:
```bash
pip install nltk huggingface-transformers pandas seaborn matplotlib torch
```

## Dataset

The project utilizes the Amazon customer reviews dataset. It comprises reviews across various products, with fields including product ID, user ID, profile name, review score, review summary, and the review text.

## Quick EDA

Exploratory data analysis (EDA) is performed to get a sense of the distribution of review scores in the dataset.

## VADER Sentiment Scoring

VADER (Valence Aware Dictionary and sEntiment Reasoner) is a lexicon-based sentiment analysis tool from the NLTK library. It's pre-trained on internet text and is sensitive to both polarity (positive/negative) and intensity (strength) of emotion.

## RoBERTa Pretrained Model

RoBERTa is a variant of BERT that is more robustly optimized. It is a transformer-based model and is known for producing state-of-the-art results on various NLP tasks. This section showcases the application of the RoBERTa model from Huggingface's Transformers library for sentiment analysis.

## Comparison & Visualization

Once both methods are applied, their results are compared and visualized. This will provide insights into the performance nuances of both techniques.

## Extra: Transformers Pipeline

This section briefly showcases the Huggingface Transformers' pipeline utility, which offers a quick and easy way to run sentiment predictions.
