# Mechanistic Interpretability of Transformers

This repository contains code and experiments related to training transformers and exploring their interpretability using various datasets such as IMDB and WIKITEXT.

## Introduction

Transformers have been a cornerstone in language and vision modeling since the publication of the paper "Attention is All You Need". However, the inner workings of transformers remain somewhat mysterious. This project attempts to demystify transformers by building and training a transformer from scratch. The focus is on understanding what the attention layers of the model have learned through the analysis of attention scores.

## Files and Notebooks

- **Transformer-2-Layer-Attention.ipynb**: Contains code for a 2-layer attention model using IMDB dataset.
- **Transformer-2-Layer-MLP.ipynb**: Includes code for a 2-layer attention model with additional MLP layers using IMDB dataset.
- **Transformer-BERT-Tokenizer.ipynb**: Implements a 1-layer attention model using BERT tokenizer and IMDB dataset.
- **Transformer-sweep.ipynb**: Code for a 1-layer attention model sweep using wandb with IMDB dataset.
- **WIKITEXT-600K-Transformer.ipynb**: Implements a 1-layer attention model using the WIKITEXT dataset with 600K datapoints.
- **WIKITEXT-Full-data-Transformer.ipynb**: Code for a 1-layer attention model using the full WIKITEXT dataset.

For the complete code, please refer to the `Code/` directory.

## Results and Report

For detailed results and analysis, refer to the report in Documentation folder.

