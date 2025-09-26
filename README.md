⚖️ Personal AI Legal Assistant with CrewAI
A powerful multi-agent AI system built with CrewAI that assists with legal research, IPC section identification, precedent analysis, and legal document drafting for Indian law.

🎯 Project Overview
This project creates an intelligent legal assistant that can:

Understand & Classify legal issues from plain English descriptions

Research IPC Sections using vector database search

Find Legal Precedents through web search and analysis

Draft Legal Documents with professional formatting

✨ Key Features
🤖 4 Specialized AI Agents working in orchestrated workflow

🔍 Custom RAG Tools for IPC section search via ChromaDB

🌐 Web Search Integration for legal precedent research

📄 Document Generation with formal legal structure

💻 Streamlit Interface for easy user interaction

🔧 Multi-LLM Support (Groq, OpenAI, local models)

🏗️ System Architecture
text
User Input → Case Intake Agent → IPC Section Agent → Legal Precedent Agent → Document Drafting Agent → Final Output
              ↓                    ↓                   ↓                      ↓
           Classify Issue    →  Vector Search    →   Web Search       →   Generate Document
🛠️ Tech Stack
Framework: CrewAI for multi-agent orchestration

LLMs: Groq (Llama 3.3 70B), OpenAI GPT-4, or local models

Vector DB: ChromaDB for IPC section storage and retrieval

Search: Tavily API for legal precedent research

Frontend: Streamlit for web interface

Embeddings: Sentence Transformers (all-MiniLM-L6-v2)

📋 Prerequisites
Python 3.8+

Git

API Keys for:

Groq (recommended) or OpenAI

Tavily (for web search)

🚀 Quick Start
1. Clone Repository
bash
git clone https://github.com/yourusername/ai-legal-assistant-crewai.git
cd ai-legal-assistant-crewai
2. Create Virtual Environment
bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts
