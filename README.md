# 🩺 RAG- Based-Medical-Chatbots
A medical chatbot using RAG with HuggingFace, FAISS, LangChain, and Streamlit. Powered by llama-2-7b-chat.Q4_K_M.gguf, a 7B dialogue-optimized LLaMA 2 model in GGUF format, it retrieves context from medical PDFs and generates accurate, AI-based answers.

---

## 🧠 About the Model

We use `llama-2-7b-chat.Q4_K_M.gguf`, a 7B parameter model from LLaMA 2—optimized for dialogue and converted to GGUF format for efficient local inference. LLaMA 2 is a family of pretrained and fine-tuned generative text models ranging from 7B to 70B parameters.

---

## ⚙️ Features

- 📄 Parse and embed medical PDF documents
- 🔍 Semantic search with FAISS
- 🧩 Modular query processing via LangChain
- 🤖 Local LLM inference using LLaMA 2 in GGUF format
- 💬 Streamlit-based chatbot interface

---

## 🧰 Tech Stack

- Python
- HuggingFace Transformers
- FAISS
- LangChain
- llama-cpp-python
- Streamlit
- Jupyter notebook (optional)

---

## 📂 Folder Structure
```.
├── data/
|   └── downloadmedicalbook.txt            # Raw text data from medical book
├── model/
│   └── instructions.txt                   # Instructions or metadata for the model
├── .gitignore                             # Git ignore file
├── LICENSE                                # MIT License
├── README.md                              # Project overview and details
├── connect_memory_with_llm.ipynb          # Notebook to connect vector memory with LLM
├── create_memory_for_llm.ipynb            # Notebook to create memory using FAISS
├── medibot.py                             # Main chatbot logic
├── requirements.txt                       # Required Python packages




