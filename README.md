# Financial Fraud Detection and Explainable Analysis using RAG and LLMs

## Overview

This project presents an AI-powered financial fraud analysis system that combines **Retrieval-Augmented Generation (RAG)** and **Large Language Models (LLMs)** to detect suspicious financial transactions and generate human-readable explanations.

Unlike traditional fraud detection systems that provide only binary predictions, this framework performs semantic retrieval, fraud scoring, transaction entity extraction, and explainable risk analysis to improve transparency and decision-making.

## Publication Status

**Role:** Primary Author

**Paper Status:** Under Review

**DISHA 2026 – 5th International Conference on Deep Learning Innovations for Smart Humanized AI**

**Paper Title:**
*Financial Fraud Detection and Explainable Analysis using Retrieval-Augmented Generation and Large Language Models*

## Key Features

- Retrieval-Augmented Generation (RAG) based fraud analysis
- Semantic retrieval using FAISS vector database
- Sentence-BERT embeddings for transaction understanding
- Explainable fraud reasoning using Phi-2 LLM
- Transaction entity extraction
- Rule-based fraud scoring mechanism
- PDF bank statement processing
- Human-readable fraud explanations and recommendations

## System Workflow

1. Transaction Input (Manual Entry / PDF Statement)
2. Text Preprocessing and Normalization
3. Entity Extraction
4. Sentence-BERT Embedding Generation
5. FAISS-Based Semantic Retrieval
6. Fraud Rule Retrieval
7. Prompt Construction
8. Phi-2 LLM Reasoning
9. Fraud Explanation Generation
10. Fraud Scoring and Classification

## Technologies Used

### Machine Learning & NLP
- Retrieval-Augmented Generation (RAG)
- Sentence-BERT
- Phi-2 Large Language Model

### Libraries & Tools
- Python
- Transformers
- Sentence-Transformers
- FAISS
- NumPy
- Gradio

### Development Environment
- Google Colab
- GitHub

## Methodology

### Data Processing
- Transaction text normalization
- Fraud keyword identification
- Entity extraction using pattern matching

### Semantic Retrieval
Fraud indicators are converted into dense vector embeddings using Sentence-BERT and stored in a FAISS vector database. Relevant fraud patterns are retrieved through similarity search.

### Explainable Fraud Analysis
Retrieved fraud indicators are passed as contextual information to the Phi-2 Large Language Model through a RAG pipeline, enabling explainable and context-aware fraud analysis.

### Fraud Scoring
The system assigns fraud scores based on suspicious transaction patterns and retrieved fraud indicators before generating recommendations.

## Sample Capabilities

- Detect suspicious money transfers
- Analyze high-value transactions
- Identify risky transaction patterns
- Extract transaction entities
- Generate fraud explanations
- Recommend preventive actions

## Research Contribution

This work integrates:

- Retrieval-Augmented Generation (RAG)
- Sentence-BERT Embeddings
- FAISS Vector Search
- Large Language Models (Phi-2)

to improve explainability and contextual understanding in financial fraud detection systems.

## Future Improvements

- Integration with real-world banking datasets
- Advanced Named Entity Recognition (NER)
- Fraud pattern learning using supervised ML models
- Multi-language fraud analysis
- Real-time fraud monitoring dashboard
