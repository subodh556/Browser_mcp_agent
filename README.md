# Browser MCP Agent

Browser MCP Agent is a Streamlit-based application that lets you control a real web browser using plain English. It combines LLMs, the Model Context Protocol, and Playwright to turn natural language instructions into reliable browser actions.

Think of it as a conversational layer on top of a real browser, capable of navigating pages, interacting with elements, and extracting information step by step.

## 🏗️ How It Works

The system is built around an agent-driven architecture:

- A **Streamlit UI** collects user commands and displays results
- **MCP (Model Context Protocol)** connects language models with browser tools
- **Playwright** performs real browser automation
- **MCP-Agent** handles planning, tool execution, and multi-step reasoning
- **LLMs** interpret instructions and decide which browser actions to take

This setup allows complex browsing tasks to be executed conversationally, without writing automation scripts.

## 🛠️ Technology Stack

- Frontend: Streamlit
- Browser Automation: Playwright
- AI Framework: MCP-Agent
- Language Models: OpenAI API
- Protocol: Model Context Protocol (MCP)

## ✨ Capabilities

- **Natural Language Control**  
  Drive the browser using simple, conversational commands.

- **Complete Browser Navigation**  
  Open websites, move between pages, and follow links.

- **Page Interaction**  
  Click buttons, fill forms, scroll pages, and interact with UI elements.

- **Visual Output**  
  Capture screenshots of full pages or specific elements.

- **Content Extraction**  
  Pull text from pages and generate summaries or structured outputs.

- **Multi-step Workflows**  
  Execute chained tasks like searching, filtering, and summarizing in one command.

## 🚀 Getting Started

### Prerequisites

Make sure the following are installed:

- **Python 3.8 or higher**
- **Node.js and npm** (required for Playwright)
  - Verify with:
    ```bash
    node --version
    npm --version
    ```
- **An API key** for OpenAI or Anthropic

---

### Installation Steps

**1. Clone the repository**
```bash
git clone https://github.com/subodh556/Browser_mcp_agent.git
cd Browser_mcp_agent
```

**2. Install Python dependencies**
```bash
pip install -r requirements.txt
```

**3. Verify Node.js installation**
```bash
node --version
npm --version
```
Both commands should return version numbers. If not, install Node.js from the official website.

**4. Configure API keys**
```bash
export OPENAI_API_KEY=your-openai-api-key
```

### Running the Application

**1. Launch the Streamlit app**
```bash
streamlit run main.py
```

**2. Using the interface**
- Enter your browsing command in the text input
- Click "Run Command" to execute
- View results and screenshots in real-time


