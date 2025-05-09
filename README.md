# Financial Sentiment Analysis Using FinBERT
By: Nuria S. Seijas
 
For: LING 539 – Statistical Natural Language Processing, Spring 2025

## Project Overview

This project explores the application of **FinBERT**, a transformer-based language model fine-tuned on financial text,It focuses on classifying the sentiment of texts such as earnings calls, SEC filings, and financial news as Positive, Negative, or Neutral. The project demonstrates how to tokenize input text, run predictions using FinBERT, and apply the results to real-world use cases in accounting and financial analytics.

The project includes a discussion of the evolution of classification models used in sentiment analysis—from early approaches like **Naive Bayes** and **Logistic Regression**, to more advanced techniques such as **word embeddings**, **neural networks**, and ultimately **large language models**. This historical perspective helps contextualize the performance and capabilities of FinBERT within the broader development of natural language processing.

## Key Dependencies

This projects mainly follows the dependencies required by **ProsusAI/finBERT** in the git repository [https://github.com/ProsusAI/finBERT.git](https://github.com/ProsusAI/finBERT.git) with a few modifications for compatability

- `transformers`==4.40.1
- `pytorch`==2.0.1
- `scikit-learn`==1.1.3
- `spacy`==3.7.5
- `textblob`==0.15.3

## Conda Environment Setup & Management

### Navigate to the Project Folder
From the Command Prompt, Anaconda Prompt or terminal:

`cd "C:\Users\..."`

Use double quotes if the path contains spaces.

### Create the Environment from `environment.yml`

`conda env create -f environment.yml`

This creates a new environment (named finbert) and installs the packages, including:
- `pytorch`
- `transformers`
- `scikit-learn`, etc.

### Activate the Environment

`conda activate finbert`

### Register the Kernel with Jupyter

Optional but Recommended

`python -m ipykernel install --user --name finbert --display-name "Python (finbert)"`

This allows the environment to be selected inside Jupyter by the name given. 

### Launch Jupyter Notebook

In the notebook interface, select: Kernel -> Change Kernel -> Python (finbert)

### Deactivate the Environment

`conda deactivate`

When you are finished you can deactivate the environment. 

### Troubleshooting the Environment
The following commands can help troubleshoot the environment

#### List Installed Packages in the Environment

`conda list -n finbert`

#### List All Conda Environments

`conda env list`
or
`conda info --envs`

#### Remove an Environment

`conda env remove --name finbert`

## Use Cases

- Earnings call analysis
- SEC 10-K sentiment classification
- Financial news screening
- Market reaction modeling
