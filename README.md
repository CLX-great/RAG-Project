# RAG-Project (Retrieval-Augmented Generation)

A lightweight RAG demo: 1.ingest documents  2. build vector index  3. retrieve  4. answer with citations.

## Features
- Document ingestion (PDF/TXT/Markdown)
- Chunking + embeddings
- Vector search retrieval (top-k)
- LLM answering with sources / citations
- Simple app UI (Streamlit) or API (FastAPI)

## Tech Stack
- Python
- Vector DB: FAISS / Chroma
- Embeddings: OpenAI / Sentence-Transformers
- LLM: OpenAI / local LLM
- (Optional) Streamlit / FastAPI

## Project Structure

src/ core logic (ingest, chunk, embed, retrieve, generate)
app/ demo app (Streamlit/FastAPI)
notebooks/ experiments
data/ sample docs (do not upload private data)
docs/ notes / screenshots

## Quickstart
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt

 Baseline RAG pipeline

 Evaluation (retrieval quality, answer faithfulness)

 Add reranker + caching

 Deploy (Docker)

