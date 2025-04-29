# Text Preprocessing and Document Representation

This project demonstrates how to perform various natural language processing (NLP) techniques on a sample text document. The following operations are applied:

1. **Tokenization**: Splitting text into words.
2. **POS (Part-of-Speech) Tagging**: Identifying the grammatical categories of words.
3. **Stop Words Removal**: Removing common words that don't add much meaning.
4. **Stemming**: Reducing words to their root form.
5. **Lemmatization**: Reducing words to their base form.
6. **Term Frequency and Inverse Document Frequency (TF-IDF)**: A representation of the document using Term Frequency and Inverse Document Frequency.

The project is built using Python and NLTK (Natural Language Toolkit) and also makes use of `TfidfVectorizer` from `scikit-learn` for TF-IDF computation.

## Prerequisites

To run the code, ensure you have the following Python libraries installed:

- `nltk` (for tokenization, POS tagging, stopwords, stemming, and lemmatization)
- `scikit-learn` (for TF-IDF vectorization)

Install the required libraries with:

```bash
pip install nltk scikit-learn
