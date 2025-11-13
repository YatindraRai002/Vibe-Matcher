# Vibe Matcher - AI-Powered Fashion Recommendation System

A prototype recommendation system that uses semantic embeddings and vector similarity to match user "vibe" queries with fashion products.

## 🎯 Project Overview

This project demonstrates how AI can transform fashion discovery by understanding abstract style concepts and emotional connections to clothing, rather than relying on traditional keyword-based search.

## 🚀 Features

- **Semantic Search**: Uses OpenAI embeddings (text-embedding-ada-002) to understand vibe queries
- **Vector Similarity**: Cosine similarity matching for top-K product retrieval
- **Rich Product Data**: 10 curated fashion items with detailed vibe-focused descriptions
- **Performance Metrics**: Latency tracking, similarity scoring, and quality evaluation
- **Edge Case Handling**: Fallback strategies for unrelated or empty queries
- **Interactive Demo**: Test your own vibe queries in real-time

## 📋 Requirements

- Python 3.8+
- OpenAI API key (free tier available)
- Required packages (see below)

## 🛠️ Setup

1. **Clone or download this repository**

2. **Install dependencies**:
   ```bash
   pip install openai pandas scikit-learn matplotlib seaborn python-dotenv numpy ipykernel
   ```


. **Run the notebook**:
   - Open `vibe_matcher.ipynb` in Jupyter or VS Code
   - Run all cells sequentially

## 📊 Deliverables

- ✅ Complete Jupyter notebook with outputs
- ✅ 10 mock fashion products with rich descriptions
- ✅ Embedding generation and vector search implementation
- ✅ 5+ test queries with performance metrics
- ✅ Visualizations (similarity scores, latency, quality distribution)
- ✅ Edge case handling and fallback strategies
- ✅ Reflection on improvements (Pinecone integration, hybrid search, etc.)

## 🎨 Example Queries

Try these vibe queries:
- "energetic urban chic"
- "cozy comfortable weekend vibes"
- "bold statement pieces for a night out"
- "romantic and feminine date night outfit"
- "casual vintage aesthetic"


