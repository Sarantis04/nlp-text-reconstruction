# Natural Language Processing : Text Reconstruction
## Description
A complete NLP project for text reconstruction and evaluation using rule-based rewriting, pre-trained language model pipelines, semantic similarity analysis, and automatic metrics like cosine similarity, PCA/t-SNE visualization, and BERTScore.

## 📌 Features
- ✅ Rule-based text rewriting  
- 🤖 Grammar correction and summarization with pre-trained transformers  
- 📊 Semantic similarity analysis (cosine similarity, embeddings)  
- 🧪 Visualization with PCA and t-SNE  
- 📈 BERTScore evaluation vs. gold standards

## 🤖 Models & Tools Used
The project makes use of several pre-trained NLP models and libraries:
- Rule-based rewriting with Python (re, nltk) for controlled sentence corrections.
- vennify/t5-base-grammar-correction – Transformer model for grammar correction.
- prithivida/grammar_error_correcter_v1 – Grammar error correction model.
- sshleifer/distilbart-cnn-12-6 – Summarization model for generating concise versions of texts.
- Sentence-Transformers (all-MiniLM-L6-v2) – For semantic embeddings and cosine similarity analysis.
- BERTScore – For evaluation against gold standard texts.
- scikit-learn (PCA, t-SNE) – For dimensionality reduction and visualization of embeddings.

## 🚀 Usage
Run each notebook step by step to reproduce results.

## 📊 Results
- Grammar-corrected text shows highest semantic similarity to gold standard
- Summarization yields concise but less faithful outputs
- Rule-based rewriting is useful for predictable error patterns and smaller texts
