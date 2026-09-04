# 🤖 AI Agent System

An AI-powered multi-agent application built using **Python, Streamlit, LangGraph, and OpenRouter**.
The project allows different AI agents to work together to generate, process, and manage tasks efficiently.

## 🚀 Features

* 🤖 AI-powered agent system
* 🔗 Multi-agent workflow using LangGraph
* 💬 OpenRouter LLM integration
* 🖥️ Interactive Streamlit web interface
* 📁 Workspace for managing project data
* ⚙️ Environment variable support using `.env`
* 🔄 Agent-based task processing

## 🛠️ Technologies Used

* **Python**
* **Streamlit**
* **LangGraph**
* **LangChain**
* **OpenRouter**
* **Python-dotenv**

## 📂 Project Structure

```text
agentss/
│
├── agents/                 # AI agent files
├── workspace/              # Workspace/data files
├── venv/                   # Python virtual environment
│
├── drl.py                  # Main Streamlit application
├── aai.py                  # AI agent-related functionality
├── agent_systems.json      # Agent system configurations
├── team.csv                # Team information
├── dev_team.csv            # Development team configuration
├── edu_team (1).csv        # Education team configuration
├── mark_team.csv           # Marketing team configuration
├── writing_team.csv        # Writing team configuration
├── instructions.txt        # Project instructions
├── .env                    # Environment variables
└── README.md               # Project documentation
```

## ⚙️ Installation

### 1. Clone or download the project

Download the project to your computer and open the project folder in VS Code.

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the virtual environment

**Windows PowerShell:**

```powershell
venv\Scripts\Activate.ps1
```

You should see:

```text
(venv)
```

### 4. Install required packages

```bash
python -m pip install streamlit
python -m pip install langchain-openrouter
python -m pip install langgraph
python -m pip install python-dotenv
```

If the project shows another `ModuleNotFoundError`, install the missing package using:

```bash
python -m pip install package-name
```

## 🔑 Environment Setup

Create a `.env` file in the main project folder.

Add your OpenRouter API key using the variable name expected by your Python code:

```env
OPENROUTER_API_KEY=your_api_key_here
```

**Never upload or publish your actual API key to GitHub.**

## ▶️ Run the Application

Activate the virtual environment:

```powershell
venv\Scripts\Activate.ps1
```

Then start the Streamlit application:

```powershell
python -m streamlit run drl.py
```

The application will open in your browser.

Usually, Streamlit runs at:

```text
http://localhost:8501
```

## 🧠 How It Works

1. The user interacts with the Streamlit interface.
2. The application receives the user's task.
3. LangGraph manages the agent workflow.
4. Different AI agents process their assigned tasks.
5. OpenRouter provides access to the selected language model.
6. The final result is displayed through the Streamlit interface.

## 🎯 Project Objective

The main objective of this project is to demonstrate how **multiple AI agents can collaborate through a structured workflow** to solve complex tasks efficiently.

## 🔮 Future Improvements

* Add more specialized AI agents
* Improve agent communication
* Add conversation history
* Add authentication
* Store results in a database
* Deploy the application online
* Add more LLM providers

## 👩‍💻 Author

**Roqayya Abdul**

Computer Science & Engineering Student

## 📄 License

This project is created for educational and learning purposes.
