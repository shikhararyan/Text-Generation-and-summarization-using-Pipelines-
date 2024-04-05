# Hugging Face Framework Tutorial using Transformers and Pipeline

![Hugging Face Logo](https://huggingface.co/datasets/huggingface/brand-assets/resolve/main/hf-logo-with-title.png)

This repository contains a Jupyter Notebook tutorial on utilizing the Hugging Face framework for natural language processing tasks. The tutorial demonstrates how to use pretrained models provided by Hugging Face to analyze sentiment and generate text.

## Getting Started

To run the notebook, follow these steps:

1. Install the required dependencies by executing the following command:
   ```bash
   pip install pandas transformers
   Download the dataset from the provided Google Drive link and save it as bbc_news.csv.
   Open the Jupyter Notebook and execute each cell sequentially.


   ## Dataset Download and Execution Instructions

1. **Download Dataset**: Download the dataset from the provided Google Drive link and save it as `bbc_news.csv`.

2. **Open Jupyter Notebook**: Open the Jupyter Notebook and execute each cell sequentially.

## Overview of Notebook Content

1. **Importing Libraries and Loading Data**: The notebook starts by importing necessary libraries such as pandas for data manipulation and loads the dataset from a Google Drive link.

2. **Data Preprocessing**: It demonstrates how to preprocess the text data by converting it to lowercase, removing stopwords, and combining title and description columns.

3. **Sentiment Analysis using Pipeline**: The notebook utilizes the Hugging Face pipeline for sentiment analysis. It demonstrates how to use the sentiment-analysis pipeline to analyze the sentiment of text data.

4. **Text Generation using GPT-2 Model**: It showcases text generation using the GPT-2 model provided by Hugging Face. The notebook utilizes the text-generation pipeline to generate text based on input descriptions.

5. **Results and Conclusion**: Finally, the notebook presents the results of sentiment analysis and text generation, along with the original dataset, sentiment labels, and generated text.

## Dataset
The dataset used in this tutorial contains news articles from various categories, including politics, business, entertainment, etc. It is available for download from [Kaggle](https://www.kaggle.com/datasets/gpreda/bbc-news).

