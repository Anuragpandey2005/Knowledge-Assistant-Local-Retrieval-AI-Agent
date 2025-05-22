# Knowledge-Assistant-Local-Retrieval-AI-Agent

# 🦊 FOXO Knowledge Assistant – Local RAG AI Agent

A fully offline Retrieval-Augmented Generation (RAG) AI agent that answers questions using local documents (`.txt`, `.md`, `.pdf`) without requiring any OpenAI API. Built using FAISS, Sentence-Transformers, and Hugging Face Transformers, the agent runs entirely on your local machine or in Google Colab.

---

## 🚀 Features

- 📄 Ingests and indexes local `.txt`, `.md`, and `.pdf` files
- 🧠 Uses Sentence-BERT (`all-MiniLM-L6-v2`) for semantic search
- ⚡ Fast vector search via FAISS
- 🤖 Local answer generation using Hugging Face Transformers (GPT-2)
- 🧮 Multi-tool mode (e.g., calculator)
- 💻 CLI interface (easy to use and test)

📝 Sample Questions
You: What does the a.txt file say?
Assistant: Hello world

You: Show me the content in the PDF file.
Assistant: This is PDF content.



