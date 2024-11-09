# ChatBot

## Overview

This is a simple command-line chatbot created using Python. The chatbot, named **Kinshu**, can respond to basic user inputs, provide the current time, and fetch weather information for specified cities. The bot calculates the similarity between user inputs and predefined responses to provide the most relevant answer.

## Features

- **Greeting and Farewell Responses**: Kinshu can respond to greetings and say goodbye.
- **Time Check**: Kinshu can tell the current time.
- **Weather Information**: Kinshu can provide real-time weather information for a specified city.
- **Customizable Responses**: The bot’s responses are stored in a dictionary and can be easily customized.

## How It Works

1. **Text Similarity Matching**: The bot uses the `SequenceMatcher` class from Python’s `difflib` library to calculate the similarity between user input and predefined responses.
2. **Weather Information**: Kinshu fetches weather data from the OpenWeatherMap API. It requires an API key to access this data.
3. **Command Recognition**: The bot can interpret commands to tell the time, provide weather, or exit the conversation.

## Requirements

- Python 3.x
- `requests` library for API calls

Install the requests library using:
pip install requests

Setup
Obtain an API key from OpenWeatherMap to access weather data.
Replace "YOUR_API_KEY" in the code with your actual API key.

Usage
Run the chatbot.

The bot will prompt you to input text. You can type questions or commands such as:
"Hello"
"What time is it?"
"What's the weather in [City Name]?"
"Exit" to end the chat.

Example Interaction:
Hello! My name is Kinshu. How can I help you today?
You: What's the weather in London?
Kinshu: The weather in London is partly cloudy with a temperature of 15°C.

Customization
You can add or modify responses in the responses dictionary to extend Chat Bot's functionality.
