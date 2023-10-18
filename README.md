# AI-Wizards

# Wiki Chatbot

**Wiki Chatbot** is a Streamlit-based application that allows users to input a Wikipedia URL, retrieve text data from Wikipedia using Wikipedia API, and then use the OpenAI API to create a conversational AI chatbot based on the retrieved data. The chatbot can answer questions related to the text data from the given Wikipedia URL.

## Features

- User-friendly web interface using Streamlit for interaction.
- Retrieve and process text data from a Wikipedia URL.
- Utilize OpenAI API to create a question-answering chatbot based on the processed data.
- Display chat history in a chat-like format, with the user and AI responses shown accordingly.

## How to Use

1. Clone the repository to your local machine.

```bash
git clone add-the-https-link-of-the-git-repository
cd Wiki_ChatBot
```

2. Install the required dependencies.

```bash
pip install -r requirements.txt
```
3. Create a .env file in the project directory and add your OpenAI API key.
```bash
OPENAI_API_KEY=your_openai_api_key_here
```
4. Run the Streamlit app.
```bash
streamlit run app.py
```

## Requirements
* Python 3.7 or higher
* OpenAI API key (Sign up and get your API key from OpenAI)

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Credits
This project was inspired by the Streamlit and OpenAI platforms.
