# nlp-text-reconstruction-and-semantic-analysis
Natural Language Processing project implementing text reconstruction, semantic similarity analysis, and word embedding evaluation (Word2Vec, GloVe, FastText, BERT).

Natural Language Processing Assignment 2025

This project focuses on text reconstruction, semantic similarity, and vector-based analysis using modern NLP techniques. The goal is to transform unclear or poorly structured texts into clearer and more coherent versions, and to evaluate the transformations using word embeddings and cosine similarity.

Project Overview

The assignment is divided into three main parts:

1. Text Reconstruction

Reconstructed selected sentences automatically using a custom Python pipeline.

Reconstructed two full texts using three different NLP libraries/pipelines.

Compared the clarity and structure of all reconstructed versions.

2. Computational Analysis

Used multiple embedding models (Word2Vec, GloVe, FastText, BERT embeddings).

Computed cosine similarity between original and reconstructed texts.

Visualized word embeddings with PCA / t-SNE to observe semantic shifts.

Implemented custom preprocessing and embedding workflows.

3. Structured Report

Includes methodology, experiments, results, discussion, and conclusions.

Discusses challenges in reconstruction and differences between methods.

Contains full comparison of the pipelines and embedding techniques.

Bonus (Optional Work)

Implemented Masked Clause Input completion for Greek civil code clauses.

Compared open-source models on meaning restoration accuracy.

Tools & Requirements

Python ≥ 3.10

Poetry for dependency management

Recommended libraries: numpy, pandas, scikit-learn, pytorch, gensim, transformers

Conda environment supported

.env and .gitignore included to hide credentials and large files

How to Run
poetry install
poetry run python main.py

Contents

src/ – all code for reconstruction, embeddings, and evaluation

notebooks/ – experiments, visualizations, and analysis

report/ – structured written report (PDF/Markdown)

data/ – input texts, processed versions, and embedding vectors
