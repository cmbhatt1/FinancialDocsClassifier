# Finance Documents Classifier

## Overview
This project aims to classify finance documents into different categories using natural language processing (NLP) techniques. The classification model will be fine-tuned on a pre-trained model available in the Hugging Face model hub, specifically the `distilroberta-finetuned-financial-news-sentiment-analysis` model. The fine-tuning process will be performed on finance documents stored in the `data` folder within this repository.

## Data
The data folder has 5 subfolders. Each containg the class of the financial documents. Each of these folders have html files and data stored in the form of a table.

## Installation
These are the libraries being used in the project
- `transformers` library from Hugging Face: `pip install transformers`
- `datasets` library from Hugging Face: `pip install datasets`
- `scikit-learn` library for data preprocessing: `pip install scikit-learn`
- `pandas` library for data manipulation: `pip install pandas`
- `beautifulsoup4` library for HTML parsing: `pip install beautifulsoup4`
- `gradio` library for building the user interface: `pip install gradio`
Please follow the steps in the first cell to install them without errors in colab



