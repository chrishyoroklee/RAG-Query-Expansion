# Query Expansion for Reducing Hallucinations in RAG-based Chatbots

This repository contains the code, data, and experiment notebook for the research project exploring the use of **Query Expansion (QE)** to reduce hallucinations in Retrieval-Augmented Generation (RAG)-based chatbots.

## Overview

This project demonstrates how **Query Expansion (QE)**, powered by Large Language Models (LLMs), can enhance the relevance of retrieved documents in RAG systems. By generating expanded queries from an original query, we leverage the LLM's ability to retrieve highly relevant chunks of information, thereby reducing hallucinations in chatbot responses.

### Key Contributions
- Utilizing query expansion to retrieve more relevant documents from a vector database.
- Improving cosine similarity relevance scores by 4%–16%.

## Features

- **Query Expansion**: Generate expanded queries using OpenAI's GPT-3.5-turbo.
- **Document Retrieval**: Retrieve relevant text chunks from a vector database using cosine similarity.
- **Visualization**: Use UMAP for visualizing document-query relationships in 2D.


## Results

The experimental results demonstrate a consistent improvement in cosine similarity scores with Query Expansion (QE). For detailed results and visualizations, refer to the results/ directory or the project report.



