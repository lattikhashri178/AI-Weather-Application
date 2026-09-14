# AI Weather Application

## Project Overview

AI Weather Application is a Streamlit-based weather assistant that uses a Large Language Model (LLM) with function calling to provide current weather information for different cities.

The application uses Hugging Face for the LLM and Open-Meteo APIs to retrieve real-time weather information.

## Features

- Ask weather-related questions using natural language
- Get current weather information for any city
- Temperature displayed in °C
- Humidity displayed in %
- Wind speed displayed in km/h
- AI-powered responses using Hugging Face
- Function calling for weather retrieval
- Interactive Streamlit interface

## Technologies Used

- Python
- Streamlit
- Hugging Face Transformers / Inference API
- Hugging Face InferenceClient
- Open-Meteo Geocoding API
- Open-Meteo Weather API
- Requests
- python-dotenv

## Project Structure

```text
AI-Weather-Application/
│
├── app.py
├── requirements.txt
├── .gitignore
├── README.md
└── .env
