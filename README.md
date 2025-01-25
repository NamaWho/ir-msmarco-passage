# IR Notebook (MSMARCO)

## Description
This notebook focuses on an **Information Retrieval project** conducted by: L. Arduini, D. N. Ghaneh, L. Menchini, C. Petruzzella.

It covers the implementation of various techniques and tools for building and analyzing retrieval systems, leveraging state-of-the-art libraries and datasets.

Query processing is performed through TAAT (Term-at-a-Time) and DAAT (Document-at-a-Time) approaches. Scoring is computed using both TFIDF and BM25. The dataset used for evaluation is MSMARCO (Passage). 

## Structure of the Notebook

### Key Sections
1. **Setup and Installation:**
   - Dependencies are installed using Python's `pip`, including libraries like `ir_datasets`, `nltk`, `ir_measures`, `PyStemmer`, and `pandas`.
   - Example:
     ```bash
     !pip install ir_datasets
     ```

2. **Dataset Loading:**
   - Utilizes tools such as `ir_datasets` to work with standard datasets for retrieval tasks.

3. **Preprocessing:**
   - Steps include tokenization, stemming, and handling stopwords using libraries like `nltk` and `PyStemmer`.

4. **Retrieval System Implementation:**
   - Employs frameworks such as `python-terrier` for retrieval system creation and evaluation.

5. **Evaluation and Metrics:**
   - Methods to evaluate system performance using measures from `ir_measures`.

## Requirements
To run this notebook, ensure the following are installed:
- Python >= 3.7
- Required Libraries:
  - `ir_datasets`
  - `nltk`
  - `ir_measures`
  - `PyStemmer`
  - `pandas`
  - `python-terrier`
  - `gdown`