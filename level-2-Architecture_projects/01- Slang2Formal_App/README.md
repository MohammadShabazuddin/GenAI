### Slang2Formal-App

This project is a Streamlit app that allows users to re-write text in different tones and dialects. Users input their text, select a tone (formal or informal), and choose an English dialect (American or British). The app uses OpenAI's language models via LangChain to process the input, re-writing the text according to the specified tone and dialect. A customizable prompt is used to guide the model in rephrasing the text while maintaining context. The app ensures the input text is within a 700-word limit and requires the user’s OpenAI API key for functionality.

### How to run? Use python = 3.11

1. conda create -n llmapp python=3.11 -y

2. conda activate llmapp

3. pip install -r requirements.txt

4. streamlit run main.py

