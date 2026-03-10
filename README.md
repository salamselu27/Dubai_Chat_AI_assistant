# ✈️ Dubai Trip AI Assistant 🐪

An AI-powered personalized travel planner designed to help users plan trips to Dubai by providing tailored itineraries, weather expectations, and intuitive recommendations using the OpenAI API.

## 🚀 Overview
This project is an interactive chatbot that serves as your dedicated Dubai travel guide. It engages users to suggest hidden gems, cultural hotspots, and iconic attractions while offering real-time assistance and estimations.

## 🛠️ Tech Stack
* **Language:** Python
* **Framework:** Streamlit (Interactive UI)
* **AI Model:** OpenAI GPT-4o-mini

## ✨ Key Features
* **Personalized Itineraries:** Generates custom daily plans based on your specific preferences.
* **Interactive Experience:** The AI asks relevant questions to suggest hidden gems, cultural hotspots, and iconic attractions.
* **Helpful Information:** Provides details on the best travel seasons, visa requirements, and current travel regulations.
* **Streamlit Interface:** A clean, seamless, responsive chat interface built with Streamlit.

## ⚙️ Setup & Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/salamselu27/Dubai_Chat_AI_assistant.git
   cd Dubai_Chat_AI_assistant
   ```

2. **Set up a virtual environment (recommended):**
   ```bash
   python -m venv chatbot
   .\chatbot\Scripts\activate
   ```

3. **Install the required dependencies:**
   Make sure you have `streamlit`, `openai`, and `python-dotenv` installed:
   ```bash
   pip install streamlit openai python-dotenv
   ```

4. **Set up environment variables:**
   Create a `.env` file inside the `chatbot` directory and add your OpenAI API key:
   ```env
   OPENAI_API_KEY=your_openai_api_key_here
   ```

## ▶️ Running the Application

To run the application, use the Streamlit CLI. From the root directory, run:
```bash
streamlit run chatbot/chatbotai.py
```
