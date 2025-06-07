# Law-GPT
This repository contains the code for a chatbot using `Langchain` and backed by `Llama-7B-chat` by `Meta` using `Huggingface` and `Streamlit` for frontend UI.

## Table of Contents
1. [Usage](#usage)

## Usage
1. Ingesting Knowledge into the Chatbot.
    - Add your pdfs or docx files to the `dataset` folder.
    - Run the following command to ingest the knowledge into the chatbot.
    ```
    python ingest.py
    ```
    - This will create a `/vectorstore` folder which will contain the vectorized knowledge.
2. Running the Chatbot.
    - Run the following command to start the chatbot.
    ```
    python app.py
    ```
