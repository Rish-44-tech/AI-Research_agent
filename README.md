🧠 Research Assistant with LangChain & Multi-LLM Support

This project is an AI-powered research assistant that uses LangChain, Google Gemini, and various tools like search, Wikipedia, and a custom save_tool to assist in generating research summaries in a structured format using Pydantic validation.

🚀 Features:
  ✅ Supports Google Gemini (gemini-2.5-pro) as the LLM
  🧰 Tool-using agent with support for: 
    🔍 Web Search (search_tool)
    📚 Wikipedia (wiki_tool)
    💾 Save Tool (save_tool)
  📦 Outputs structured research using Pydantic model
  🧠 Built using LangChain's tool calling agent API
  
🛠️ Project Structure

├── main.py            # Entry point to run the assistant
├── tools.py           # Custom tools used by the agent
├── .env               # Environment variables (API keys)
├── requirements.txt   # Python libraries and frameworks required
└── README.md          # You're here!
