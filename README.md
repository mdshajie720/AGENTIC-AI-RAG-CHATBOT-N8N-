🤖 N8N RAG Chatbot Model
 AI-powered chatbot built using n8n, Google Gemini, and Pinecone with Retrieval-Augmented Generation (RAG) — all free and open-source.

<div align="center"> <img src="Screenshot 2025-07-09 144526.png" alt="Architecture Diagram" width="600"/> </div>

<div align="center"> <img src="Screenshot 2025-07-09 144548.png" alt="Architecture Diagram" width="600"/> </div>
🧠 What Is It?
Build your own intelligent Q&A chatbot that can search and answer from your documents, using a combination of:

Google Gemini for text embeddings & generation

Pinecone for storing and retrieving knowledge

Google Drive for document storage

n8n to connect everything — no coding required

🔍 Key Features
💬 No-code Chatbot built on n8n AI Agent

🧠 Uses Google Gemini Embeddings + Chat Model

📂 Supports PDF documents from Google Drive

🔗 Stores knowledge using Pinecone Vector DB

🧠 Includes Simple Memory for improved context

📚 Built on RAG (Retrieval-Augmented Generation)

✅ Fully customizable, extendable, and open-source

🧰 Tech Stack
Tool	Role
n8n	Workflow automation engine
Google Gemini	Embeddings and generative AI
Pinecone	Vector database for long-term storage
Google Drive	Document source (PDFs, Docs, etc.)

🚀 How It Works
📂 Upload your documents to Google Drive.

🔄 The n8n workflow pulls files using the Google Drive node.

📃 Documents are split into chunks (Recursive Character Splitter).

🧬 Chunks are embedded via Google Gemini.

📥 Vectors are stored in Pinecone under a specific namespace.

💬 When a user sends a message:

Simple Memory keeps the conversation in context.

Relevant chunks are retrieved from Pinecone.

Gemini generates an accurate and human-like response.

🧪 Sample Use Case
User: Who is shajie?

Bot: Shajie is an aspiring  Data Engineer and Data Analyst who has hand on experience in EDA,Machine Learning,Gen AI,LLMS and Agentic AI

🛠️ Setup Instructions
🔁 Clone or import the workflow into your n8n instance.

🔑 Configure the required credentials:

Google Drive OAuth

Google Gemini API

Pinecone API Key

📤 Upload your documents to Google Drive.

🔧 (Optional) Update the file ID in the Google Drive node.

▶️ Activate the workflow.

🧪 Start chatting with your agent using the Chat Trigger or Webhook.

🧠 System Prompt
The agent uses a custom system prompt that encourages natural and human-like responses, avoiding robotic repetition and maintaining conversational flow.

📎 Resources
📘 n8n Documentation

🧠 Google Gemini API

🧲 Pinecone Documentation

🏷️ Tags
n8n • AI Agent • RAG • Gemini • Pinecone • Chatbot • Vector DB • Knowledge Base • No-Code • Automation

📜 License
This project is licensed under the MIT License.
Built with ❤️ using n8n and AI.