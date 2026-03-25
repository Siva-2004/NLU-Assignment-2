# Natural Language Understanding - Assignment 2

## How to Run the Notebooks

### Prerequisites

Install the required dependencies:

```bash
pip install gensim scikit-learn numpy pandas matplotlib nltk wordcloud torch
```

Download required NLTK data:

```bash
python -c "import nltk; nltk.download('stopwords')"
```

### Running Problem 1: Word Embeddings

1. Open Jupyter Notebook:
```bash
jupyter notebook
```

2. Navigate to and open `Word_Embeddings.ipynb`

3. Run the notebook cells sequentially using `Shift+Enter` or click the "Run All" button

4. The notebook will:
   - Load and preprocess the IIT Jodhpur corpus
   - Display dataset statistics
   - Train CBOW and Skip-gram Word2Vec models
   - Show model comparison results
   - Display nearest neighbors for key words
   - Show analogy results
   - Visualize word embeddings using t-SNE

### Running Problem 2: Name Generation

1. Open Jupyter Notebook:
```bash
jupyter notebook
```

2. Navigate to and open `Name_Generation.ipynb`

3. Run the notebook cells sequentially using `Shift+Enter` or click the "Run All" button

4. The notebook will:
   - Load 1,000 Indian names dataset
   - Train three RNN variants (Vanilla RNN, BiLSTM, RNN with Attention)
   - Show training loss curves for each model
   - Display training dynamics
   - Generate names using each model
   - Calculate and compare metrics (Novelty Rate and Diversity)
   - Show generated name samples

### Output Files

After running the notebooks, the following output files will be generated:
- Word embeddings model files
- Generated name samples
- Visualization plots and t-SNE projections
- Evaluation metrics and comparisons

### Note

- The notebooks include detailed comments explaining each step
- Run cells in order as they may depend on previous outputs
- Training may take a few minutes depending on your hardware

---

**Course**: CSL 7640 - Natural Language Understanding  
**Assignment**: Assignment-2  
**Date**: March 2026
