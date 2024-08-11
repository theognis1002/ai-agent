# AI Agent - Julienne

---

A simple conversation manager that uses a language model, Deepgram for speech-to-text, and Text-To-Speech to interact with users.

### Features

- Uses a language model to generate responses to user input
- Utilizes Deepgram for speech-to-text using the `asynchronous live transcription` feature
- Text-To-Speech capabilities using `ffplay`

### How to Use

1. Install the required packages by running `pip install -r requirements.txt`
2. Copy `.env.sample` -> `.env` and set third-party API keys
3. Run the code using `python main.py`

### Parameters

- `GROQ_API_KEY` - Your Groq API key
- `DEEPGRAM_API_KEY` - Your Deepgram API key
- `system_prompt.txt` - The system prompt used by the language model

### Limitations

- The language model used is a simple chatbot and may not be able to understand complex sentences or follow conversations for a long time.
- Deepgram may require additional setup and configuration for your specific use case.
- Text-To-Speech capabilities are based on `ffplay` and may not work on all systems.
