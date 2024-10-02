# chat-bot
Speech-Based Assistant

# Speech-Based Assistant
This project is a Python-based voice assistant that uses Speech Recognition to understand user queries and responds using Text-to-Speech (TTS). It also employs fuzzy matching to determine the best possible answer for user questions.

# Features
Converts speech to text using the Google Speech Recognition API.
Responds to questions using text-to-speech (TTS) with pyttsx3.
Fuzzy matching via fuzzywuzzy to match user queries with predefined answers.
Handles multiple queries and gracefully exits on user request.
Prerequisites
Before you begin, ensure you have the following installed on your machine:

# Python 3.x
pip (Python package installer)
Required Libraries
The project depends on the following Python libraries:

# SpeechRecognition
pyttsx3
fuzzywuzzy
pyaudio

# Example Queries
Here are some example queries that the assistant can understand:

"How can I update my profile details?"
"How do I add my recent achievements or collaborations?"
"Can I hide certain information on my profile?"
The assistant responds based on a predefined dictionary of questions and answers. If the question is not in the dictionary, it will respond with a default message.

# Conversation Flow
The assistant greets you and asks how you are doing.
You can ask a question or respond with small talk like "I am fine, what about you?".
The assistant will respond based on your query.
You can continue asking questions or say "no" to exit the conversation.
Customization
You can add more questions and answers by editing the qa_pairs dictionary in main.py. Example:


