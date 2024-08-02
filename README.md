# AI Chatbot with Streamlit, Gemini, Speech Recognition, and Text-to-Speech

## Overview
This Python script creates a chatbot interface using Streamlit. It leverages the Gemini language model for generating responses, speech recognition for voice input, and text-to-speech for audio output.

## Key Features
- **Text-based interaction**: Users can input text queries.
- **Voice input**: Users can provide input through voice commands.
- **Speech output**: The chatbot can provide spoken responses.
- **Gemini integration**: Uses the Gemini language model for generating human-like text.
- **Error handling**: Includes basic error handling for API calls, speech recognition, and text-to-speech.

## Dependencies
- streamlit
- os
- google.generativeai
- speech_recognition
- pyttsx3

## Setup
1. Replace `'YOUR_API_KEY'` with your Google API key.
2. Install required libraries using:
    ```sh
    pip install streamlit os google-generativeai speech_recognition pyttsx3
    ```

## Usage
1. Run the script using:
    ```sh
    streamlit run your_script.py
    ```
2. Interact with the chatbot by typing text or using voice input.

**Note**: Requires a Google Cloud Platform project with the Generative AI API enabled and an API key.

## Additional Considerations
- Consider enhancing error handling for a more robust application.
- Explore additional features like conversation history or user authentication.
- Optimize the code for performance and efficiency.

This summary provides a concise overview of the code's functionality, dependencies, setup, and usage.
