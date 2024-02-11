For an in-depth analysis of our findings, please refer to the [Mechanistic Interpretability Report](Documentation/Report.pdf).

# Mechanistic Interpretability of Transformers

Welcome to the Mechanistic Interpretability of Transformers repository! Here, we delve into the fascinating world of transformers, the backbone of language and vision models, to uncover their mysteries. This project takes you on a journey of building and training transformers from scratch, with a special focus on unraveling the secrets hidden within their attention layers.

## Introduction

Transformers are like the wizards of the artificial intelligence realm, enabling machines to understand and generate human-like text and images. Think of them as brilliant storytellers that learn from examples and capture intricate patterns in language and vision. Our project aims to demystify these transformers by not only using them but also understanding what happens inside their magical layers.

## Code and Experimentation

Embark on a technical journey by delving into the following notebooks, each unraveling distinct aspects of transformer dynamics:

- **Transformer-2-Layer-Attention.ipynb**: A deep dive into a 2-layer attention model employing the IMDB dataset.
- **Transformer-2-Layer-MLP.ipynb**: Extending the exploration with a 2-layer attention model enriched by additional Multi-Layer Perceptron (MLP) layers using the IMDB dataset.
- **Transformer-BERT-Tokenizer.ipynb**: Harnessing the potency of a 1-layer attention model leveraging the BERT tokenizer in conjunction with the IMDB dataset.
- **Transformer-sweep.ipynb**: A comprehensive exploration involving a 1-layer attention model sweep utilizing wandb with the IMDB dataset.
- **WIKITEXT-600K-Transformer.ipynb**: Uncovering insights derived from a 1-layer attention model deployed on the WIKITEXT dataset containing 600K datapoints.
- **WIKITEXT-Full-data-Transformer.ipynb**: Expedition into a 1-layer attention model using the complete WIKITEXT dataset.

The entirety of the source code is accessible in the `Code/` directory.

## Results and Report Highlights 

1. **Model Training Performance**: An evaluation of the performance metrics achieved by our transformers on IMDB and WIKITEXT datasets.
2. **Attention Layer Insights**: An exploration of the learned patterns within the attention layers, unraveling the narrative-building capacities of transformers.
3. **Model Comparisons**: A comparative analysis spanning diverse models, ranging from 2-layer attention to those augmented with supplementary MLP layers.
4. **BERT Tokenizer Experiment**: An investigation into the implications of integrating the BERT tokenizer, accentuating the augmentation it introduces.
5. **Sweeping Discoveries**: An account of the comprehensive sweep through the 1-layer attention model facilitated by wandb on the IMDB dataset.
6. **WIKITEXT Dataset Dive**: An exploration of model behavior when exposed to the WIKITEXT dataset, both in its 600K datapoint iteration and in its entirety.

