# Synqora AI 🤖

An advanced AI-powered Multi-Agent Research System built using LangChain, LangGraph, Gemini API, Tavily Search, BeautifulSoup, and LCEL Runnable Pipelines.

This project is designed to perform intelligent research by combining multiple AI agents, web search capabilities, and web scraping tools into a single automated workflow.

---

# Features

* Multi-Agent Architecture
* Gemini API Integration
* Tavily AI Search Tool
* BeautifulSoup Web Scraping
* ReAct Agent Workflow
* LCEL Runnable Pipelines
* Async Tool Support
* Modular Project Structure
* Streamlit Frontend
* FastAPI Backend Support
* LangGraph State Management
* Extensible Tool System

---

# Tech Stack

## AI / LLM

* Google Gemini API
* LangChain
* LangGraph

## Search & Scraping

* Tavily Search API
* BeautifulSoup4
* Requests
* LXML

## Backend

* Python

## Frontend

* Streamlit

---

# Installation

## Clone Repository

```bash
git clone https://github.com/your-username/multi-agent-research.git

cd multi-agent-research
```

---

## Create Virtual Environment

```bash
python -m venv .venv
```

---

## Activate Virtual Environment

### Windows

```bash
.venv\Scripts\activate
```

### Linux / MacOS

```bash
source .venv/bin/activate
```

---

## Install Dependencies

```bash
python -m pip install -r requirements.txt
```

---

# Environment Variables

Create a `.env` file in the root directory.

```env
GOOGLE_API_KEY=your_gemini_api_key
TAVILY_API_KEY=your_tavily_api_key
```

---

# Running the Project

## Streamlit Frontend

```bash
python -m streamlit run app.py
```


# How It Works

1. User enters a research query.
2. Tavily agent searches the internet.
3. BeautifulSoup agent extracts detailed webpage content.
4. Gemini-powered agents analyze information.
5. ReAct Agent decides which tool to use.
6. LCEL Runnable Pipelines process the workflow.
7. Final research response is generated.

---

# Future Improvements

* Memory-enabled agents
* Vector database integration
* Multi-modal research support
* Autonomous planning agents
* PDF report generation
* Voice-enabled AI agents
* Docker deployment
* Authentication system

---

# Why This Project?

This project demonstrates:

* Real-world AI agent orchestration
* Tool-augmented LLM workflows
* Production-style AI architecture
* Modern LangChain + LangGraph ecosystem
* Advanced research automation systems

---

# Author

Yash Barfa

---

# License

This project is licensed under the MIT License.
