# AI Assistant

This is a simple command-line AI assistant built with LangChain and OpenAI. It uses a ReAct agent and supports custom tools for basic arithmetic and greeting users.

## Features

- Responds to user input using OpenAI's language model
- Supports custom tools:
  - Calculator for basic arithmetic
  - Greeting tool to say hello
- Easy to extend with additional tools

## Requirements

- Python 3.8+
- An OpenAI API key
- UV (pip3 install uv)

## Installation
 
```Clone the repository :
git clone https://github.com/firdaoussladham/ai-assistant.git
cd ai-assistant

``Create a .env file in the project directory and add your API key like this:  OPENAI_API_KEY=your-openai-api-key

```Install the dependencies : 
uv install .

```Run the environment :
uv run main.py
