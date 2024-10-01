# RAGXiv: Retrieval Augmented Generation Chatbot

## Project Overview
**RAGXiv** is a Retrieval Augmented Generation (RAG) chatbot designed to help users ask domain-specific research questions and retrieve answers from relevant literature on arXiv. The project leverages **Hugging Face Sentence Transformers** for context retrieval and **GPT-4** for generating coherent, detailed responses based on the most relevant papers. The user interface is built with **Streamlit**, allowing for a smooth and intuitive user experience.

## Features
- **Dynamic UI with Streamlit:** A clean and interactive interface that displays the most relevant arXiv paper abstracts in response to user queries.
- **Top-k Retrieval of Papers:** Uses Sentence Transformers to retrieve and rank the top-k relevant papers based on the user's question.
- **Integration with GPT-4:** Generates detailed answers to the user's questions by synthesizing information from the top-k retrieved papers.
- **arXiv Links:** Each abstract displayed in the UI includes a direct link to its respective arXiv publication, enabling users to explore the source literature further.

## Tech Stack
- **Python:** Core programming language for backend logic and integration.
- **Streamlit:** For building an interactive user interface to display retrieved abstracts and responses.
- **LangChain:** Helps with managing LLM-based pipeline tasks, including context retrieval and question answering.
- **Hugging Face Sentence Transformers:** Used for embedding paper abstracts and performing semantic search.
- **Git:** Version control for tracking development progress and collaboration.

## Let's Start! 🕹️

1. **Input your research question**: 
  <img src="blank.png" alt="RAGXiv Platform" width="400">
  <img src="enter_question.png" alt="User Input" width="400">
  
2. **Submit your question**: 
  <img src="answer1.png" alt="Abstracts" width="400">
  <img src="answer2.png" alt="Abstracts" width="400">
  
3. **Read the retrieved abstracts**: 
