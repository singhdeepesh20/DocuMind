DocuMind — Talk to Your Documents
Interact with your PDFs, text files, and knowledge sources like never before.
Powered by LangChain, FAISS, and LLMs, DocuMind lets you chat with your documents to extract insights, summarize, and answer questions instantly.

📌 Overview
DocuMind is an AI-powered document assistant that transforms static documents into interactive knowledge bases.
Simply upload your documents, and DocuMind will allow you to ask questions in natural language and receive context-aware, accurate responses.

✨ Features
📄 Multi-Document Support — Upload multiple PDFs or text files.

🧠 LangChain + FAISS — Intelligent chunking and fast vector search.

🔍 Context-Aware Answers — Responses grounded in your document content.

⚡ Local or API LLMs — Use OpenAI, Ollama, or other supported LLMs.

🌐 Streamlit UI — Simple, interactive web interface.

🛠️ Tech Stack
Language: Python 3.10+

Frameworks: LangChain, Streamlit

Vector DB: FAISS

LLMs: OpenAI API, Ollama, or local models

Others: PyPDF2, dotenv

📂 Folder Structure
bash
Copy
Edit
DocuMind/
│
├── app.py              # Streamlit app entry point
├── requirements.txt    # Python dependencies
├── README.md           # Project documentation
├── LICENSE             # MIT License
└── data/               # Uploaded documents
🚀 Getting Started
1️⃣ Clone the Repository
bash
Copy
Edit
git clone https://github.com/singhdeepesh20/DocuMind.git
cd DocuMind
2️⃣ Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
3️⃣ Set Up Environment Variables
Create a .env file in the root directory and add:

ini
Copy
Edit
GROQ_API_KEY=your_api_key_here
4️⃣ Run the App
bash
Copy
Edit
streamlit run app.py
📊 Roadmap
 Single-document chat

 Multi-document support

 Multi-modal document support (images, tables)

 Deployment on Streamlit Cloud

🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

📜 License
This project is licensed under the MIT License — see the LICENSE file for details.


