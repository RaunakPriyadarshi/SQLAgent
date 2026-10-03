# 🤖 Conversational SQL AI Agent

A conversational AI agent that allows users to interact with a SQL database using natural language instead of writing SQL queries manually.

## ✨ Features

- 💬 Ask database questions in plain English
- 🧠 Automatically generates and executes SQL queries
- 🔄 Supports follow-up questions using conversation history
- 🔍 Handles filtering, sorting, and calculations
- ✅ Uses actual database results to provide accurate responses

## 🛠️ Tech Stack

- **Python**
- **LangChain**
- **Groq + Qwen**
- **SQLite**
- **SQLAlchemy**
- **Jupyter Notebook**

## 🔄 How It Works

```text
User Question
      ↓
Groq LLM
      ↓
LangChain SQL Agent
      ↓
SQLite Database
      ↓
Natural Language Answer

🚀 Setup

1. Install Dependencies
pip install -r requirements.txt

2. Configure Environment Variables
Create a .env file in the project directory and add your Groq API key:
GROQ_API_KEY=your_groq_api_key

⚠️ Never commit your .env file or expose your API key publicly.

3. Run the Project
Open SQLAgent.ipynb in VS Code or Jupyter Notebook and run the cells sequentially.
💡 Example
You: Which product has the highest stock?

Agent: Product F has the highest stock with 800 units.

🔮 Future Improvements
- 📋 Display generated SQL queries
- 📊 Add data tables and visualizations
- 📈 Add interactive charts
- 🌐 Build a Streamlit web interface
- 🗄️ Support multiple databases

👨‍💻 Author
Raunak Priyadarshi Yadav
M.Tech Data Science | IIT Roorkee
