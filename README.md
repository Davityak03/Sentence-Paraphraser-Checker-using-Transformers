# Sentence-Paraphraser-Checker-using-Transformers

## Overview

This Jupyter Notebook, `Sentence_Paraphrase_Checker.ipynb`, implements a tool to check whether two sentences are paraphrases of each other. It leverages natural language processing (NLP) techniques and with the help of transformers to analyze the semantic similarity between pairs of sentences.

## Features

- **Sentence Pair Input**: Allows users to input pairs of sentences to check for paraphrasing.
- **Semantic Analysis**: Uses NLP models to determine the similarity between sentences.
- **Similarity Score**: Returns a similarity score or a binary decision (paraphrase or not) based on the analysis.

## Requirements

To run this notebook, you need to have the following installed:

- Python 3.x
- Jupyter Notebook
- The following Python libraries:
  - `numpy`
  - `pandas`
  - `nltk` (Natural Language Toolkit)
  - `transformers` (Hugging Face library for NLP models)
  
You can install these libraries using pip:

```bash
pip install numpy pandas nltk transformers
```

## How to Use

1. **Launch Jupyter Notebook**: Open a terminal and navigate to the directory containing this notebook. Launch Jupyter Notebook using the command:

   ```bash
   jupyter notebook
   ```

2. **Load the Notebook**: In the Jupyter Notebook interface, navigate to `Sentence_Paraphrase_Checker.ipynb` and open it.

3. **Run the Notebook**: Execute the cells sequentially. The notebook may include sections for:
   - Data preprocessing
   - Loading pre-trained NLP models
   - Computing similarity scores
   - Outputting results

4. **View Results**: The notebook will output whether the sentences are paraphrases and may provide a similarity score.

## Example

Here’s an example :

- **Input**:
  - Sentence 1: "The quick brown fox jumps over the lazy dog."
  - Sentence 2: "A fast, dark-colored fox leaps over a sleeping dog."

- **Output**:
  - Similarity Score: 0.85
  - Paraphrase: Yes


## Acknowledgements

- This notebook may use pre-trained models from the Hugging Face `transformers` library.
- NLP techniques may be based on concepts from `nltk`.
