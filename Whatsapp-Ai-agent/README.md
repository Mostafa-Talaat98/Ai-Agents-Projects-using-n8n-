🤖 Multi-Agent AI WhatsApp Assistant (n8n)
This project features a sophisticated Autonomous AI Agent System built using n8n. It acts as a central brain (Orchestrator) connected to WhatsApp, capable of processing Text, Voice, and Images to execute complex tasks through specialized sub-agents.

🚀 Key Features
Multi-Modal Inputs: Processes text, transcribes voice notes (OpenAI Whisper), and analyzes images (Vision models).

Orchestrator Architecture: Uses a central "Brain" to route requests to the appropriate specialized agent based on user intent.

Specialized Sub-Agents:

Search Agent: Real-time web searching via Wikipedia and Google Search.

E-mail Agent: Full control over Gmail (Read, Send, Reply, and Manage).

Calendar Agent: Manages Google Calendar events (Create, Delete, Update).

Social Media Agent: Automated posting and management for X (Twitter).

Omnichannel Output: Sends responses back to WhatsApp as text or AI-generated voice.

🛠️ Tech Stack
Automation: n8n (LangChain Integration)

AI Models: GPT-4o / GPT-4o-mini

Communication: WhatsApp Cloud API

Tools: Google Search, Wikipedia, Gmail, Google Calendar, X API, OpenAI Whisper.

📸 Workflow Preview
![Workflow Preview](./)

⚙️ Setup & Installation
Import: Download the workflow.json file and import it into your n8n instance.

Credentials: You will need to configure your own credentials for:

OpenAI API (for the LLM and Whisper).

WhatsApp Cloud API.

Google Cloud Console (for Calendar and Gmail).

X (Twitter) Developer Portal.
