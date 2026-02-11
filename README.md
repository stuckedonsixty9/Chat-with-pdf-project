# 🤖 Chat with PDF Pro

> **A powerful, AI-powered document assistant that lets you chat with your PDFs using Google Gemini 2.5 Flash.**

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-App-ff4b4b)
![Gemini](https://img.shields.io/badge/AI-Google%20Gemini-4285F4)

## 🌟 Features

-   **📄 Multi-PDF Support**: Upload multiple PDF documents at once.
-   **🧠 Advanced AI Analysis**: Uses **Google Gemini 2.5 Flash** for deep understanding of content.
-   **👁️ Vision Mode**: Handles scanned docs, handwritten notes, and tables with ease.
-   **🌍 Multi-Language Support**: Chat in **English, Hindi, or Hinglish**.
-   **⚡ Quick Actions**: One-click summaries, key concept explanation, and more.
-   **🎨 Premium UI**: A sleek, dark-themed interface built with Streamlit.

## 🚀 Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/chat-with-pdf.git
cd chat-with-pdf
```

### 2. Create a Virtual Environment (Recommended)
```bash
python -m venv .venv
# Windows
.venv\Scripts\activate
# Mac/Linux
source .venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Set up API Keys
1.  Get your **FREE** API Key from [Google AI Studio](https://aistudio.google.com/).
2.  Create a `.env` file in the root directory:
    ```env
    GOOGLE_API_KEY=your_api_key_here
    ```

## 🏃‍♂️ Usage

1.  **Run the Application**:
    ```bash
    streamlit run main.py
    ```
    *Or use the provided `run_app.bat` on Windows.*

2.  **Upload PDFs**: Use the sidebar to upload your documents.
3.  **Process**: Click "Process Documents" to initialize the AI.
4.  **Chat**: Start asking questions!

## 🛠️ Tech Stack

-   **Frontend**: [Streamlit](https://streamlit.io/)
-   **AI Model**: Google Gemini 2.5 Flash
-   **Orchestration**: LangChain
-   **Vector Store**: ChromaDB
-   **Embeddings**: HuggingFace (`all-MiniLM-L6-v2`)

## 🤝 Contributing

Contributions are welcome! Feel free to submit a Pull Request.

---
*Made with ❤️ by Raghvendra*
