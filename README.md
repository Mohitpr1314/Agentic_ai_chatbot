# Agentic_ai_chatbot

## just click image to use live demo

[![Watch the demo](https://github.com/Mohitpr1314/Agentic_ai_chatbot/blob/main/agentic.png)](https://agenticaichatbot-mohit.streamlit.app/)



# 💬 LangGraph Chatbot — Streamlit + Gemini 2.5 Flash

An intelligent multi-threaded chatbot built with **Streamlit**, **LangGraph**, and **Gemini 2.5 Flash** that supports real-time conversations, tool use (calculator, weather, stock info, and web search), and persistent chat history using **SQLite**.

---

## 🚀 Features

- 🧠 **Conversational AI** powered by [Gemini 2.5 Flash](https://ai.google.dev/)
- 🧰 **Tool Integration**:  
  - 🌐 Web search (DuckDuckGo)  
  - 🔢 Arithmetic calculator  
  - 🌦️ Real-time weather data (OpenWeatherMap)  
  - 💹 Stock price lookup (Alpha Vantage)
- 💾 **Persistent Chat History** — Stores chat threads in SQLite  
- 🪄 **Multi-Threaded Conversations** — Switch easily between multiple chats  
- 🎨 **Interactive Streamlit UI** with dynamic chat bubbles  

---

## 🧩 Tech Stack

| Component | Technology |
|------------|-------------|
| Frontend | [Streamlit](https://streamlit.io/) |
| Backend | [LangGraph](https://github.com/langchain-ai/langgraph), [LangChain](https://python.langchain.com/) |
| LLM | [Google Generative AI (Gemini 2.5 Flash)](https://ai.google.dev/) |
| Tools | DuckDuckGo Search, OpenWeatherMap API, Alpha Vantage |
| Database | SQLite |
| Environment Management | python-dotenv |

---

## ⚙️ Installation

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/langgraph-chatbot.git
cd langgraph-chatbot

```
### 2️⃣ Create a virtual environment
```bash
python -m venv venv
source venv/bin/activate   # (Mac/Linux)
venv\Scripts\activate      # (Windows)
```
### 3️⃣ Install dependencies
```
pip install -r requirements.txt
```

### 4️⃣ Add environment variables

Create a .env file in the project root and add:

```
GOOGLE_API_KEY=your_google_api_key
WEATHER_API_KEY=your_openweathermap_api_key
```
💻 Usage
Start the chatbot
```
streamlit run frontend.py
```


