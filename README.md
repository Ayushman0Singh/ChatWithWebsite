# Chat with a Website from URL - LangChain Chatbot with Stream-lit GUI
___
Welcome to the GitHub repository for the LangChain Chatbot with Streamlit GUI! This project is a comprehensive guide to building a chatbot capable of interacting with websites, extracting information, and communicating in a user-friendly manner. It leverages the power of LangChain 0.1.0 and integrates it with a Streamlit GUI for an enhanced user experience.
# Features
___
- Website Interaction: The chatbot uses the latest version of LangChain to interact with and extract information from various websites.
- Large Language Model Integration: Compatibility with models like GPT-4, Mistral, Llama2, and ollama. In this code I am using GPT-4, but you can change it to any other model.
- Streamlit GUI: A clean and intuitive user interface built with Streamlit, making it accessible for users with varying levels of technical expertise.
- Python-based: Entirely coded in Python.
___
# Brief explanation of how RAG works
A RAG bot is short for Retrieval-Augmented Generation. This means that we are going to "augment" the knowledge of our LLM with new information that we are going to pass in our prompt. We first vectorize all the text that we want to use as "augmented knowledge" and then look through the vectorized text to find the most similar text to our prompt. We then pass this text to our LLM as a prefix.

![image](https://github.com/Ayushman0Singh/ChatWithWebsite/assets/99126946/6cf90f1d-cb95-4561-8a99-b6163d0c536e)

# Installation

Clone this repository
 ```python
git clone [repository-link]
cd [repository-directory]
```

Install the required packages:
```python
pip install -r requirements.txt
```

Create your own .env file with the following variables:
```pyhton
OPENAI_API_KEY=[your-openai-api-key]
```

# USage
___
```python
streamlit run app.py
```

**Note:** This project is for educational and research purposes. Ensure to comply with the terms of use and guidelines of the utilized APIs and services.
