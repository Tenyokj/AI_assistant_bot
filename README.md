# 🤖 AI ChatBot for Telegram

A simple and powerful Telegram bot using the [OpenRouter API](https://openrouter.ai) to access models like GPT-3.5, Mistral, Claude, LLaMA and more — all **for free**.

---

## ✨ Features

- 🧠 Multiple AI models (Mistral, GPT-3.5, Claude, etc.)
- ✏️ Custom system prompt (assistant personality)
- ⚙️ Inline settings menu with buttons
- 💬 Fast replies via OpenRouter API
- 🌍 English-only interface for global use

---

## 📦 Tech Stack

- Node.js
- [node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api)
- OpenRouter.ai (OpenAI-compatible API)

---

## 🚀 Getting Started

1. Clone the repo:
```bash
git clone https://github.com/yourusername/yourrepo.git
cd yourrepo

2. Install dependencies:

npm install

3. Create .env file:

BOT_TOKEN=your_telegram_bot_token
OPENROUTER_API_KEY=your_openrouter_key

4. Run the bot:

node index.js

🔧 Commands
Command	Description
/start	Welcome message
/help	Show available commands
/model	Manually select AI model
/prompt	Set assistant personality
/reset	Reset settings
/menu	Open inline menu with buttons

💡 Example Prompts

/prompt
You are a funny pirate that loves giving sarcastic answers.
/prompt
You are a professional teacher who explains like a human.

🤖 Available Models

    mistralai/mistral-7b-instruct

    openai/gpt-3.5-turbo

    anthropic/claude-3-haiku

    meta-llama/llama-3-8b-instruct

💡 Example demo screenshot

![изображение](https://github.com/user-attachments/assets/25b4f609-840a-4748-9e75-af69243cddf8)


