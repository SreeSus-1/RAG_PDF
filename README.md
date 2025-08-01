# RAG_PDF

🗞️ Notebook: Business_news.ipynb
This notebook enables semantic search and generative Q&A over business news PDFs using LLMs, embeddings, and vector similarity techniques. It allows users to extract, embed, and interact with documents intelligently.

🧠 Core Purpose
Perform intelligent question answering on business news documents using LangChain, Pinecone, and OpenAI.

🔧 Libraries Used
OpenAI, Pinecone, LangChain, transformers, torch

PyMuPDF (fitz), faiss-cpu, scikit-learn, tiktoken, pypdf, groq

⚙️ Main Functions
extract_text_from_pdf(): Reads and extracts text from PDFs using PyMuPDF

search_documents(query): Searches for relevant chunks using vector similarity

trim_prompt(): Cleans and formats prompt inputs for LLM use

query_response(): Generates an answer based on top retrieved text

ask_bot(): Provides an interactive Q&A interface

This notebook is ideal for applying LLM-powered information retrieval to financial or business news archives.
