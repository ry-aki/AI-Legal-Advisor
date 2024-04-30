

# AI-Powered Legal Counsel

The project leverages advanced AI through Meta's Llama-7B-chat model and Langchain to provide real-time legal advice. Designed with a Streamlit-based UI, it offers an accessible and user-friendly platform for legal queries.

## Project Description

This project aims to simplify legal consultations by providing a reliable AI-driven chatbot that can interpret and respond to user queries with accurate legal advice. By processing extensive legal documents and employing cutting-edge NLP models, it ensures high-quality, context-aware responses.

## Features

- **Real-time legal advice:** Quick responses to legal queries.
- **User-friendly interface:** Easy-to-navigate frontend built with Streamlit.
- **Extensive legal knowledge base:** Uses a rich dataset of legal documents.


## Working

1. **Data Ingestion:**
   - Legal documents are added to the `dataset` folder and processed by `ingest.py`, which extracts text and converts it into numerical vectors stored in `/vectorstore`.
   
2. **Chatbot Functionality:**
   - `app.py` initializes the Streamlit UI and handles user interactions.
   - When a query is received, it is passed to the Langchain integrated Llama-7B-chat model.
   - The model processes the query using the vectorized knowledge base to generate accurate legal advice, which is then displayed to the user.



---