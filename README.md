# voice_virtual_assistant

A simple Python script that connects to the **ElevenLabs Conversational AI API** and starts an interactive voice session with a custom prompt and greeting.  

The script:
- Loads your ElevenLabs **Agent ID** and **API Key** from environment variables.
- Configures a conversational AI agent with a personalized schedule and welcome message.
- Starts a voice-enabled conversation using the default audio interface.
- Prints the agent's responses, user transcripts, and interrupted responses to the console.

## Requirements
- Python 3.8+
- ElevenLabs Python SDK
- `python-dotenv` for environment variable loading

## Installation
```bash
pip install elevenlabs python-dotenv
