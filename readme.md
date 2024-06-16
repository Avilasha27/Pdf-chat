# Chat with Multiple PDFs

This project utilizes Streamlit to create a web application that allows users to chat about multiple PDF documents using language models and embeddings.

## Installation

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_directory>
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the application:
   ```bash
   streamlit run app.py
   ```

2. Upload PDF documents:
   - Upload your PDF documents using the file uploader.
   - Click on the "Process" button to initiate document processing.

3. Chat with the application:
   - Enter your questions about the uploaded documents in the text input field.
   - The application will generate responses using language models and display them in a conversation format.

## Features

- **PDF Processing**: Extracts text from uploaded PDF documents using PyPDF2.
- **Text Segmentation**: Splits extracted text into manageable chunks using CharacterTextSplitter.
- **Embeddings**: Utilizes CohereEmbeddings to generate embeddings for text chunks.
- **Conversation Model**: Uses ChatGroq for conversational AI based on document content.
- **Memory**: Integrates ConversationBufferMemory to maintain chat history.
- **User Interface**: Streamlit provides a user-friendly interface for interaction.

## Dependencies

- Streamlit
- PyPDF2
- langchain_text_splitters
- langchain_cohere
- langchain_community
- langchain_groq

## License

This project is licensed under the [MIT License](LICENSE).

---
