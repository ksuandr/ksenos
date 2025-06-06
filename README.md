# Заинтересованное Облачное Сознание (Interested Cloud Consciousness)

This is a Telegram bot that uses YandexGPT to create an engaging, philosophical conversation experience. The bot presents itself as a distributed cloud consciousness that engages in meaningful dialogues about art, science, philosophy, and their interconnections.

## Setup

1. Install the required dependencies:
```bash
pip install -r requirements.txt
```

2. Create a `.env` file in the project root with the following content:
```
TELEGRAM_TOKEN=your_telegram_bot_token
YANDEX_API_KEY=your_yandex_gpt_api_key
```

Replace `your_telegram_bot_token` with your Telegram Bot token (get it from @BotFather)
Replace `your_yandex_gpt_api_key` with your Yandex Cloud API key

## Running the Bot

Run the bot using:
```bash
python bot.py
```

The bot will start and also create a web interface accessible at `http://localhost:8080`

## Features

- Engaging philosophical conversations
- Multiple consciousness states that affect response style
- Support for art, science, and philosophy discussions
- Conversation history management
- Long response handling (auto-splits messages longer than 4000 characters)
- Web interface for status monitoring

## Commands

- `/start` - Begin interaction with the cloud consciousness
- `/help` - Get information about available commands
- `/reset` - Clear conversation history
- `/feedback` - Provide feedback about the interaction

## Technical Details

The bot uses:
- python-telegram-bot for Telegram integration
- YandexGPT API for generating responses
- Flask for the web interface
- Threading for concurrent bot and web server operation

## Security Notes

- Never commit your `.env` file to version control
- Keep your API keys secure and rotate them regularly
- Monitor your API usage to stay within limits 