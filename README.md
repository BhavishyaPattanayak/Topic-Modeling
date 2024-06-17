# Topic-Modeling
A dynamic topic modeling framework with a primary focus on Latent Dirichlet Allocation (LDA) and Non-Negative Matrix Factorization (NMF) algorithms. Augmented functionality with an article recommendation engine utilizing TF-IDF methodology, facilitating seamless retrieval of top-ranked documents based on user-specified keywords

This repository contains a Jupyter notebook for performing topic modeling using various Python libraries. Topic modeling is a type of statistical modeling for discovering abstract topics within a collection of documents.

## Notebook Overview

The notebook, `Topic_Modeling.ipynb`, includes the following key sections:

1. **Introduction**
   - Brief overview of topic modeling and its applications.
   
2. **Data Loading and Preprocessing**
   - Steps to load and preprocess the data.
   
3. **Topic Modeling Methods**
   - Implementations of various topic modeling techniques:
     - Latent Dirichlet Allocation (LDA)
     - Non-negative Matrix Factorization (NMF)
     - Latent Semantic Analysis (LSA)
   
4. **Model Evaluation**
   - Methods to evaluate the models and select the best performing one.
   
5. **Visualization**
   - Visualizations to interpret the topic models.

## Getting Started

### Prerequisites

Make sure you have the following packages installed:

- `numpy`
- `pandas`
- `scikit-learn`
- `nltk`
- `gensim`
- `matplotlib`
- `seaborn`

You can install these packages using `pip`:

```sh
pip install numpy pandas scikit-learn nltk gensim matplotlib seaborn
```

### Usage
Follow the instructions in the notebook to perform topic modeling on your dataset. Ensure your dataset is in the correct format as required by the notebook.

### Results
The notebook provides both qualitative and quantitative evaluation of the topic models, including visualizations to help interpret the results.

### Acknowledgements:
1. The gensim library for topic modeling.
2. The nltk library for natural language processing tools.
3. The scikit-learn library for machine learning utilities.
