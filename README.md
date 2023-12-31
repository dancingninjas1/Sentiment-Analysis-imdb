# Sentiment-Analysis-imdb with Fine-Tuned BERT

## Table of Contents
- [Introduction](#introduction)
- [Requirements](#requirements)
- [Model Information](#model-information)
- [Dataset](#Daatset)

## Introduction

This repository contains code for fine-tuning a BERT model for sentiment analysis and deploying it as a Streamlit app. The model is trained to classify text into positive or negative sentiment categories.

## Requirements

Before running the code, ensure you have the following packages installed:

```bash
!pip install datasets transformers huggingface_hub
!apt-get install git-lfs
```


## Model Information
The sentiment analysis model used in this code is based on the BERT architecture.
It has been fine-tuned on a sentiment analysis dataset.
The trained model is available on the Hugging Face Model Hub at [Hugging Face Model hub](https://huggingface.co/dancingninjas/sentiment-model/tree/main).
The streamlit app is available [here](https://huggingface.co/spaces/dancingninjas/sentiment-analysis-nlp)


## Dataset
The model has been fine-tuned on [IMDB Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

