# Chatify_Generative_AI_Project
In this project I work on chat with pdf documents.

# **Chat with PDF Using Chatify Gen AI Application** 🤖📚

Welcome to the **Chat with PDF Using Chatify** project! This application allows users to interact with any PDF document in a conversational way. You can upload a PDF, ask questions related to the document, and get AI-powered answers based on the document’s content. 

---

**Project Link:**  
*Add your project link here (e.g., hosted URL)*

---

## 🔧 **Getting Started**

Follow these easy steps to get the project running on your local machine:

### **Prerequisites**

- Python 3.x
- Flask
- langchain
- PyPDF2
- google-generativeai (Gemini API)
- FAISS
- dotenv

### **Install Dependencies**

Make sure you have Python 3.x installed. Then, install the required libraries by running:

```bash
pip install flask langchain PyPDF2 google-generativeai faiss-cpu python-dotenv
### Install Dependencies

Make sure you have Python 3.x installed. Then, install the required libraries using:

## SetUp .env File

Create a .env file in your project directory with the following content:

GOOGLE_API_KEY=your_google_api_key

## 🚀 Running the Project

1. **Clone the Repository**

2. **Run the App**:

   Start the chatbot by running:

   ```bash
   python app.py
   ```

   Your chatbot will now be live and ready to chat with you!
## 🤖 How It Works

The application uses **Google Gemini 2.0 Flash-Lite** to process and answer questions based on the content of a PDF document. Here's how it works:

- **User Uploads PDF:** Upload one or more PDF files to the web application.
- **Text Extraction:** The content of the PDF is extracted using PyPDF2 and split into smaller chunks.
- **Vector Store Creation:** The text chunks are embedded using Google Generative AI Embeddings and stored in a FAISS vector database.
- **User Query:** When the user asks a question, the application performs a similarity search in the vector store to find relevant text and generates an AI response based on that context.

---

## 📚 Future Improvements
While the application is functional, here are a few ways we can enhance it further:


- **Support for Multiple File Types:** Extend the app to support additional file formats like Word and Excel.
- **Advanced AI Models:** Experiment with more advanced AI models for better understanding of document context.
- **Search Features:** Add search features to allow users to browse document content before asking questions.
- **Real-time Document Processing:** Automatically update the vector store when a new document is uploaded.

---

## 🚀 Future Scope

- **Multi-Document Processing:** Enable users to upload multiple documents at once and interact with content across different PDFs.
- **Improved User Interface:** Make the UI more interactive and user-friendly for better accessibility.
- **Integration with Cloud Storage:** Allow users to upload PDFs directly from cloud storage services like Google Drive or Dropbox.
- **AI-based Summarization:** Implement summarization features to provide brief overviews of long documents.

---

## 🌍 Why Use This Chatbot?

his application helps users get quick and accurate answers from any uploaded PDF document without having to read through pages of content. It's useful for a variety of scenarios such as:

- **Research Papers:** Quickly extract key points and answers from scientific papers.
- **Manual & Guides:** Find relevant information in technical manuals without manually searching.
- **Contracts and Legal Documents:** Extract specific clauses and terms from lengthy contracts or agreements.
- **Educational Content:** Ask questions about textbooks, study materials, and learning resources.

## 👨‍💻 Tech Stack
- Python 3.x
- Flask: A lightweight framework to build the web application.
- langchain: For building and managing conversational chains.
- PyPDF2: To extract text from PDF files.
- Google Generative AI: To generate AI-based responses from document context.
- FAISS: For fast, scalable vector search to find relevant text.
- dotenv: To manage environment variables.