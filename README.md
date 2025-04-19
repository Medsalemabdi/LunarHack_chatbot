# LunarHack_chatbot

# 🧠🎓 Smart Campus Assistant – Project Reveal

Welcome to the Smart Campus Assistant, developed as part of **Lunar Hack 1.0**. This unified platform consists of two intelligent components:

1. **Campus Navigation and Inquiry Bot**
2. **Lost-and-Found Assistant**

---

## 📌 Project Overview

This application aims to improve the daily life of students on campus by combining AI-powered tools to:
- Guide users through campus buildings and rooms.
- Provide detailed administrative procedure information.
- Efficiently handle lost and found items using smart matching.

---

## 🧭 PART 1: Navigation and Inquiry Bot

An intelligent chatbot that helps users:
- Navigate the university campus (e.g. “Where is the computer science department?”).
- Understand administrative procedures (e.g. “How do I get a student ID card?”).

### 🔧 Tech Stack
- **LLM**: LLaMA 2 / Mistral (via `transformers` or `Ollama`)
- **Embeddings**: SentenceTransformers (`all-MiniLM-L6-v2`)
- **RAG**: FAISS or Chroma for context-aware responses
- **Interface**: Python Flask or Streamlit (CLI/Web UI)

### 🧾 Sample Dataset
Administrative procedures are stored as structured dictionaries with required documents and steps. Example:

```json
{
  "Student ID Card": "Submit your enrollment certificate, a copy of your National ID, and a passport-sized photo..."
}
