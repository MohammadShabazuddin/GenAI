### Blog Post Generation Application

This project is a Streamlit app that generates blog posts based on a user-provided topic. Users enter their OpenAI API key and the topic for the blog post, and the app uses OpenAI's language models to create a 400-word blog post about the topic. The post is generated in the style of an experienced startup and venture capital writer. After generating the content, the app also 
outputs the total word count of the blog post. The app ensures the user provides a valid API key before processing the request.

### How to run? Use python = 3.11

1. conda create -n llmapp python=3.11 -y

2. conda activate llmapp

3. pip install -r requirements.txt

4. streamlit run main.py


Live Website: https://blog-post-generator1.streamlit.app/
