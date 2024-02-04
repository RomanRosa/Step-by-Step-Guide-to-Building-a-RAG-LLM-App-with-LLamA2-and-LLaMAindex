# Step-by-Step Guide to Building a RAG LLM App with LLamA2 and LLaMAindex

<div align="center">

[![End to end RAG LLM App Using Llamaindex and OpenAI: Indexing and Querying Multiple pdf's](http://img.youtube.com/vi/f-AXdiCyiT8/0.jpg)](https://www.youtube.com/watch?v=f-AXdiCyiT8)

</div>

In this video, we will be creating an advanced RAG LLM app with Meta Llama2 and Llamaindex. We will be using the Huggingface API for using the LLama2 Model.

# 🚀 RAG System Using Llama2 With Hugging Face

This repository contains the implementation of a Retrieve and Generate (RAG) system using the Llama2 model with the Hugging Face library, developed as a part of our comprehensive guide to building advanced language model applications. 📘💻

The code was initially developed in a Google Colaboratory notebook and is designed to demonstrate the advanced capabilities of language models in processing and generating information.

Access the original Colab notebook here: [RAG System Using Llama2 With Hugging Face.ipynb](https://colab.research.google.com/drive/1HsKNhtqnoH3G2wdgr8-iN0Snj7kbCJKt)

## 🛠️ Installation Setup

Begin by installing the necessary Python packages to set up the environment:

```bash
!pip install pypdf
!pip install transformers einops accelerate langchain bitsandbytes
!pip install sentence_transformers
!pip install llama_index

🐍 Python Code Breakdown
The core script for setting up the RAG system is detailed below, outlining each step in the process:

Key Components:

📚 Loading Documents: SimpleDirectoryReader is used for loading the documents that will be indexed.

🤖 System Prompt Setup: A system prompt is defined to guide the Q&A assistant's responses.

🔍 Query Wrapper Prompt: Format the queries using SimpleInputPrompt.

🌐 Hugging Face Integration: Setup for using Llama2 model with Hugging Face API.

🧠 Embedding Model and Service Context: Establishing the embedding model and service context for processing the documents.

🔢 Index Creation and Query Engine: Building an index from the documents and setting up a query engine for response generation.

Queries and Responses:

💡 Querying the Index: The system queries the index for specific questions and prints the responses, demonstrating the RAG system's capability to retrieve and generate information based on indexed data.

🌟 Conclusion
This script encapsulates the journey from setting up the necessary environment and libraries to querying an index with a sophisticated language model. It exemplifies how to harness the power of Llama2 and Hugging Face for building a RAG system, demonstrating the advanced potential of modern language models in information processing and generation.
