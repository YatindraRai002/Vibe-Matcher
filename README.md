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

3. **Set up OpenAI API key**:
   - Get your API key from [OpenAI Platform](https://platform.openai.com/api-keys)
   - Create a `.env` file in the project root
   - Add your key: `OPENAI_API_KEY=your-api-key-here`

4. **Run the notebook**:
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

## 📈 Evaluation Criteria

- **Code Quality (30%)**: Modular functions, type hints, error handling
- **Accuracy/Eval (30%)**: Similarity metrics, threshold analysis (>0.7 = "good")
- **Innovation (20%)**: Vibe-based search, semantic understanding
- **Process (20%)**: Structured workflow, comprehensive testing

## 🔧 Future Improvements

1. **Pinecone/Weaviate Integration**: Scale to millions of products with vector databases
2. **Hybrid Search**: Combine semantic search with filters (price, category, availability)
3. **Multi-Modal Embeddings**: Add image-based search using CLIP
4. **Fine-tuning**: Train on fashion-specific corpus for better accuracy
5. **User Feedback Loop**: Implement thumbs up/down for continuous improvement

## 📝 License

This project is for educational and demonstration purposes.

## 👤 Author

Created as a prototype for Nexora's AI-powered fashion recommendation system.

---

**Note**: Remember to keep your `.env` file secure and never commit it to version control. Add `.env` to your `.gitignore` file.
