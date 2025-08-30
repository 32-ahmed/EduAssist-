# EduAssist-
📚 Telegram RAG Bot – PDF Question Answering & Summarization

This project is a Retrieval-Augmented Generation (RAG) bot for Telegram that can:

📄 Read PDF files and extract text.

🧠 Store and search relevant information using FAISS vector search.

❓ Answer user questions based on the extracted content.

✍️ Summarize documents into concise bullet points.

🚀 How It Works

Upload a PDF to the Telegram bot.

The bot extracts and chunks the text.

Text is converted into vector embeddings for fast semantic search.

When you ask a question, the bot:

Retrieves the most relevant chunks.

Uses a Flan-T5 model to generate an accurate answer.

You can also request a summary of the whole document.

🛠 Tech Stack

Python

Hugging Face Transformers (Flan-T5)

Sentence Transformers (for embeddings)

FAISS (vector search)

pdfplumber & PyPDF2 (PDF text extraction)

Telegram Bot API

📌 Example Use Cases

Quickly find answers inside research papers or books.

Summarize meeting minutes or reports.

Chat with long documents directly on Telegram.
