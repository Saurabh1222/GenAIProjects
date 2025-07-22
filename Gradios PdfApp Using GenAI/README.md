# 🧠 Gradio PDF Chatbot using GenAI

Interact with any **PDF document** using **Generative AI** via a **Gradio UI**! This app lets users upload PDFs and ask questions, with smart answers powered by an embedding model and a large language model (LLM).

---

## 🚀 Features

- 📄 Upload any PDF and chat with it
- 🔍 Extracts and embeds PDF content using `SentenceTransformers`
- 🧠 Answers questions using a transformer-based LLM (google/flan-t5-base)
- 🖥️ Simple user interface using Gradio

---

## 🛠️ Tech Stack

| Component        | Tool/Library               |
|------------------|----------------------------|
| UI               | Gradio                     |
| Embeddings       | `all-MiniLM-L6-v2` (via `sentence-transformers`) |
| Vector Store     | FAISS                      |
| LLM              | google/flan-t5-base        |
| Language         | Python (Colab Notebook)  |

---

## 🙌 Acknowledgements
 - HuggingFace Transformers & Inference API
 - SentenceTransformers
 - Gradio Team
