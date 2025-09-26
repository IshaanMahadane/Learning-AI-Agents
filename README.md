# Learning-AI-Agents

This repository contains my experiments in building intelligent agents using **LangChain** and the **OpenAI API**.  
The agents can reason step-by-step, perform arithmetic calculations, and answer queries interactively.

---

## 🚀 Features
- Built using **OpenAI's `gpt-4o-mini`** model (low-cost and efficient).  
- Supports mathematical reasoning through the `llm-math` tool.  
- Implements **LangChain Agents** (`CHAT_ZERO_SHOT_REACT_DESCRIPTION`) for structured reasoning.  
- Modular and extendable design for adding more tools in the future.  

---

## ⚙️ Architecture
- **LLM Backend:** OpenAI model (`gpt-4o-mini`) powers the reasoning.  
- **LangChain Agent:** Orchestrates reasoning and tool use.  
- **Tools Integrated:**  
  - `llm-math` → arithmetic and mathematical reasoning.  

---

## 🛠️ Technologies Used
- **Python** (v3.10+)  
- **LangChain**  
- **OpenAI API**  

---

## 📦 Installation

Clone the repo and install dependencies:
```bash
git clone https://github.com/IshaanMahadane/Learning-AI-Agents.git
cd Learning-AI-Agents

Set your OpenAI API key:

export OPENAI_API_KEY="your_api_key_here"

Run the agent:

python your_agent_script.py

🧠 What I Learned

Through this project, I explored:

LangChain Agents – how they reason and invoke tools step-by-step.

OpenAI Models – using cost-effective models like gpt-4o-mini.

Tool Integration – extending LLMs with llm-math for reliable calculations.

Agent Design – understanding how models, tools, and prompts interact.

📌 Example Usage
result = agent.invoke("What is the GDP of India in 2024 plus 5?")
print(result)
