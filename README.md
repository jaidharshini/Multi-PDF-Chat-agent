# Multi-PDF-Chat-agent
The Multi-PDF's Chat Agent is a Streamlit-based web application designed to facilitate interactive conversations with a chatbot. 

📝 Overview
Multi-PDFs Chat Agent is a Streamlit-based web application that enables users to chat with multiple PDF files.
It extracts text from uploaded PDFs, builds a searchable knowledge base, and powers real-time conversations using generative AI.

🎯 How It Works
Workflow:

PDF Loading: Upload and extract text content from multiple PDF documents.

Text Chunking: Split extracted text into manageable chunks for better processing.

Embeddings Generation: Convert text chunks into vector embeddings using an AI model.

Similarity Search: Match your questions with relevant content chunks.

Response Generation: Generate accurate, context-aware answers using the selected content.

🔥 Key Features
Adaptive Chunking: Sliding Window Chunking dynamically balances fine and coarse-grained data access.

Multi-Document QA: Supports both simple and multi-hop queries across multiple documents.

Flexible File Support: Upload both PDF and TXT files.

LLM Compatibility: Works with Google Gemini Pro, OpenAI GPT-3, Anthropic Claude, Llama 2, and other open-source models.

🌟 Requirements
Streamlit: Build interactive web apps easily.

google-generativeai: Utilize Google's generative AI capabilities.

python-dotenv: Manage sensitive API keys and configs securely.

LangChain: Powerful tools for conversational retrieval and language tasks.

PyPDF2: Extract and manipulate PDF files.

FAISS (CPU version): Fast similarity search for dense vector embeddings.

langchain_google_genai: Integration of LangChain with Google Generative AI SDK.

▶️ Installation
Clone the Repository:

bash
Copy
Edit
git clone https://github.com/GURPREETKAURJETHRA/Multi-PDFs_ChatApp_AI-Agent.git
Install Dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Set Up Environment Variables:

Get your Google API Key from MakerSuite.

Create a .env file in the project root:

ini
Copy
Edit
GOOGLE_API_KEY=<your-api-key-here>
Run the Application:

bash
Copy
Edit
streamlit run app.py
💡 Usage
Launch the app using Streamlit CLI.

Use the sidebar to upload one or more PDF or TXT files.

Click "Submit & Process" to extract and prepare the documents.

Start chatting! Enter your questions in natural language and get instant responses based on the uploaded documents.

Demo:
You can also visualize the application via the Streamlit Cloud deployment. (Demo visualization only.)

📢 Highlights
Real-time Q&A with multiple PDFs.

Supports document summarization, content retrieval, and deep multi-hop querying.

Easy to customize and integrate with other LLMs and vector databases.

📜 License
Distributed under the MIT License. See the LICENSE file for more details.

⭐ Transform how you interact with documents — Try the Multi-PDF ChatApp AI Agent today! 🚀
