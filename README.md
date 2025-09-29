# Advanced-Chatbot-Using-LangGraph

📖 Project Overview

This project implements an Advanced Chatbot powered by LangGraph, Streamlit, and OpenAI models. It combines a backend conversational graph with a frontend UI to provide a seamless chat experience with tools like web search and calculations.

🗂 Project Structure

langgraph_advanced_chatbot.py – Defines the backend chatbot logic using:
- LangGraph for stateful conversation handling
- LangChain tools like DuckDuckGo search and a custom calculator
- OpenAI for natural language understanding
- SQLite for chat history persistence
- A StateGraph for multi-turn conversations with tool integration

langgraph_advanced_chatbot_frontend.py – Provides the frontend using Streamlit, including:
- Multiple chat threads support
- Conversation persistence & retrieval
- A simple chat UI for interaction with the backend

🚀 Features

- Multiple Conversation Threads: Manage and revisit past conversations.
- Tool Integration: Includes a web search tool and a basic calculator.
- Persistent Memory: Conversation states stored in SQLite.
- Modular Design: Easily extend with more tools or UI improvements.
- Streamlit UI: Intuitive interface for chatting with the model.

🧩 Extending the Chatbot

- Add new tools using @tool decorators in langgraph_advanced_chatbot.py.
- Enhance the UI in langgraph_advanced_chatbot_frontend.py with Streamlit components.
- Connect external APIs for more powerful features.
