# 📈 MarketInsight

**MarketInsight** is an AI-powered stock market analysis platform that helps users research stocks, analyze market data, and get intelligent insights using AI.

##  Features

* 📊 Stock market analysis
* 🤖 AI-powered financial insights
* 📈 Real-time/market data integration
* 🔎 Stock research and analysis tools
* 💬 AI agent for market-related queries
* 🌐 Modern React + Vite frontend
* ⚡ FastAPI/Python backend
* 📋 Interactive market dashboard

## Tech Stack

### Backend

* Python
* FastAPI
* LangChain
* LangGraph
* OpenAI
* YFinance
* Langfuse

### Frontend

* React
* TypeScript
* Vite
* CSS

### Deployment

* Vercel
* Render

## Project Structure

```text
MarketInsight-main/
├── MarketInsight/
│   ├── components/
│   │   └── agent.py
│   └── utils/
│       ├── logger.py
│       └── tools.py
├── config/
│   └── config.py
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── vite.config.ts
├── main.py
├── requirements.txt
├── pyproject.toml
├── render.yaml
└── README.md
```

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/himanshu239111/Marketinsight.git
cd Marketinsight
```

### 2. Set up the Python environment

```bash
python -m venv venv
```

Windows:

```powershell
venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

### 3. Install frontend dependencies

```bash
cd frontend
npm install
```

### 4. Configure environment variables

Create your environment file and add the required API configuration.

Example:

```env
OPENAI_API_KEY=your_api_key
```

**Never commit API keys or other secrets to GitHub.**

## ▶️ Running the Project

### Backend

From the backend project directory:

```bash
python main.py
```

### Frontend

From the `frontend` directory:

```bash
npm run dev
```

The frontend will provide the web interface for interacting with MarketInsight.

## How It Works

MarketInsight combines market-data tools with AI agents to analyze financial information.

```text
User
  ↓
React Frontend
  ↓
Python Backend
  ↓
AI Agent
  ↓
Market Data / Analysis Tools
  ↓
AI-generated Insights
  ↓
Frontend
```

## Data & AI

MarketInsight uses market-data services and AI models to assist with stock research and analysis.

The application is intended as an **analysis and research tool**, not as financial advice.

## Security

* Keep API keys in environment variables.
* Never commit `.env` files containing secrets.
* Rotate any API key that has accidentally been exposed.

## Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Commit your changes.
5. Open a pull request.

## 📄License

This project is licensed under the terms specified in the repository's `LICENSE` file.


