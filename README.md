# LangChain_Crash_Course

AI Agent: 
An Agent is a LLM based application which has capability to call tools, take decisions,perform a Task with minimum Human intervention.

Agentic AI:
Agentic AI is a goal-oriented AI system where LLM-powered agents autonomously reason, plan, use tools, and take actions. In more complex systems, Agentic AI can orchestrate multiple specialized agents to accomplish a goal.

LangChain:
LangChain is a framework for developing LLM-powered applications, including agentic AI systems, by connecting LLMs with tools, data sources, memory, and workflows.

Environment Set up:
python --version
uv --version
pip install uv (for UV Installation)
uv init --python 3.12
uv sync (This will take care of venv creation)
git branch -m main
git add .
git commit -m "intial commit"
uv add langchain
uv add langchain-groq
.venv/Scripts/activate

Create your file .ipynb or .py, select your kernel 
Note: you can install ipykernel or it is will be installed automatically when you allow notification

1. create .env file and paste your API keys
2. Include .env and .venv in gitignore file 

Core Components of Langchain:
Models
Messages
Agents
