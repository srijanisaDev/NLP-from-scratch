# NLP From Scratch

A hands-on repository documenting core **Natural Language Processing (NLP)** concepts implemented step-by-step using notebooks, practice datasets, and small experiments.  
This repo is focused on learning-by-doing: preprocessing, linguistic features, vectorization, and classic NLP workflows.

## What’s inside

- Text preprocessing pipeline (cleaning + normalization)
- Tokenization
- Stemming
- Lemmatization
- POS (Part-of-Speech) tagging
- Feature extraction
- Word vectorization (Word2Vec)
- Text classification workflow
- Practice datasets + transcripts (e.g., IMDB / Friends)

## Repository structure

Typical files/folders you may find:

- `data_GOT/` : Dataset folder (custom / project specific)
- `IMDB Dataset.csv` : Dataset used for sentiment / classification experiments
- `Friends_Transcript...` : Raw/processed transcript text used for NLP tasks
- `slang.txt` : Slang/normalization reference list
- Notebooks:
  - `Tokenization.ipynb`
  - `stemming.ipynb`
  - `lemmatization.ipynb`
  - `POS_Tagging.ipynb`
  - `feature_extraction...ipynb`
  - `word_2_vec.ipynb`
  - `word2vec_friends...ipynb`
  - `text_preprocessin...ipynb`
  - `text_classification...ipynb`

## Getting started

### Requirements
- Python 3.8+  
- Jupyter Notebook / JupyterLab (or VS Code notebooks)

### Setup

```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
python -m venv venv
# Activate:
# Windows: venv\\Scripts\\activate
# Mac/Linux: source venv/bin/activate
pip install -r requirements.txt
```

If `requirements.txt` is not present yet, install common NLP libraries:

```bash
pip install numpy pandas scikit-learn nltk spacy gensim matplotlib seaborn jupyter
```

> Note: Some notebooks may require downloading language models/resources (e.g., NLTK corpora or spaCy models).

## How to run

Open notebooks locally:

```bash
jupyter notebook
```

Then run notebooks in roughly this learning order:

1. `text_preprocessin...ipynb`
2. `Tokenization.ipynb`
3. `stemming.ipynb`
4. `lemmatization.ipynb`
5. `POS_Tagging.ipynb`
6. `feature_extraction...ipynb`
7. `word_2_vec.ipynb` / `word2vec_friends...ipynb`
8. `text_classification...ipynb`

## Datasets used

- IMDB dataset for sentiment analysis (`IMDB Dataset.csv`)
- TV show transcripts (example: Friends / GOT) for word embeddings & text experiments
- Game of Thrones script present in the data_Got

If any dataset is large, consider using Git LFS or providing a download link instead of committing the full file.

## Learning goals

- Understand why each preprocessing step matters (and when it can hurt).
- Build intuition for sparse vectors (BoW/TF-IDF) vs dense vectors (Word2Vec).
- Create an end-to-end text classification pipeline with evaluation.

