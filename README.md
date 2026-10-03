🤖 Conversational SQL AI Agent
A conversational AI agent that allows users to interact with a SQL database using natural language instead of writing SQL queries.


✨ Features
- Ask database questions in plain English
- Automatically generates and executes SQL queries
- Supports follow-up questions with conversation history
- Handles filtering, sorting, and calculations
- Uses database results to provide accurate responses

🛠️ Tech Stack
- Python
- LangChain
- Groq + Qwen
- SQLite
- SQLAlchemy
- Jupyter Notebook

🔄 How It Works
User Question
      ↓
Qwen / Groq LLM
      ↓
LangChain SQL Agent
      ↓
SQLite Database
      ↓
Natural Language Answer


🚀 Setup
pip install -r requirements.txt

Create a .env file:
GROQ_API_KEY=your_groq_api_key

Then open SQLAgent.ipynb and run the cells.

💡 Example
You: Which product has the highest stock?

Agent: Product F has the highest stock with 800 units.

🔮 Future Improvements
- SQL query visualization
- Data tables and charts
- Streamlit web interface
- Support for multiple databases

Author: Raunak Priyadarshi Yadav
M.Tech Data Science | IIT Roorkee
