# RAG-based-Question-Answering-System
This project implements a basic Retrieval-Augmented Generation (RAG) model, which allows users to input a URL, process the content found on that webpage, and then ask relevant questions about it. The system uses RAG techniques to combine the power of information retrieval with the generative capabilities of large language models (LLMs), providing answers directly based on the extracted content from the given URL.

Key Features:
Input: A URL is provided as input, from which the system retrieves relevant content for processing.
Question Answering: After processing the content, the system generates relevant answers to any questions posed about the material found in the URL.

Technologies Used:
ChatGroq and Llama model for language generation.
Langchain to facilitate the chaining of prompts and memory management across interactions.
FAISS (Facebook AI Similarity Search) for efficient retrieval and embedding-based search of relevant content.

This project demonstrates the integration of state-of-the-art technologies in LLMs and retrieval systems to enhance the accuracy and relevance of generated responses based on external data sources.

Feel free to explore the code and contribute to further improvements!
