# Generative AI Fundamentals

## 1. Large Language Models (LLMs)
LLMs are deep learning algorithms that can recognize, summarize, translate, predict, and generate content using very large datasets.
*   **Transformer Architecture:** The backbone of most modern LLMs, utilizing "attention" mechanisms to understand context.
*   **Tokens:** The basic units of text processed by an LLM (words or parts of words).

## 2. Retrieval-Augmented Generation (RAG)
RAG is a technique used to give an LLM access to data it wasn't trained on.
*   **Process:** Retrieve relevant documents from an external database -> Feed them to the LLM as context -> Generate a grounded answer.
*   **Benefit:** Reduces "hallucinations" and provides up-to-date information.

## 3. Fine-Tuning
The process of taking a pre-trained model and training it further on a smaller, specific dataset.
*   **Purpose:** To make the model specialized in a particular domain (e.g., medical, legal, or a specific brand voice).

## 4. Embeddings & Vector Databases
*   **Embeddings:** Numerical representations of text that capture semantic meaning.
*   **Vector DBs:** Specialized databases (like Pinecone or Weaviate) that store and search these embeddings for fast retrieval.
