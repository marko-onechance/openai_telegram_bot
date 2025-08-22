# OpenAI Telegram Bot

Telegram bot that integrates with OpenAI to provide various interactive features including random facts, GPT chat interface, and personality-based conversations.

Feel the full power of chatGPT assistant!

## Setup

1. **First, you need to install some dependencies (modules):**
   ```bash
   pip install -r technical_requirements.txt
   ```

2. **Create config file:**
   Create `config.py` with your API keys:
   ```python
   TG_BOT_API_KEY = "your_telegram_bot_token"
   OPENAI_API_KEY = "your_openai_api_key"
   ```

3. **Run the bot:**
   ```bash
   python src/bot.py
   ```

## Features

- `/start` - Welcome message with main menu 
- `/random` - Random fact generator with GPT assistant 
- `/gpt` - Direct GPT chat interface  
- `/talk` - Personality-based conversations (Cobain, Hawking, Nietzsche, Queen, Tolkien)
- `/quiz` - Quiz functionality (you can test your knowledge in various fields, such as: history, science, art, sports)

## Requirements

- Python 3.7+
- Telegram Bot Token (from @BotFather)
- OpenAI API Key
