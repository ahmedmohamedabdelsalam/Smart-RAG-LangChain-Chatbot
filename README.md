# Smart-RAG-LangChain-Chatbot

## Project Overview

Large Language Models (LLMs) are powerful but may generate outdated or incorrect information as they are trained on static data. This project implements a Retrieval-Augmented Generation (RAG) chatbot using LangChain, powered by OpenAI, Google Generative AI, and Hugging Face APIs. Users can upload documents in txt, pdf, CSV, or docx formats and interact with the data. Relevant documents are retrieved and sent to the LLM along with user queries for accurate responses.

The system includes components from document loading to conversational retrieval chain and provides a user interface using a Streamlit application.

## Features

- Multi-source document support (txt, pdf, CSV, docx)
- Real-time interactive chatbot using RAG
- Integration with OpenAI, Google Generative AI, and Hugging Face APIs
- Semantic search and vector database (Chroma) for accurate answers
- User-friendly interface with Streamlit

## Installation

This project requires Python 3 and the following libraries:
`langchain`, `langchain-openai`, `langchain-google-genai`, `chromadb`, `streamlit`

Full dependencies are listed in `requirements.txt`.

## Instructions

1. Create a virtual environment: `python -m venv langchain_env`
2. Activate the virtual environment: `.\langchain_env\Scripts\activate` on Windows or `source langchain_env/bin/activate` on Mac/Linux.
3. Navigate to project directory: `cd Smart-RAG-LangChain-Chatbot`
4. Install dependencies: `pip install -r requirements.txt`
5. Start the app: `streamlit run RAG_app.py`
6. In the sidebar, select the LLM provider (OpenAI, Google Generative AI, or Hugging Face), choose the model, adjust parameters, and enter your API keys.
7. Create or load a Chroma vectorstore.
8. Chat with your documents and get AI-generated answers.

## Notes

- Users can add their own documents for chat interactions.
- The project is designed for educational and portfolio purposes.
- No sample data is required to run the chatbot; the `data/` folder can remain empty.

## Author

Developed by Ahmed Mohamed Abdelsalam.

## License

This project is open for personal and educational use. Modify and use freely for your own projects.
