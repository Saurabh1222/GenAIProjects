# 🤖 GenAI PDF Question-Answering (RAG App)

This project is a simple **Retrieval-Augmented Generation (RAG)** pipeline that allows you to **ask questions from a PDF document**, and get smart answers using **MiniLM embeddings + Flan-T5 LLM** — all without needing a GPU.

---

## 🧠 How it Works

1. 📄 **Read a PDF**
2. ✂️ **Split it into chunks**
3. 🔍 **Create vector embeddings** using `all-MiniLM-L6-v2`
4. 🧊 **Store in FAISS** (vector database)
5. ❓ **Query with a question**
6. 💬 **Get an answer** from a small LLM (`flan-t5-base`)

---

## 📁 Project Structure

```bash
.
├── GenAI_QA_Project.ipynb    # Main notebook (can export as .py)
├── README.md                 # This file
└── GenAI_QA_Project_Interview_Questions.pdf  # Your input file
```
---

## 📌 Notes

- This version uses **Flan-T5** (*fast, light, free*) — ideal for basic Q&A tasks.
- You can later upgrade to more advanced models like **Mistral**,


