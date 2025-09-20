# Whatsapp_RAG_Bot
📜 Project Summary

This project builds a personal Retrieval-Augmented Generation (RAG) chatbot using your exported WhatsApp conversations as the knowledge base.
The goal is to let a local or cloud-hosted Large Language Model (LLM) respond to new messages in your own style by searching past chats and using them as context.

Key steps:

Chat Export & Parsing – Upload and parse the WhatsApp .txt export to extract conversation blocks (multi-message turns ending with your reply).

Semantic Embeddings – Convert each block into dense vectors using a multilingual Sentence Transformer to capture meaning (Arabic-friendly).

Vector Search (FAISS) – Store embeddings in a FAISS index for fast nearest-neighbor retrieval.

RAG Pipeline – At query time, the system retrieves the most relevant past blocks and feeds them into an LLM to generate a natural response.

Local / API Inference – Optionally run an open-source LLM (e.g., Falcon, Gemma) in Colab or call OpenAI/Hugging Face endpoints.

This enables personalized auto-responses without heavy preprocessing or strict Q/A formatting.
