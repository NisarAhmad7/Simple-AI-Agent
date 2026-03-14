#LangGraph Simple Agent 
## Project Overview

This project demonstrates a simple AI agent workflow using LangGraph and LangChain with OpenAI’s GPT model. The agent takes user messages, processes them through a GPT model, and returns responses interactively in the console.

## Features

Interactive command-line AI agent

Uses LangGraph to define agent workflow

Uses LangChain with OpenAI GPT-4o

Easy to extend with additional nodes or logic

## How It Works

Load environment variables (.env) for API keys.

Define AgentState to hold conversation messages.

Initialize ChatOpenAI model.

Create a StateGraph workflow with process node.

Take user input and invoke the agent until exit is entered.

## Usage

Install requirements:

```pip install -r requirements.txt```

Create a .env file with your OpenAI API key:

OPENAI_API_KEY=your_api_key_here

## Run the agent:

```python app.py```

Type messages interactively; type exit to quit.

## Project Structure
LangGraph-Agent/
│
├── app.py              
├── .env                
├── requirements.txt    
└── .gitignore           