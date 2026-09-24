AI Weather Assistant

##  About the Project

AI Weather Assistant is a simple AI-based weather application developed using Python and Streamlit.

The application allows users to ask questions about the weather in natural language. It uses a Hugging Face LLM with Function Calling to identify the city and retrieve current weather information using the Open-Meteo API.
<img width="1268" height="491" alt="Screenshot 2026-09-15 004720" src="https://github.com/user-attachments/assets/83b32b28-4737-4ad2-97a3-cc6317c3fc61" />
<img width="922" height="333" alt="Screenshot 2026-09-15 005204" src="https://github.com/user-attachments/assets/4c9b6a8f-acd8-4efa-94d4-89672c524db5" />


##  Features

- Ask weather questions in natural language
- Get current weather information
- Temperature in °C
- Humidity in %
- Wind speed in km/h
- AI-based responses using Hugging Face
- Interactive Streamlit interface
- Automatic city location detection

## 🛠️ Technologies Used

- Python
- Streamlit
- Hugging Face
- Open-Meteo API
- Requests
- Python-dotenv

##  How It Works

```text
User Question
      ↓
Hugging Face LLM
      ↓
Function Calling
      ↓
get_weather()
      ↓
Open-Meteo API
      ↓
Weather Information
      ↓
AI Response

