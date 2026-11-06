Restaurant Ordering AI Agent 🍽️

A restaurant ordering AI agent built using Python, LangGraph, LangChain, and Groq LLM.

The agent handles customer orders, checks menu availability, and manages cooking and serving workflows.

Features

Extracts dish names and quantities using an LLM.

Checks menu availability (full, partial, or unavailable).

Uses probabilistic cooking and serving simulations.

Implements retry mechanisms for failed operations.

Manages workflow using LangGraph state and conditional edges.

Tech Stack

Python

LangGraph

LangChain

Groq

Pydantic

uv


Create a .env file:

GROQ_API_KEY=your_api_key

Run the project:

uv run python main.py
