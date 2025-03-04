# RAG Pipeline Project

A Python-based implementation of Retrieval Augmented Generation (RAG) for document question answering.

## Overview

This project implements a RAG pipeline that:
- Retrieves relevant information from documents
- Uses Cohere for embeddings and language model capabilities  
- Leverages Google LLMs
- Provides accurate answers to queries based on document content

## Requirements

- Python 3.7+
- Cohere API key
- Google API key

## Environment Setup

1. Clone the repository
2. Set up environment variables:
```bash
export COHERE_API_KEY="your-key-here"
export GOOGLE_API_KEY="your-key-here"

## Features
Use the cosine similarity function to fetch the similarity between data