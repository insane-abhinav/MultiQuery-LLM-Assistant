# MultiQuery LLM Assistant

**MultiQuery LLM Assistant** is a context-aware chatbot system built on the LLaMA-8B-Instruct model (served via Fireworks API). It is designed to process and handle **multiple user queries in a single input**, intelligently routing them to appropriate APIs such as **Weatherstack** (for weather data) and **Spoonacular** (for food, recipes, and nutrition).

The assistant supports both **single-query** and **multi-query** modes of operation and is capable of parsing complex instructions to deliver coherent, accurate responses in real time.

---

## Features

- LLM-based semantic intent recognition using Fireworks LLaMA-8B-Instruct
- Multiple API integration: Weatherstack and Spoonacular
- Multi-intent parsing from a single user query
- Configurable single or multi-query processing mode
- Dynamic response generation combining data from multiple sources

---

## Requirements

FIREWORKS_API_KEY=your_fireworks_api_key
SPOONACULAR_API_KEY=your_spoonacular_api_key
WEATHERSTACK_API_KEY=your_weatherstack_api_key

