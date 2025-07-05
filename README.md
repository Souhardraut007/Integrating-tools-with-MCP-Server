# MCP Demo with LangChain and Groq

This project demonstrates how to use **LangChain MCP Adapters** with multiple tools (`mathserver.py`, `weather.py`) and integrate it with **Groq LLMs** to build a multi-agent intelligent system.

## 🔧 Technologies Used -

- [LangChain](https://github.com/langchain-ai/langchain)
- [LangGraph](https://github.com/langchain-ai/langgraph)
- [MCP (Multi-tool Composable Protocol)](https://github.com/langchain-ai/langchain-mcp-adapters)
- [Groq LLMs](https://groq.com/)
- FastAPI (for weather service)
- AsyncIO (Python async)
- `.env` configuration via `python-dotenv`

---

## 📁 Project Structure

```bash
.
├── client.py               
├── weather.py            
├── mathserver.py        
├── .env                   
├── requirements.txt       
├── README.md            
└── env/ or .venv/       
```
