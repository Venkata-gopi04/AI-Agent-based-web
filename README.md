
## 📌 Problem Statement Chosen  
**"Autonomous Web Navigator AI Agent"** – Build an AI Agent that can take natural language instructions and autonomously drive the web on a local computer.  

---

## 💡 Detailed Proposal & Prototype Plan  
The goal is to design a **local-first AI Web Agent** that eliminates the need for complex scripts and cloud-based dependencies while automating web browsing tasks through natural language.  

**Prototype Workflow:**  
1. **Input Layer:** User gives instructions in plain text or voice.  
2. **Processing Layer:** Local LLM parses the instruction into step-by-step tasks.  
3. **Execution Layer:** Browser automation tool (Puppeteer/Playwright/Selenium) executes actions.  
4. **Output Layer:** Clean structured outputs (tables, JSON, CSV) are generated and displayed in CLI/GUI.  

**Prototype Deliverables:**  
- Lightweight GUI for input/output.  
- Ability to perform at least 3 types of tasks: **Search & Extract**, **Form Filling**, and **Comparison Tables**.  
- Local execution ensuring security and privacy.  

---

## 🚀 Features to be Implemented  
- **Natural Language Processing:** Understand commands like “Find top 5 laptops under 50k.”  
- **Browser Automation:** Search, click, extract, and navigate autonomously.  
- **Data Extraction & Structuring:** Export in CSV/JSON/Table formats.  
- **Voice Input Support:** Optional voice commands for seamless usage.  
- **Local-First Execution:** No dependency on external cloud services.  
- **Simple UI:** User-friendly CLI and GUI.  

---

## ⚙️ Tech Stack Used  
- **LLM**: Ollama / GPT4All / Local LLaMA  
- **Orchestration:** Python or Node.js with LangChain  
- **Browser Automation:** Playwright / Puppeteer / Selenium  
- **Interface:** CLI & lightweight Web App (React/Flask)  
- **Data Handling:** JSON, CSV, Tables  

---

## 👥 Team Contributions  
- **Member 1:** Problem statement research & Proposal drafting.  
- **Member 2:** Prototype design & GUI development.  
- **Member 3:** LLM integration & command parsing.  
- **Member 4:** Browser automation & Output formatting (CSV/JSON) + Documentation.  

---



## 🙏 Acknowledgements  
Special thanks to the open-source AI community and automation frameworks that made this possible.  
