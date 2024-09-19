📦 Dependencies
Python 3.7+
Streamlit: Interactive UI framework for Python
Groq: API for interacting with LLAMA 3.1
You can find the list of all required packages in the requirements.txt file.

✨ Usage
Once the app is running, enter your query in the input field provided.
The chatbot, powered by LLAMA 3.1, will respond to your messages and maintain a conversation history.
Responses are fetched from the Groq API.
🔧 Customization
API Key: The Groq API key is stored in the config.json file. Ensure you have a valid key for the API calls.
Model: The model used (llama-3.1-8b-instant) can be changed in the main.py script to use a different variant, depending on your Groq account.
