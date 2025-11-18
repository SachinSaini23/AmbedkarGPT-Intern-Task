# AmbedkarGPT-Intern-Task


This project is a simple command-line RAG system that answers questions using the provided Ambedkar speech text.

Features
- Text loading
- Chunking
- Embedding with all-MiniLM-L6-v2
- ChromaDB vector store
- Retrieval-based QA
- LLM using Ollama (Mistral 7B)


# Setup Instructions

Create Virtual Environment
python -m venv venv
source venv/bin/activate # Mac/Linux
venv\Scripts\Activate.ps1 # Windows

Install Dependencies
pip install -r requirements.txt

Install Ollama
ollama pull mistral

Run the Script
python main.py # normal run
python main.py --rebuild

