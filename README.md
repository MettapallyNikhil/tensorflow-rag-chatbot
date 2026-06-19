# NLP Lecture Retrieval RAG Chatbot

## Overview

This project demonstrates the complete Natural Language Processing (NLP) workflow for building a lecture slide retrieval chatbot.

The system extracts text from lecture slides, preprocesses and chunks the content, converts text into numerical representations, trains a TensorFlow classification model, and compares traditional retrieval methods with Retrieval-Augmented Generation (RAG) based semantic retrieval.

---

## Objectives

- Extract text from lecture slides
- Perform preprocessing and chunking
- Apply TensorFlow TextVectorization
- Train a simple NLP classification model
- Compare TF-IDF retrieval with semantic retrieval
- Build a RAG-style chatbot
- Evaluate retrieval quality

---

## Technologies Used

- Python
- TensorFlow
- SentenceTransformers
- FAISS
- Streamlit
- NumPy
- Pandas
- Scikit-Learn

---

## NLP Pipeline

Lecture Slides
↓
Text Extraction
↓
Text Cleaning
↓
Chunking
↓
Text Vectorization
↓
TensorFlow Model Training
↓
TF-IDF Retrieval
↓
SentenceTransformer Embeddings
↓
FAISS Vector Search
↓
RAG-based Answer Retrieval

---

## Conventional Retrieval

Methods used:

- Keyword Search
- TF-IDF

Advantages:

- Fast
- Easy to implement

Limitations:

- Requires exact keyword matches
- Poor semantic understanding

---

## RAG-Based Retrieval

Methods used:

- SentenceTransformer (all-MiniLM-L6-v2)
- FAISS Similarity Search

Advantages:

- Semantic understanding
- Better retrieval quality
- Handles paraphrased questions

---

## Results

The RAG-based retrieval system consistently returned more relevant document chunks compared to traditional keyword-based retrieval methods.

The system was capable of retrieving semantically similar content even when exact keywords were absent from the user query.

---

## Streamlit Interface

The chatbot was deployed through a Streamlit user interface to allow interactive testing and evaluation.

---

## Future Improvements

- Better chunking strategies
- Larger embedding models
- Hybrid Retrieval (TF-IDF + Semantic Search)
- LLM-based answer generation
- Multi-document support

---

## Author

Nikhil Mettapally
Master's Student – AI for Digital Production Management
Technische Hochschule Deggendorf (THD)
