# RAG-Powered Research Paper Assistant 📚🤖

A powerful research assistant built using Retrieval-Augmented Generation (RAG) to enhance your research paper queries and work. This app allows users to upload PDF documents or search for research papers on arXiv, store them, and retrieve relevant information to generate insightful responses to specific queries. Utilizing the power of RAG, the system can generate responses that are contextually relevant and accurate, enhancing the user's research experience.

## Features ✨

- **PDF Upload & Processing** 📄: Upload research papers in PDF format, and the system extracts the text and stores it in a knowledge base for later querying.
- **Semantic Search** 🔍: Perform semantic searches on the stored documents or arXiv search results to retrieve relevant information.
- **Query Response Generation** 📝: Based on the context retrieved from the documents, the system generates answers to your queries using a state-of-the-art language model.
- **arXiv Integration** 📚: Search for academic papers directly on arXiv, process their content, and use it for querying.

## Tech Stack 🛠️

- **Streamlit**: For building the interactive web app interface.
- **Sentence-Transformers**: For generating text embeddings and performing semantic search.
- **ChromaDB**: For persistent storage of text embeddings in the knowledge base.
- **Litellm**: For utilizing the Gemini AI model for generating responses.
- **PyPDF2**: For extracting text from PDF files.
- **langchain & langchain_community**: For text processing and arXiv search integration.
- **HuggingFace**: For managing API keys and model access.

## Prerequisites ⚡

To run this project, you'll need the following dependencies:

- Python 3.7+
- `streamlit`
- `sentence-transformers`
- `chromadb`
- `litellm`
- `PyPDF2`
- `langchain`
- `langchain_community`
- `huggingface_hub`
- `dotenv`

You can install them using `pip`:

```bash
pip install streamlit sentence-transformers chromadb litellm PyPDF2 langchain langchain_community huggingface_hub python-dotenv
