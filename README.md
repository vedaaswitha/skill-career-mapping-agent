# skill-career-mapping-agent
An AI-powered Skill-to-Career Mapping Assistant built with LangChain, LangGraph, and Google Gemini. It analyzes industry skill demands using Tavily Search and fetches real-time job openings in India via the JSearch API.
# AI-Powered Skill-to-Career Mapping Assistant 🤖💼

An intelligent career development agent built using **LangChain**, **LangGraph**, and **Google Gemini 2.5 Flash**. This assistant acts as a personalized career advisor for students and job seekers, analyzing industry trends, salary insights, and fetching active job or internship openings tailored to specific skills and locations.

## 🚀 Features

*   **Market Analysis**: Performs real-time web searches using the Tavily Search API to gauge global and local demand, salary ranges, and industry trends for any tech skill.
*   **Live Job Fetching**: Connects to the **JSearch API (via RapidAPI)** to pull live entry-level and internship job listings in India based on user queries.
*   **Conversational Memory**: Utilizes LangGraph's `InMemorySaver` to remember context across conversations (e.g., asking for deeper insights into companies listed in previous turns).
*   **Clean Output formatting**: Delivers unstructured, clean, and highly readable responses focused on user intent.

## 🛠️ Architecture & Tech Stack

*   **LLM Core**: Google Gemini (`gemini-2.5-flash`) via `langchain-google-genai`
*   **Framework**: LangChain & LangGraph (State management & tool-calling agent framework)
*   **Search Engine**: Tavily Search Engine Tool
*   **Job Directory API**: JSearch API via RapidAPI

---

## 📋 Prerequisites & API Keys

To run this notebook, you will need to acquire the following API credentials and store them securely in your environment or Google Colab Userdata secrets:

1.  **`GEMINI_API_KEY`**: Obtain from [Google AI Studio](https://aistudio.google.com/).
2.  **`TAVILY_API_KEY`**: Obtain from [Tavily AI](https://tavily.com/).
3.  **`RAPIDAPI_KEY`**: Obtain by subscribing to the **JSearch API** hosted on [RapidAPI](https://rapidapi.com/).

---

## ⚙️ Installation & Usage

1. **Clone the Repository**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/skill-career-mapping-agent.git](https://github.com/YOUR_USERNAME/skill-career-mapping-agent.git)
   cd skill-career-mapping-agent
