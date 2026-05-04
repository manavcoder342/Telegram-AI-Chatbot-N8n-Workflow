  Telegram AI Chatbot - n8n Workflow

A powerful, fully automated Telegram AI Chatbot built with **n8n**. This workflow enables intelligent, real-time conversations through your Telegram bot using AI.

   ✨ Features

- Real-time message receiving and processing
- Intelligent AI-powered responses
- Natural conversation flow with context awareness
- Customizable system prompt and bot personality
- Logging of conversations
- Error handling and retry logic
- Fully self-hosted solution
- Easy to deploy and modify

   How It Works

The workflow connects to Telegram, receives incoming messages, processes them through an AI model, and sends back smart replies automatically. Everything runs smoothly in n8n without any manual intervention.

   Prerequisites

- n8n (self-hosted recommended)
- Telegram Bot Token (from [@BotFather](https://t.me/botfather))
- Access to an AI provider API

   Setup Instructions

1. Clone or Download** this repository
2. Import the `workflow.json` file into your n8n instance
3. Set up your credentials:
   - Telegram Bot Token
   - AI API credentials
4. Configure the system prompt in the workflow
5. Activate the workflow

   Configuration

- Edit the **system prompt** to define your bot's personality and behavior
- Adjust response settings (temperature, max tokens, etc.)
- Customize logging and storage options

   Files Included

- workflow.json → Main n8n workflow file
- README.md → This file

   Usage

After activating the workflow, simply message your Telegram bot. It will respond intelligently in real-time.

   Customization

You can easily extend this workflow by adding:
- Database integrations
- Additional notification channels
- Advanced conversation memory
- File handling capabilities

   Support

Feel free to open an issue if you face any problems or want new features.

---

Made with ❤️ using n8n
