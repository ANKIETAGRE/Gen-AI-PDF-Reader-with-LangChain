# 📄 Gen AI – PDF Reader with LangChain

An intelligent PDF analysis application powered by **LangChain** and **Large Language Models (LLMs)**. This project enables users to upload PDF documents, extract and process text, generate summaries, and ask natural language questions about document content.

## ✨ Features

* 📂 Upload and process PDF documents
* 📝 Extract and clean text from PDFs
* 🤖 Generate AI-powered summaries
* ❓ Ask questions about document content
* 🔍 Perform contextual content analysis
* ⚡ Modular and easy to extend

---

## 🛠️ Tech Stack

* **Python**
* **LangChain**
* **OpenAI API** (or any supported LLM provider)
* **PyPDF2**
* **Vector Database** (optional for advanced retrieval)
* **Environment Variables** with `python-dotenv`

---

## 📁 Project Structure

```text
gen_ai/
├── pdf_reader.py         # Main script for PDF processing
├── requirements.txt      # Project dependencies
├── README.md             # Project documentation
└── .env                  # Environment variables (not included in repository)
```

---

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have:

* Python 3.10 or higher
* An API key from your preferred LLM provider

### 1. Clone the Repository

```bash
git clone https://github.com/ANKIETAGRE/gen_ai.git
cd gen_ai
```

### 2. Create a Virtual Environment

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

**Linux / macOS**

```bash
python -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure Environment Variables

Create a `.env` file in the project root and add your API key:

```env
OPENAI_API_KEY=your_api_key_here
```

---

## ▶️ Usage

Run the application:

```bash
python pdf_reader.py
```

Then:

1. Select or provide the path to a PDF file.
2. Extract and process the document text.
3. Generate summaries or ask questions about the content.
4. Review AI-generated insights.

---

## 🔄 Workflow

```text
PDF Upload
     ↓
Text Extraction
     ↓
Text Chunking
     ↓
Embeddings Generation
     ↓
Vector Storage
     ↓
Question Answering / Summarization
```

---

## 📦 Dependencies

Core libraries used in this project:

* `langchain`
* `openai`
* `PyPDF2`
* `python-dotenv`

Install all dependencies using:

```bash
pip install -r requirements.txt
```

---

## 💡 Future Improvements

* Build a user-friendly Streamlit interface
* Support additional file formats (DOCX, TXT)
* Add conversation memory for contextual Q&A
* Enable multi-document analysis
* Integrate advanced vector databases such as FAISS or Chroma
* Add unit and integration tests
* Deploy the application to the cloud

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/your-feature-name
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to the branch

```bash
git push origin feature/your-feature-name
```

5. Open a Pull Request

---


