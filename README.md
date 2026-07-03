# 🧠 AI Neural Search Engine

> Next-generation enterprise search infrastructure combining FAISS, ColBERT, Cross-Encoder, and Gemini AI

[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.109.0-green.svg)](https://fastapi.tiangolo.com/)
[![React](https://img.shields.io/badge/React-18.2.0-blue.svg)](https://reactjs.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## 📋 Overview

AI Neural Search Engine is a **production-ready practice project** that combines:

- 🔍 **Semantic Retrieval** - FAISS vector similarity search
- 🎯 **Late Interaction** - ColBERT for document-query relevance
- 📊 **Neural Reranking** - Cross-Encoder for result refinement
- 🤖 **Contextual AI** - Gemini API for understanding
- ⚡ **Hybrid Search** - Semantic + Keyword retrieval

---

## ✨ Features

### 🔎 Search Capabilities
- ✅ Semantic Vector Search (FAISS)
- ✅ Keyword Search (Elasticsearch BM25)
- ✅ Hybrid Search (Combine both)
- ✅ Neural Reranking (Cross-Encoder)
- ✅ Contextual Understanding (Gemini AI)
- ✅ Query Suggestions & Autocomplete
- ✅ Real-time Search Results

### 📄 Document Management
- ✅ Upload (PDF, DOCX, TXT, Markdown)
- ✅ Automatic Text Chunking
- ✅ Metadata Extraction
- ✅ Real-time Indexing
- ✅ Bulk Document Operations

### 📊 Analytics Dashboard
- ✅ Search Query Logging
- ✅ Click-through Tracking
- ✅ Performance Metrics
- ✅ User Behavior Analysis
- ✅ Trending Topics

### 🎨 Modern UI
- ✅ Glass-morphism Design
- ✅ Dark/Light Mode
- ✅ Fully Responsive
- ✅ Interactive Animations
- ✅ Keyboard Shortcuts

---

## 🛠️ Tech Stack

### Backend
| Technology | Purpose |
|------------|---------|
| **FastAPI** | REST API Framework |
| **FAISS** | Vector Similarity Search |
| **ColBERT** | Late Interaction Retrieval |
| **Elasticsearch** | Keyword Search |
| **Gemini AI** | Embeddings & Context |
| **PostgreSQL** | Metadata Storage |
| **Redis** | Caching |
| **JWT** | Authentication |

### Frontend
| Technology | Purpose |
|------------|---------|
| **React 18** | UI Framework |
| **Tailwind CSS** | Styling |
| **Framer Motion** | Animations |
| **Recharts** | Analytics Charts |
| **Axios** | HTTP Client |
| **React Router** | Navigation |

---

## 🚀 Quick Start

### Prerequisites
```bash
# Required installations
Python 3.10+
Node.js 18+
PostgreSQL 14+
Redis 7+
Docker (optional)


# Create virtual environment
cd backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Setup environment variables
cp .env.example .env
# Edit .env with your credentials (Gemini API key, database, etc.)
cd frontend
npm install
cp .env.example .env