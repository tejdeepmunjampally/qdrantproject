# 📚 Document Intelligence using Qdrant Vector Database

## Overview

This project demonstrates how to build a document intelligence system using vector embeddings and Qdrant.

Documents are uploaded, converted into embeddings, stored in Qdrant, and made searchable using semantic similarity.

---

## Features

### File Upload

Supports:

- Text Files
- PDF Documents

---

### Text Extraction

Extracts content from:

- TXT Files
- PDF Files

using PyPDF.

---

### Embedding Generation

Uses:

all-MiniLM-L6-v2

to generate vector representations of documents.

---

### Qdrant Integration

Stores:

- Vector Embeddings
- File Metadata
- Document Content

inside Qdrant Collections.

---

### Semantic Search Foundation

The generated vectors can be used for:

- Retrieval Augmented Generation (RAG)
- Semantic Search
- Knowledge Base Systems
- AI Assistants

---

### Contradiction Detection

Additional logic detects contradictions and inconsistencies in uploaded content.

---

## Workflow

Upload Document
↓
Extract Text
↓
Generate Embedding
↓
Create Collection
↓
Store Vector
↓
Semantic Retrieval

---

## Tech Stack

- Python
- Qdrant
- Sentence Transformers
- PyPDF
- Google Colab

---

## Example Use Cases

- RAG Applications
- Enterprise Search
- Document Analysis
- AI Knowledge Bases
- Research Assistants

---

## Learning Outcomes

- Vector Databases
- Embeddings
- Semantic Search
- RAG Foundations
- Document Processing
