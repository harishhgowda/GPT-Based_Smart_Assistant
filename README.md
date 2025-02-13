# GPT-Based Smart Assistant
Create an interactive voice-controlled assistant using OpenAI's GPT model. Convert speech to text process.

## Overview
GPT-Based Smart Assistant is a voice-controlled AI assistant leveraging OpenAI's GPT model to process and respond to user queries in natural language. It enhances user interaction by enabling seamless speech recognition and text-to-speech conversion.

## Features
- Captures voice commands and converts speech to text
- Processes queries using OpenAI's GPT API
- Converts responses back into speech for intuitive interaction
- Supports general queries and web browsing commands

## Workflow
![Project Workflow](Screenshot%20(176).png)
1. Capture audio command from the user
2. Convert speech to text
3. Process text using the ChatGPT API
4. Convert response to speech
5. Read out the response

## Project Structure
- `app.py` - Main script handling speech recognition, text processing, and text-to-speech conversion.
- `apikey.py` - Stores API key (ensure to keep it secure and do not expose it publicly).

## Requirements
Ensure you have the following dependencies installed:
```bash
pip install openai speechrecognition pyttsx3
```
## Usage
Run the script:
```
python app.py
```
Give voice commands, and the assistant will respond accordingly. Say "bye" to terminate the session.

## Security Notice

Make sure to keep your OpenAI API key secure and avoid sharing it in public repositories.
