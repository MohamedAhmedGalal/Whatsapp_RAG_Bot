# Whatsapp_RAG_Bot
🛰️ Project Summary

This project implements a local Retrieval-Augmented Generation (RAG) chatbot powered by Ollama and Hugging Face models, designed to run securely on your own machine.
Unlike typical chatbots, this one is trained to mimic my personal WhatsApp conversation style and lingo. I exported a real WhatsApp chat between myself and a friend, processed it, and used it as the knowledge base for the model.

The result is a chatbot that not only provides context-aware answers but also responds as if you’re chatting with me on WhatsApp, reflecting my tone, phrasing, and texting habits.
It can also be adapted to any custom dataset—such as PDFs, text files, or other private documents—making it a flexible, privacy-focused AI companion.

🔑 Key Features

WhatsApp Chat Ingestion: Uses an exported WhatsApp conversation as the primary dataset, enabling the bot to replicate my unique messaging style.

Document Ingestion & Chunking: Supports uploading text files, PDFs, or other documents, splitting them into manageable chunks for efficient processing.

Semantic Embeddings: Leverages Sentence Transformers to generate high-quality vector representations of text.

FAISS Vector Database: Stores and retrieves relevant text chunks with lightning-fast, similarity-based search.

LLM-Powered Q&A: Combines retrieved context with an Ollama/Hugging Face language model to generate accurate, natural, and personalized responses.

GPU-Optimized: Fully supports CUDA acceleration for faster inference when running locally.

🚀 Use Cases

Digital Twin Chatbot: Create a chatbot that communicates exactly like you, based on your own WhatsApp conversations.

Private Knowledge Assistants: Build personalized AI tools using personal chats, company data, or proprietary documents—all kept offline and secure.

Local RAG Applications: Interact with research papers, manuals, or legal documents without relying on cloud APIs.

Style-Aware AI: Train AI to mimic specific writing or texting styles for fun, entertainment, or research.
