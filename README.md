# Pdf-Summarizer


PDF Summarizer + Q/A Chatbot using Google Gemini API
A Streamlit web app that lets you:

✅ Upload any PDF
✅ Get an AI-generated summary of its content
✅ Ask questions — AI answers strictly based on the generated summary
✅ Built using Google Gemini 1.5 API, PyMuPDF, and Streamlit — runs on Google Colab with public access link via LocalTunnel.

🚀 Features
PDF Upload: Easily upload any PDF document.

Automatic Summarization: Summarizes the entire PDF using Gemini 1.5 Flash model.

Q/A Chatbot: Ask questions and get answers based only from the summarized content — no external info.

Streamlit Interface: Clean and simple web-based UI.

Google Colab Compatible: Fully runs in Colab — no local setup needed.

Free-Tier Friendly: Designed to reduce Gemini API usage (only summary + 1 answer per query).

🛠️ Technologies Used

| Technology                 | Purpose                         |
| -------------------------- | ------------------------------- |
| **Python 3.11+**           | Main language                   |
| **Google Gemini API (v1)** | Text summarization & Q/A        |
| **PyMuPDF (fitz)**         | PDF text extraction             |
| **Streamlit**              | Web interface                   |
| **LocalTunnel / PyNgrok**  | Public URL generation for Colab |
