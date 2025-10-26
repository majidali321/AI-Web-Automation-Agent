🚀 MyAirtop – AI Web Automation Agent
🤖 Powered by n8n, Airtop.ai, and Google Gemini

MyAirtop is an AI-powered web automation agent built using n8n and integrated with Airtop.ai and Google Gemini.
This project allows an AI agent to control a browser, load websites, search or extract data, and interact with pages—just like a human user, but automatically!

🧠 Overview

The MyAirtop agent acts as a smart web operator that can:

Start and manage browser sessions

Load any webpage dynamically

Type into search bars or input fields

Click buttons or links

Query and extract information from pages

Close sessions once tasks are done

All of this is managed through n8n’s visual workflow automation with Airtop.ai providing real-time browser control and Google Gemini as the reasoning engine.

🧩 Tech Stack
Tool	Purpose
n8n	Workflow automation platform
Airtop.ai	Browser automation and web interaction
Google Gemini (PaLM)	AI reasoning and natural language understanding
LangChain Nodes for n8n	Used for AI agent orchestration
Custom Tools	Click, Type, Load, and Query operations
⚙️ How It Works

Chat Trigger – Starts the workflow when a chat message is received.

Google Gemini Model – Interprets the user’s message and decides actions.

AI Agent – Uses predefined tools to:

Start browser sessions

Load URLs

Type search queries

Click elements

Query or extract information

Memory Buffer – Stores short-term memory for multi-step operations.

Terminate Tool – Ends the session cleanly after task completion.

🧠 Agent Prompt Summary

The agent is designed to act like a human assistant controlling a browser:

It begins by starting a browser session.

Loads a given URL.

Interacts with elements like buttons, search bars, or links.

Extracts or summarizes content when asked.

Always closes the session before replying.

💡 Example Use Cases

Automated web searches and data extraction

Smart product lookup or price comparison bots

AI assistant that navigates and summarizes websites

Testing workflows that simulate user actions in browsers

📸 Project Workflow (n8n Overview)

Main nodes used in this workflow:

Chat Trigger

Google Gemini Chat Model

AI Agent

Create Browser

Load a Page

Type Tool

Click Tool

Query Tool

Terminate Tool

Think (Reasoning Helper)

Simple Memory

👨‍🏫 Credits

This project was created as part of my AI Automation learning journey under the guidance of
🎓 Sir Zafar Iqbal, who has been teaching us powerful tools like n8n, Google Gemini, and Airtop.ai.
Special thanks for his mentorship and practical teaching approach that inspired this project. 🙏

🧰 Setup Instructions
1. Clone this Repository
git clone https://github.com/<your-username>/myairtop.git

2. Import Workflow into n8n

Open your n8n dashboard.

Click Import from File.

Upload myairtop.json.

3. Add Required Credentials

Airtop API Key

Google Gemini API Key

4. Run the Workflow

Trigger the workflow manually or via the Chat Trigger node, and watch your AI agent in action! ⚡

🏷️ Tags

#AI #n8n #Airtop #Automation #GoogleGemini #LangChain #WebAutomation #IntelligentAgent

🌟 Author

Majid Ali
AI Automation Enthusiast | Student of Sir Zafar Iqbal
