# Multi-PDF-Chat-agent
The Multi-PDF's Chat Agent is a Streamlit-based web application designed to facilitate interactive conversations with a chatbot. 

# 📚 Multi-PDF-s ChatApp AI Agent 🤖

Meet MultiPDF Chat AI App! 🚀  
Chat seamlessly with multiple PDFs using LangChain, Google Gemini Pro & FAISS Vector DB with Streamlit.  
Get instant, accurate responses powered by Google's Gemini OpenSource Language Model. 📚💬  
**Transform your PDF experience today!** 🔥✨

---

## 📄 Description

The Multi-PDF's Chat Agent is a Streamlit-based web application designed to facilitate interactive conversations with multiple PDFs.  
Users can upload PDFs, extract text, and chat with an AI agent trained on this extracted content in real time.

---

## 🎯 How It Works

- **PDF Loading**: Upload and extract text from one or multiple PDF documents.
- **Text Chunking**: Split extracted text into manageable chunks for better processing.
- **Embeddings Generation**: Convert chunks into vector embeddings using an AI model.
- **Similarity Search**: Match user queries with the most relevant text chunks.
- **Response Generation**: Generate accurate, context-aware answers based on matched content.

---

## 🔥 Key Features

- **Adaptive Chunking**: Dynamically balances fine and coarse-grained text chunking.
- **Multi-Document QA**: Ask questions across one or multiple PDFs at once.
- **Flexible File Support**: Upload PDF and TXT files.
- **LLM Compatibility**: Supports Google Gemini Pro, OpenAI GPT-3, Anthropic Claude, Llama 2, and more.
- **Easy Deployment**: Streamlit-based deployment for rapid setup and use.

---

## 🌟 Requirements

- **Streamlit**: Build and deploy interactive web apps easily.
- **google-generativeai**: Use Google's powerful generative AI services.
- **python-dotenv**: Manage API keys and secrets securely.
- **LangChain**: For conversational retrieval and language tasks.
- **PyPDF2**: For PDF text extraction.
- **FAISS (CPU Version)**: Fast similarity search for dense vector embeddings.
- **langchain_google_genai**: Integration of LangChain with Google's Generative AI SDK.

---

## 🛠️ Installation

Follow these steps to set up the project:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/GURPREETKAURJETHRA/Multi-PDFs_ChatApp_AI-Agent.git
   cd Multi-PDFs_ChatApp_AI-Agent

🚀 Usage
Launch the app using the Streamlit CLI:

streamlit run app.py

Upload one or multiple PDF or TXT files via the sidebar.

Click "Submit & Process" to extract and prepare the documents.

Start chatting! Ask questions in natural language and receive answers based on your documents.

Optional: View a demo on Streamlit Cloud (only visualization purposes).

📌 Highlights
🔥 Real-time Question & Answering with multiple PDFs.

📄 Document summarization, content retrieval, and deep multi-hop querying.

🛠️ Easy integration with other LLMs and vector databases.

✨ Dynamic adaptive chunking and efficient memory usage.

🔒 Secure API Key handling with python-dotenv.

🧠 Works with Llama2, OpenAI GPT-3.5/4, Gemini Pro, and Anthropic Claude.

📜 License
Distributed under the MIT License.
See the LICENSE file for more details.
