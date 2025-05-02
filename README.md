# bartangi-lemmatizer-v2
Final version of Bartangi Lemmatizer and Word2Vec embeddings
# Bartangi Lemmatizer and Word Embeddings

This repository contains the final version of the Bartangi Lemmatizer pipeline, designed to preprocess Bartangi language text using morphological parsing, rule-based filtering, and train word embedding models (CBOW and Skip-gram) to analyze and visualize word relations.

## 📌 Project Overview

- **Language**: Bartangi (Low-Resource Language)
- **Corpus**: Cleaned and lemmatized corpus prepared using morphological parsing and post-processing.
- **Models**: Word2Vec (CBOW and Skip-gram) models trained on the cleaned corpus.
- **Visualizations**: PCA and t-SNE visualizations of word embeddings for analysis and comparison.
- **Comparison**: Side-by-side visualization of Skip-gram vs CBOW embeddings for linguistic analysis.

## 📥 Dataset

The raw corpus was processed using:

- [tsakorpus_bartangi morphological analyzer](https://github.com/Novokshanov/tsakorpus_bartangi/tree/master)

## 🔧 Morphological Parsing and Cleaning

- Affix-only lemmas were removed.
- Short/empty lemmas were discarded.
- Significant POS were retained: NOUN, VERB, ADJ, ADV, ADP, PRON, NUM.

## 🧠 Word Embedding Models

- CBOW and Skip-gram Word2Vec models.
- Models exported to `.txt` format for reuse.

## 📊 Visualization

- PCA and t-SNE plots for each model.
- Skip-gram vs CBOW comparison plots included.

## 📧 Contact

For questions or collaborations:

[Warda Tariq]  
[varda@hse.ru]

