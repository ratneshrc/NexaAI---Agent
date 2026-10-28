🤖 NexaAI Agent

Your Intelligent AI Assistant for Answers, Web Search, and Daily News

NexaAI Agent is an intelligent AI assistant powered by Google Gemini and n8n workflow automation. It answers user questions, searches the web for useful information, provides the latest news updates, and delivers automated news notifications through Telegram and Email.

🚀 Features

- 🤖 AI-Powered Answers: Ask questions and get answers from Google Gemini.
- 🔍 Web Search: Search for relevant information using Google Search through SerpApi.
- 📰 Latest News Updates: Retrieve news about India, World, Technology, AI, and Sports.
- 💬 Telegram Integration: Interact with the AI assistant directly through Telegram.
- 📧 Email Notifications: Receive daily news updates through email.
- ⏰ Scheduled Automation: Configure automatic news delivery at a selected time.
- 🧠 Conversation Memory: Maintain conversational context using Simple Memory.
- 🧮 Calculator Tool: Perform calculations through the AI agent.

🛠️ Technologies Used

Technology| Purpose
n8n| Workflow automation
Google Gemini| AI-powered responses
Telegram Bot API| Chatbot communication
SerpApi| Google Search and news discovery
SMTP / Gmail| Email notifications
JavaScript| News formatting and data processing

⚙️ How It Works

1. AI Assistant Workflow

"Telegram Trigger → AI Agent → Telegram Send Message"

The user sends a question through Telegram. The AI Agent processes the message using Google Gemini and its configured tools, then sends a response back to Telegram.

2. Automated News Workflow

"Schedule Trigger → HTTP Request → JavaScript Code → Telegram / Email"

The workflow fetches Google Search results through SerpApi, formats the news, and sends updates through Telegram and Email.

📌 Example Use Cases

- Ask general questions and receive AI-generated answers.
- Search the web for relevant information.
- Get the latest available news headlines and links.
- Receive scheduled news updates on Telegram.
- Receive daily news digests through email.

🔧 Setup Instructions

1. Create an account on "n8n" (https://n8n.io/).
2. Create a Telegram bot using "BotFather" (https://t.me/BotFather).
3. Configure Google Gemini credentials in n8n.
4. Get an API key from "SerpApi" (https://serpapi.com/).
5. Import the exported workflow JSON file into n8n.
6. Configure the required Telegram, Gemini, SerpApi, and SMTP credentials.
7. Set the schedule and timezone to "Asia/Kolkata".
8. Test the workflows and publish or activate them in n8n.

🔐 Security

- Never upload API keys, bot tokens, passwords, or other private credentials to GitHub.
- Store credentials securely using n8n Credentials.
- Remove sensitive information from exported workflow JSON files before uploading them publicly.

🔮 Future Enhancements

- AI-powered news summarization.
- Improved filtering to reduce duplicate news.
- More news categories and personalized updates.
- Voice-based interaction.
- A web dashboard for managing preferences and news.

🎓 Project Information

- Project Name: NexaAI Agent
- Project Title: An Intelligent AI Assistant Using Gemini and n8n Automation
- Project Type: AI Agent and Workflow Automation


📄 License

This project is developed for educational purposes. A suitable open-source license can be added if the project is shared publicly.
