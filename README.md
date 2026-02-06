# Information-Retrieval-Agent

This repository contains a **Semantic Information Retrieval Agent** designed to answer user queries from a PDF document using vector-based semantic search. The system uses dense embeddings for similarity search and selectively applies large language models (LLMs) for reasoning and summarization tasks.

The solution follows Retrieval-Augmented Generation (RAG) principles while minimizing unnecessary LLM usage.

---

## Project Overview

The agent performs the following tasks:

- Extracts and preprocesses text from a structured PDF document
- Builds a semantic vector index using sentence embeddings
- Retrieves relevant information using cosine similarity
- Answers direct factual queries without LLM intervention
- Uses LLMs only for indirect reasoning and summarization
- Falls back to web search when the PDF does not contain sufficient information
- Produces concise, structured, and readable outputs

The data source used is **Data.pdf**.
