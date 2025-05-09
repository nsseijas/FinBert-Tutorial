{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "189c8014-1b15-417f-98a3-8eebd9d1af74",
   "metadata": {},
   "source": [
    "# Financial Sentiment Analysis Using FinBERT"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "2cdbb9af-c639-4ea1-98ba-9963d54838ff",
   "metadata": {},
   "source": [
    "By: Nuria S. Seijas\n",
    " \n",
    "For: LING 539 – Statistical Natural Language Processing, Spring 2025"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "b2f56a0d-07e2-47c4-8555-0f6d707ac9a2",
   "metadata": {},
   "source": [
    "## Project Overview\n",
    "\n",
    "This project explores the application of **FinBERT**, a transformer-based language model fine-tuned on financial text,It focuses on classifying the sentiment of texts such as earnings calls, SEC filings, and financial news as Positive, Negative, or Neutral. The project demonstrates how to tokenize input text, run predictions using FinBERT, and apply the results to real-world use cases in accounting and financial analytics.\n",
    "\n",
    "The project includes a discussion of the evolution of classification models used in sentiment analysis—from early approaches like **Naive Bayes** and **Logistic Regression**, to more advanced techniques such as **word embeddings**, **neural networks**, and ultimately **large language models**. This historical perspective helps contextualize the performance and capabilities of FinBERT within the broader development of natural language processing."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "26162025-1dca-479d-8b28-425e67a3d302",
   "metadata": {},
   "source": [
    "## Key Dependencies\n",
    "\n",
    "This projects mainly follows the dependencies required by **ProsusAI/finBERT** in the git repository [https://github.com/ProsusAI/finBERT.git](https://github.com/ProsusAI/finBERT.git) with a few modifications for compatability\n",
    "\n",
    "- `transformers`==4.40.1\n",
    "- `pytorch`==2.0.1\n",
    "- `scikit-learn`==1.1.3\n",
    "- `spacy`==3.7.5\n",
    "- `textblob`==0.15.3\n"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "75ada320-9ebf-45b0-92a6-ab26dfb03f46",
   "metadata": {},
   "source": [
    "## Conda Environment Setup & Management"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "80b87744-8eb1-47e3-af7e-245140d31b6d",
   "metadata": {},
   "source": [
    "### Navigate to the Project Folder\n",
    "From the Command Prompt, Anaconda Prompt or terminal:\n",
    "\n",
    "`cd \"C:\\Users\\...\"`\n",
    "\n",
    "Use double quotes if the path contains spaces."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "c5c407d1-a3a8-425d-8330-9f9024a63515",
   "metadata": {},
   "source": [
    "### Create the Environment from `environment.yml`\n",
    "\n",
    "`conda env create -f environment.yml`\n",
    "\n",
    "This creates a new environment (named finbert) and installs the packages, including:\n",
    "- `pytorch`\n",
    "- `transformers`\n",
    "- `scikit-learn`, etc.\n",
    "\n",
    "### Activate the Environment\n",
    "\n",
    "`conda activate finbert`\n",
    "\n",
    "### Register the Kernel with Jupyter\n",
    "\n",
    "Optional but Recommended\n",
    "\n",
    "`python -m ipykernel install --user --name finbert --display-name \"Python (finbert)\"`\n",
    "\n",
    "This allows the environment to be selected inside Jupyter by the name given. \n",
    "\n",
    "### Launch Jupyter Notebook\n",
    "\n",
    "In the notebook interface, select: Kernel -> Change Kernel -> Python (finbert)\n",
    "\n",
    "### Deactivate the Environment\n",
    "\n",
    "`conda deactivate`\n",
    "\n",
    "When you are finished you can deactivate the environment. "
   ]
  },
  {
   "cell_type": "markdown",
   "id": "6da29c43-9a1c-4d3a-8549-a19002d65ce5",
   "metadata": {},
   "source": [
    "### Troubleshooting the Environment\n",
    "The following commands can help troubleshoot the environment\n",
    "\n",
    "#### List Installed Packages in the Environment\n",
    "\n",
    "`conda list -n finbert`\n",
    "\n",
    "#### List All Conda Environments\n",
    "\n",
    "`conda env list`\n",
    "or\n",
    "`conda info --envs`\n",
    "\n",
    "#### Remove an Environment\n",
    "\n",
    "`conda env remove --name finbert`\n"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "0a458432-dbe5-4cf5-bff7-ad3a631b5366",
   "metadata": {},
   "source": [
    "## Use Cases\n",
    "\n",
    "- Earnings call analysis\n",
    "- SEC 10-K sentiment classification\n",
    "- Financial news screening\n",
    "- Market reaction modeling"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "bfa585cc-f2ad-4f96-9ff1-f6cb11967463",
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "",
   "name": ""
  },
  "language_info": {
   "name": ""
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
