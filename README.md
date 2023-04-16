## Description 
This repository holds the supporting data and code for experiements conducted for test generation using pretrained T5 and GPT2 transaformer based models. 

**Research: Fine-Tuning the Muse: Enhancing Quote Generation through T5 and GPT-2 Optimization**

In this research , we present a study on fine-tuning a pre-trained T5 language model for quote generation using a large corpus of textual data that we scraped from Goodreads and BrainyQuotes. We explore the impact of different hyperparameters and training strategies on the model's performance using hard prompts and evaluate its effectiveness using three commonly used metrics: perplexity, BLEU, and GLUE. Our study provides insights into the effectiveness of fine-tuning for quote generation and demonstrates the importance of careful model selection, corpus size, hyperparameter-tuning, and evaluation metrics criteria. The purpose of this repository is to share all supporting code for the experiments conducted as a part of this research. 

### Files

Dataset includes ~2million quotes including contextual tags, and authors scraped from Goodreads and BrainyQuotes. The folder "scrape" includes the scripts used to scrape the respective sites.

Basic_Data_Exploration.ipynb contains all the basic exploration done on the quotes dataset.
