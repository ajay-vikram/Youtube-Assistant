# Youtube Assistant
LLM-based YouTube Assistant for answering video-related questions. Users can ask questions about specific YouTube videos, and the assistant will provide relevant answers.

## Cohere

The code uses the CohereEmbeddings model ("embed-english-light-v3.0") for generating embeddings and Cohere LLM API for generating text based on the query.

## Running it locally

Install the required packages:

```bash
pip install -r requirements.txt
```
Set Cohere API key in a .env file:

```
COHERE_API_KEY=your_api_key_here
```

Run the streamlit app:

```bash
streamlit run youtube_assistant.py
```

![YouTube Assistant App](/Youtube-Assistant.png)


