# NaiveRAG Exploration

A hands-on exploration of Retrieval-Augmented Generation (RAG) pipelines, built from scratch for learning and experimentation. More info at the start of each notebooks.

## 🛠️ Technology Stack

- **Vector Database**: Qdrant (in-memory)
- **Embedding Model**: nateraw/bge-large-en-v1.5 (via Replicate)
- **LLM**: meta/llama-2-70b-chat (via Replicate)
- **Framework**: LangChain
- **Dataset**: atitaarora/qdrant_doc
- **Evaluation**: RAGAS

## 🚀 Quick Start

1. Install dependencies:
```bash
pip install -r requirements.txt
```
Or you can see the notebook first cell.
2. Set your Replicate API token:
```python
os.environ["REPLICATE_API_TOKEN"] = "your_token_here"
```

3. Run the notebook:
```bash
jupyter notebook Naive_RAG.ipynb
```

## 📖 What's Inside

This project contains a complete RAG pipeline implemented in notebook format. Follow the cells sequentially to:
- Load and chunk documents
- Generate embeddings
- Store vectors in Qdrant
- Retrieve relevant context
- Generate AI responses
- Evaluate with RAGAS

## 🔄 Status

This is an active learning project. I'm continuously adding new experiments and improvements. Check back for updates!

## 📝 Notes

- Currently uses in-memory Qdrant for simplicity
- Sample size limited to 50 chunks by default
- Designed for educational purposes and experimentation

## 📄 License

MIT