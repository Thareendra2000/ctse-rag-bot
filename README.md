# CTSE Lecture Notes Chatbot 🤖📘

A simple chatbot built in a Jupyter Notebook using the free Gemini API to answer questions from CTSE lecture notes (PDF format).

---

## Features

- Loads lecture notes from PDF
- Splits content into manageable chunks
- Sends question + context to Gemini via REST API
- Returns answers with referenced page numbers

---

## Tech Stack

- Python 3
- Jupyter Notebook
- `google-generativeai` (API client)
- `requests`, `dotenv`, `langchain` (for PDF handling)

---

## Folder Structure

```

ctse-chatbot-gemini/
├── ctse\_chatbot.ipynb
├── 2023-S1-SE4020-Lecture-03-Functions.pdf
├── .env
├── requirements.txt
├── report/report.pdf
├── demo/ctse\_chatbot\_demo.mp4

````

---

## Setup Instructions

1. Create and activate virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # Windows: venv\Scripts\activate
````

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Add your Gemini API key to a `.env` file:

   ```
   GOOGLE_API_KEY=your-api-key-here
   ```

4. Launch Jupyter Notebook and run `ctse_chatbot.ipynb`

## 👤 Author

**Thareendra Tennakoon**
SE4010 – Semester 1, 2025
SLIIT
