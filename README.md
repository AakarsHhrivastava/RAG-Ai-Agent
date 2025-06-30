# 📚 RAG-Based Knowledge Agent (n8n + OpenAI + Pinecone)

This agent uses Retrieval-Augmented Generation to provide accurate, real-time answers from uploaded documents.

## 💡 What It Does
- Takes real-time user queries as input (chat trigger)
- Retrieves relevant data from Pinecone (vector database)
- Uses OpenAI’s GPT model to generate context-aware answers
- All built inside n8n using nodes like memory, vector search, and prompt blocks

## 🧰 Tools Used
- n8n
- OpenAI API (ChatGPT)
- Pinecone (Vector DB)
- Google Drive (Document input)

## ⚙️ How To Run
1. Import `` into your n8n instance.
2. Replace credentials (OpenAI, Pinecone, Google Drive).
3. Trigger the chat input node and test it!

## 📸 Screenshot
![Screenshot 2025-06-25 004800](https://github.com/user-attachments/assets/ce067096-970c-4530-b31b-dbc4dfd131cb)
![Screenshot 2025-06-25 004717](https://github.com/user-attachments/assets/5abb8fc0-e2cf-423e-83b6-080f9bfbb455)


## 📂 File
- `rag-workflow.json`: Exported n8n workflow for the project.
