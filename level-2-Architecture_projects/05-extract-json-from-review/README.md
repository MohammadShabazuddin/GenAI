### Key Data Extraction from Product Reviews

This Streamlit app extracts key information from product reviews using OpenAI's language models via LangChain. Users input their OpenAI API key and provide a product review, and the app analyzes the review to extract three key data points: sentiment (positive, negative, or neutral), delivery time (in days), and price perception (expensive, cheap, or neutral). The app processes the review and displays the extracted information in a bullet-point format. It ensures the review doesn't exceed 700 words and provides a simple interface for users to efficiently gather insights from customer feedback.

### How to run? Use python = 3.11

1. conda create -n llmapp python=3.11 -y

2. conda activate llmapp

3. pip install -r requirements.txt

4. streamlit run main.py


Live Project: https://reviewai.streamlit.app/
