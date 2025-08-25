![Static Badge](https://img.shields.io/badge/open--ai--telegram--bot-white?style=for-the-badge&logo=probot&logoColor=blue&labelColor=black&color=white) ![PyPI - Python Version](https://img.shields.io/pypi/pyversions/python-telegram-bot?style=for-the-badge&logo=Python&logoColor=blue&labelColor=black&color=white) ![Static Badge](https://img.shields.io/badge/Telegram-white?style=for-the-badge&logo=Telegram&logoColor=blue&labelColor=black&color=white) ![Static Badge](https://img.shields.io/badge/ChatGPT-black?style=for-the-badge&logo=openai&logoColor=blue&labelColor=black&color=white)

# 🤖 OpenAI Telegram Bot

Telegram bot that integrates with OpenAI to provide various interactive features including random facts, GPT chat interface, words translate and personality-based conversations.

Feel the full power of chatGPT assistant!

## 🔧 Setup

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
   python src/bot/bot.py
   ```

## ✨ Features

- `/start` - welcome message with main menu 
- `/random` - random fact generator with GPT assistant 
- `/gpt` - direct GPT chat interface  
- `/talk` - personality-based conversations (Cobain, Hawking, Nietzsche, Queen, Tolkien)
- `/quiz` - quiz functionality (you can test your knowledge in various fields, such as: history, science, art, sports)
- `/translate` - functionality that allows you to translate any word into several different languages

## ❗ Requirements

- Python 3.8+
- Telegram Bot Token (from @BotFather)
- OpenAI API Key

## 👷 Examples of how the bot works

### 1. command `/start`:

- _general command to start the bot and display its capabilities_

![](src/resources/screenshots/screenshot1.png)

### 2. command `/random`:

- _this functionality provides the ability to generate any random fact_

![](src/resources/screenshots/screenshot2.png)

### 3. command `/gpt`:

- _this functionality allows you to ask anything in the chatGPT_

![](src/resources/screenshots/screenshot3.png)

### 4. command `/talk`:

_this functionality allows you to ask anything to several famous personalities_

![](src/resources/screenshots/screenshot4.png)

- _I choose "Стівен Хокінг (Stephen Hawking)"_

![](src/resources/screenshots/screenshot4.1.png)

### 5. command `/quiz`:

- _this functionality provides the opportunity to test knowledge in several different fields (history, science, art, sports)_

![](src/resources/screenshots/screenshot5.png)

- _I choose "Історія (History)"_

![](src/resources/screenshots/screenshot5.1.png)

### 6. command `/translate`:
 
- _this command allows you to translate any word into several different languages_

![](src/resources/screenshots/screenshot6.png)

- _I choose "Англійська (English)"_ 

![](src/resources/screenshots/screenshot6.1.png)

_This is not a final version of the bot, I will improve it in the future!_