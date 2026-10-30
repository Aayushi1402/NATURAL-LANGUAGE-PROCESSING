

# Natural Language Processing (NLP) Lab Programs

## Introduction
This repository contains 32 practical programs based on Natural Language Processing (NLP). These programs cover text preprocessing, feature extraction, machine learning, deep learning, transformer models, sentiment analysis, and document processing using Python and popular NLP libraries.

## List of Programs

### CO1 – Text Preprocessing and Linguistic Analysis

**1. Tokenization of Sentences and Words using NLTK and spaCy**

Tokenization is the process of splitting text into individual sentences and words. This program uses NLTK and spaCy to perform sentence and word tokenization.

**2. Stemming and Lemmatization on Sample Text**

Stemming removes word endings to obtain root-like forms, while lemmatization converts words into their meaningful dictionary forms. This program demonstrates both techniques using NLTK.

**3. Stop-word Removal from a Document**

Stop-word removal eliminates common words such as "is", "the", "and", and "are" from text. This helps retain meaningful words for further NLP processing.

**4. Part-of-Speech (POS) Tagging of a Given Sentence**

POS tagging identifies the grammatical category of each word, such as noun, verb, adjective, and adverb. This program uses NLTK to perform grammatical tagging.

**5. Parsing and Chunking using Regex and spaCy**

Parsing analyzes the grammatical structure of a sentence, while chunking groups related words into meaningful phrases. This program uses regular expressions and spaCy for extracting noun phrases and grammatical relationships.

**6. Named Entity Recognition (NER) using spaCy**

Named Entity Recognition identifies important entities such as people, organizations, locations, and dates from text. This program uses spaCy to detect and classify named entities.

### CO2 – Text Representation, Machine Learning and Analysis

**7. Coreference Resolution using neuralcoref (or Similar)**

Coreference resolution identifies different words or expressions that refer to the same entity. This program uses FastCoref to identify relationships between names and pronouns in a document.

**8. Bag-of-Words (BoW) Vectorization and Representation**

Bag-of-Words converts text documents into numerical vectors based on word frequency. This program uses CountVectorizer to represent text mathematically.

**9. TF-IDF Implementation and Comparison with BoW**

TF-IDF measures the importance of words in a document relative to a collection of documents. This program implements TF-IDF and compares its representation with Bag-of-Words.

**10. N-Gram Model (Uni-, Bi-, Tri-gram) Generation from Corpus**

N-Grams represent sequences of consecutive words in a text. This program generates unigrams, bigrams, and trigrams to analyze word combinations and language patterns.

**11. Cosine Similarity Computation between Text Documents**

Cosine similarity measures the similarity between two text documents by comparing their numerical vectors. This program uses TF-IDF and cosine similarity to identify related documents.

**12. Word2Vec Word Embeddings using Gensim on a Custom Corpus**

Word2Vec learns numerical representations of words based on their surrounding context. This program trains a Word2Vec model using Gensim on a custom text corpus.

**13. GloVe Embeddings Loading and Vector Representation**

GloVe (Global Vectors for Word Representation) generates word embeddings using global word co-occurrence statistics. This program loads pretrained GloVe embeddings and explores word vectors and similarities.

**14. Text Similarity using Word Mover's Distance (WMD)**

Word Mover's Distance measures semantic similarity between documents using word embeddings. This program calculates the minimum distance required to transform one document's word distribution into another.

**15. Text Classification using Naive Bayes/SVM with TF-IDF**

Text classification assigns predefined categories to text documents. This program uses TF-IDF features with Naive Bayes and Support Vector Machine (SVM) algorithms to classify text.

**16. Sentiment Analysis using TextBlob and VADER**

Sentiment analysis identifies whether a text expresses positive, negative, or neutral opinions. This program uses TextBlob and VADER to analyze sentiment polarity.

**17. Topic Modeling using Latent Dirichlet Allocation (LDA)**

LDA is an unsupervised machine learning technique used to discover hidden topics in a collection of documents. This program identifies topics based on frequently occurring words.

**18. Topic Modeling using Latent Semantic Analysis (LSA)**

LSA discovers hidden semantic relationships between words and documents using Singular Value Decomposition (SVD). This program applies TF-IDF and dimensionality reduction to identify latent topics.

**19. Opinion Mining on Product/Service Reviews Dataset**

Opinion mining extracts customer opinions from product and service reviews. This program analyzes reviews and classifies them as positive, negative, or neutral.

**20. Information Extraction (IE) from Structured/Unstructured Documents**

Information Extraction identifies useful information from structured and unstructured data. This program extracts named entities, email addresses, dates, and other important details using spaCy and regular expressions.

**21. Information Retrieval System with Ranking using TF-IDF**

Information Retrieval helps users find relevant documents based on a search query. This program uses TF-IDF and cosine similarity to rank documents according to their relevance.

**22. Sequence Classification using RNN/LSTM (Keras/TensorFlow)**

RNN and LSTM are deep learning architectures used to process sequential data. This program builds an LSTM model using TensorFlow/Keras to classify sequences into different categories.

**23. Implementing Attention Mechanism (Basic Custom Model)**

The attention mechanism allows a neural network to focus on important parts of input sequences. This program implements a basic custom attention model using TensorFlow/Keras.

### CO3 – Advanced NLP and Transformer-Based Applications

**24. Fine-Tuning BERT for Text Classification using Hugging Face**

BERT is a pretrained transformer model that understands contextual relationships between words. This program fine-tunes BERT using Hugging Face Transformers to classify text into different categories.

**25. Sentence Embeddings using BERT and GPT-2**

Sentence embeddings convert sentences into numerical vector representations. This program uses pretrained BERT and GPT-2 models to generate contextual sentence embeddings.

**26. Text Generation using GPT-2 on a Custom Dataset**

GPT-2 is an autoregressive language model that generates text based on previous words. This program uses a custom text prompt with pretrained GPT-2 to generate meaningful text.

**27. Named Entity Recognition using Transformers (BERT)**

This program uses a pretrained BERT-based transformer model to identify and classify named entities such as people, organizations, and locations from text.

**28. Machine Translation using MarianMT or T5 (Hugging Face)**

Machine translation automatically converts text from one language into another. This program uses the MarianMT model from Hugging Face to translate English sentences into French.

**29. Text Summarization using BART or T5**

Text summarization generates shorter versions of lengthy documents while preserving important information. This program uses a pretrained BART model to produce concise summaries.

**30. Chatbot Development using Pre-trained Transformer (DialoGPT/ChatGPT-style)**

This program develops a conversational chatbot using the pretrained DialoGPT transformer model. It accepts user messages, maintains conversation history, and generates automated responses.

**31. Automatic Document Classification and Separation using ML**

This program automatically classifies documents into predefined categories using machine learning. It uses TF-IDF and Naive Bayes to classify and group documents based on their content.

**32. Hybrid Probabilistic + FSM-Based Sequence Modeling for Document Boundary Detection**

This program combines probabilistic classification and a Finite State Machine (FSM) to detect document boundaries. It identifies the beginning of new documents and groups related pages into separate documents.

## Technologies and Libraries Used

- Python
- Google Colab
- NLTK
- spaCy
- Scikit-learn
- Gensim
- TextBlob
- VADER Sentiment
- TensorFlow and Keras
- PyTorch
- Hugging Face Transformers
- Pandas
- NumPy
- Regular Expressions (Regex)

## How to Run the Programs

1. Open Google Colab.
2. Create a new Python notebook.
3. Copy the required program code into a code cell.
4. Install the necessary libraries and dependencies.
5. Run the code and wait for execution.
6. View the generated output.

## Requirements

- Python 3.x
- Google Colab or Jupyter Notebook
- Internet connection for downloading libraries and pretrained models.
- GPU runtime recommended for deep learning and transformer-based programs.

## Learning Outcomes

After completing these programs, students will be able to:

1. Understand fundamental NLP preprocessing techniques.
2. Perform text tokenization, stemming, lemmatization, and POS tagging.
3. Convert text into numerical representations using BoW, TF-IDF, and word embeddings.
4. Apply machine learning algorithms for text classification and sentiment analysis.
5. Perform topic modeling and information retrieval.
6. Understand neural networks, RNN, LSTM, and attention mechanisms.
7. Work with transformer models such as BERT, GPT-2, and BART.
8. Develop NLP applications for translation, summarization, and text generation.
9. Perform information extraction and automatic document classification.

## Conclusion

These 32 practical programs provide hands-on experience with fundamental and advanced Natural Language Processing techniques. They demonstrate how NLP can be used to process, analyze, understand, classify, and generate human language using machine learning and deep learning approaches.

---
**Natural Language Processing (NLP) Laboratory – Practical Programs**
