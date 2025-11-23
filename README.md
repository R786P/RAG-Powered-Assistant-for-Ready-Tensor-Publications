# RAG-Powered Assistant for Ready Tensor Publications

## 🎯 Problem Statement
Ready Tensor publications often lack structured Q&A capabilities. Readers struggle to quickly find specific information within long articles.

## 🛠️ Approach
Built a Retrieval-Augmented Generation (RAG) system that:
- Ingests Ready Tensor-style publications
- Uses FAISS for vector storage
- Employs Llama3 via Groq for generation

## 📊 Results
When asked _"What is RAG?"_, the assistant responds:  
> _"RAG combines retrieval from a knowledge base with LLM generation."_

![Output Screenshot](your-screenshot-link)

## 💡 Lessons Learned
- Chunk overlap (20 chars) ensures context continuity
- Local LLMs (Llama3) work well for simple Q&A
- MIT License ensures open collaboration
```
