# PDF Document Processing with LangChain and Nomic Embeddings

This project processes PDF documents using LangChain and Nomic embeddings. It loads PDFs, splits them into chunks, generates embeddings, and creates a searchable vector store for retrieval.

## Setup

### 1. Clone the Repository

git clone: (https://github.com/boeing23/WebscrapperRAG)
cd WebscrapperRAG

2. Install Dependencies
Install the required Python packages:
pip install langchain langchain-community langchain-nomic pypdf sklearn

3. Set Up API Keys
Nomic API Key: Sign up at Nomic and get your API key.

Add the API key to your environment:
export NOMIC_API_KEY="your_nomic_api_key_here"

Usage
1. Run the Script
Execute the Python script to process the PDFs and create the vector store:

python main.py

2. Query the Vector Store
The script will create a retriever that allows you to query the PDF content. For example:

retriever.invoke("What is Prompt Engineering?")
