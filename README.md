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

## Screenshots

### - command "/start":
![Знімок екрана 2025-08-23 о 21.59.45.png](../../../../Desktop/%D0%97%D0%BD%D1%96%D0%BC%D0%BE%D0%BA%20%D0%B5%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202025-08-23%20%D0%BE%2021.59.45.png)
 
### - command "/random":
![Знімок екрана 2025-08-23 о 22.02.15.png](../../../../../../var/folders/km/4gfqcl3s75zflzgffvhs09b40000gn/T/TemporaryItems/NSIRD_screencaptureui_MeIBmW/%D0%97%D0%BD%D1%96%D0%BC%D0%BE%D0%BA%20%D0%B5%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202025-08-23%20%D0%BE%2022.02.15.png)

### - command "/gpt":
![Знімок екрана 2025-08-23 о 22.03.26.png](../../../../../../var/folders/km/4gfqcl3s75zflzgffvhs09b40000gn/T/TemporaryItems/NSIRD_screencaptureui_hbAJdP/%D0%97%D0%BD%D1%96%D0%BC%D0%BE%D0%BA%20%D0%B5%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202025-08-23%20%D0%BE%2022.03.26.png)

### - command "/talk":
![Знімок екрана 2025-08-23 о 22.04.24.png](../../../../../../var/folders/km/4gfqcl3s75zflzgffvhs09b40000gn/T/TemporaryItems/NSIRD_screencaptureui_kMs3hp/%D0%97%D0%BD%D1%96%D0%BC%D0%BE%D0%BA%20%D0%B5%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202025-08-23%20%D0%BE%2022.04.24.png)

### - command "/quiz":
![Знімок екрана 2025-08-23 о 22.05.46.png](../../../../../../var/folders/km/4gfqcl3s75zflzgffvhs09b40000gn/T/TemporaryItems/NSIRD_screencaptureui_7igwg8/%D0%97%D0%BD%D1%96%D0%BC%D0%BE%D0%BA%20%D0%B5%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202025-08-23%20%D0%BE%2022.05.46.png)


This is not a final version of the telegram-bot, and I will try to improve it in the future when I have more knowledge and skills :)
