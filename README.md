Gen AI â€“ PDF Reader with LangChain

This project demonstrates how to use **LangChain** and **Large Language Models (LLMs)** to read, process, and analyze PDF documents. It provides a simple pipeline for extracting text, asking questions, and generating summaries from PDF files.

---

## ðŸš€ Features
- ðŸ“„ Upload and process PDF documents  
- ðŸ” Extract and clean text from PDFs  
- ðŸ¤– Use LangChain + LLMs for:
  - Summarization
  - Question answering
  - Content analysis  
- âš¡ Easy to extend and customize  

---

## ðŸ› ï¸ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ANKIETAGRE/gen_ai.git
   cd gen_ai
   ```

2. Create a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Linux/Mac
   venv\Scripts\activate      # On Windows
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## ðŸ“‚ Project Structure

```
gen_ai/
â”‚â”€â”€ pdf_reader.py       # Main script for PDF processing
â”‚â”€â”€ requirements.txt    # Dependencies (rename from 'requiremnts.txt' if needed)
â”‚â”€â”€ README.md           # Project documentation
```

---

## â–¶ï¸ Usage

Run the main script:

```bash
python pdf_reader.py
```

You can customize the script to load your own PDF file and interact with it.

---

## ðŸ§© Dependencies

Core libraries used in this project:
- [LangChain](https://www.langchain.com/)
- [PyPDF2](https://pypi.org/project/PyPDF2/) or similar for PDF reading
- [OpenAI](https://platform.openai.com/) or another LLM provider

*(See `requirements.txt` for the full list.)*

---

## ðŸ“Œ Next Steps / Improvements
- Add a **Streamlit UI** for easier interaction  
- Support multiple file formats (DOCX, TXT)  
- Save conversation history for context-aware Q&A  
- Add unit tests  

---

## ðŸ“„ License
This project is licensed under the MIT License â€“ feel free to use and modify.
