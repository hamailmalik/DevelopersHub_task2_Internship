readme.md for task 4 
# Context-Aware Chatbot Using Retrieval-Augmented Generation (RAG)

## Objective

The objective of this project is to build a context-aware conversational chatbot capable of retrieving relevant information from uploaded documents using Retrieval-Augmented Generation (RAG).

The chatbot answers user queries based on the content of the provided knowledge base instead of relying only on pre-trained knowledge.

---

## Dataset

Custom Knowledge Base

Examples include:

- PDF documents
- Research papers
- User manuals
- Internal documentation
- Notes

---

## Technologies Used

- Python
- Google Colab
- LangChain
- FAISS
- Sentence Transformers
- Hugging Face Embeddings
- Gradio

---

##  Methodology

1. Uploaded PDF documents.
2. Loaded documents using LangChain.
3. Split documents into smaller chunks.
4. Generated embeddings using Sentence Transformers.
5. Stored embeddings in a FAISS vector database.
6. Retrieved relevant chunks based on user queries.
7. Displayed retrieved responses through a Gradio interface.

---

## Features

- Context-aware responses
- Document retrieval
- Semantic search
- Vector database
- Interactive chatbot interface

---

## Project Structure

```
Task_4_RAG_Chatbot/
│
├── Task_4_RAG_Chatbot.ipynb
├── README.md
└── requirements.txt
```

---

## Key Results

- Successfully built a Retrieval-Augmented Generation pipeline.
- Implemented semantic document search.
- Created an interactive chatbot using Gradio.
- Demonstrated document embedding and vector retrieval.

---

## Skills Gained

- Conversational AI
- Retrieval-Augmented Generation (RAG)
- LangChain
- FAISS Vector Database
- Embeddings
- Semantic Search
- LLM Applications

---

##  Author

Developed as part of the AI/ML Engineering Internship at DevelopersHub Corporation.
