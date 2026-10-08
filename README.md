### End to End Project Agentic AI Chatbots
# Agentic AI Chatbot with LangGraph

An end-to-end Agentic AI application built using LangGraph, LangChain, Groq, Tavily, and Streamlit.

## Features

- Basic AI chatbot
- Chatbot with real-time web search using Tavily
- Tool calling with LangGraph
- Stateful message handling
- Conditional routing between LLM and tools
- AI News Summarizer
- Daily, Weekly, and Monthly AI news summaries
- Streamlit user interface
- Multiple Groq model options

## Tech Stack

- Python
- LangGraph
- LangChain
- Groq
- Tavily
- Streamlit

## Project Flow

### Basic Chatbot

START → Chatbot → END

### Chatbot with Web Search

START → Chatbot → Tool Decision  
→ If web search is required → Tavily → Chatbot → Final Answer  
→ Otherwise → END

### AI News Summarizer

Time Frame Selection  
→ Tavily Search  
→ AI News Collection  
→ Groq LLM Summarization  
→ Streamlit Display

## Project Structure

```text
Agentic-Chatbot/
│
├── app.py
├── requirements.txt
├── README.md
│
└── src/
    └── langgraphAgenticAI/
        ├── main.py
        ├── graph/
        ├── LLMs/
        ├── Nodes/
        ├── state/
        ├── tools/
        └── ui/


## Live Demo

Try the deployed application here:

Live Demo on Render: https://agentic-chatbot-gfaq.onrender.com
