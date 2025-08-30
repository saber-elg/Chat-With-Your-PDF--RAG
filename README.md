# 📚 Chat with Your PDF using Gemini 🤖

## Project Overview
Chat with Your PDF is an intelligent system that allows you to upload PDF documents and ask natural language questions about their content.
The application uses Google Gemini AI alongside document processing and retrieval techniques to ensure responses are accurate and relevant to the uploaded file.

## Key Features
1. 📂 Document Upload & Processing
    - Upload PDFs (or text files).
    - Extracts and processes text for analysis.

2. 💬 Natural Language Q&A
    - Ask questions in plain language.
    - Receive AI-generated answers grounded in your document.

3. 📖 Contextual Accuracy
    - Responses remain relevant to the uploaded file.
    - Uses vector-based retrieval for precise answers.

4. ⚡ Fast & Interactive
    - Powered by Streamlit for a simple web interface.
    - Real-time answers from Gemini AI.

## Tech Stack

- Streamlit → Interactive web interface.

- PyPDF2 → Extracts text from PDF files.

- LangChain → Manages conversational AI workflows.

- FAISS → Vector-based search and document retrieval.

- Google Gemini AI → Generates intelligent responses.

- dotenv → Secure environment variable management.

## 🚀 Getting Started
### Prerequisites
Make sure you have the following installed:
- Python 3.8+
- A Google API key with access to Gemini AI

### Clone the Repository
```sh
git clone <repository-url>
cd <project-directory>
```
### Install Dependencies
```sh
pip install -r requirements.txt
```

### Set Up Environment Variables
Create a **.env** file and add your Google API key:
```sh
GOOGLE_API_KEY=your_google_api_key
```
### Usage
Run the application using:
```sh
streamlit run app.py
```

## Technologies Used

- Streamlit for the web interface.

- PyPDF2 for extracting text from PDFs.

- LangChain for managing conversational AI.

- FAISS for vector-based document retrieval.

- Google Gemini AI for generating responses.

- dotenv for managing environment variables.

## Home page
![System](https://github.com/user-attachments/assets/def17790-adde-4d52-9f7a-699b1c1c241d)

## Try the App 🚀
You can try the application live at:
👉 [Chat with Your PDF](https://mbnnrjr8jgmkgzuwhbmihp.streamlit.app/)

## Contact
For questions or suggestions, feel free to reach out:

📩 medsaberelguelta@gmail.com
