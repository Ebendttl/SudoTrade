# SudoCat AI Trading Assistant (SudoTrade) 🤖

A Telegram bot that provides AI-powered trading insights using SudoCat's platform. Get real-time market analysis, sentiment predictions, and trading signals directly in your Telegram chat.

[![Python Version](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Built with SudoCat](https://img.shields.io/badge/Built%20with-SudoCat-purple.svg)](https://sudocat.ai)

## 🌟 Features

- Real-time market sentiment analysis
- AI-powered trading signals
- Personalized trading recommendations
- Portfolio tracking
- Automated market alerts
- User preference management

## 🛠️ Built With

Python 3.8+ | FastAPI | SQLite | SudoCat API | Hugging Face Transformers | python-telegram-bot | aiohttp | Git | GitHub Actions | Docker | pytest | Telegram Bot API | Redis | Railway | python-dotenv | PyJWT

## 🚀 Quick Start

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/sudocat-trading-bot.git
cd sudocat-trading-bot
```

2. **Set up virtual environment**
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
.\venv\Scripts\activate  # Windows
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

4. **Set up environment variables**
Create a `.env` file in the project root:
```env
TELEGRAM_BOT_TOKEN=your_telegram_token
SUDOCAT_API_KEY=your_sudocat_api_key
REDIS_URL=your_redis_url
```

5. **Run the bot**
```bash
python bot.py
```

## 📖 Usage

Start chatting with the bot on Telegram:

- `/start` - Begin interaction with the bot
- `/analyze` - Get market sentiment analysis
- `/signals` - Receive trading signals
- `/portfolio` - View your portfolio
- `/settings` - Configure your preferences

## 🏗️ Project Structure

```
sudocat-trading-bot/
├── bot.py
├── config.py
├── requirements.txt
├── README.md
├── LICENSE
├── tests/
│   ├── __init__.py
│   └── test_bot.py
├── src/
│   ├── __init__.py
│   ├── handlers/
│   ├── services/
│   └── utils/
└── docs/
    └── api.md
```

## 🧪 Testing

Run the test suite:
```bash
pytest tests/
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [SudoCat](https://sudocat.ai) for their amazing AI platform
- [python-telegram-bot](https://python-telegram-bot.org/) community
- All contributors and supporters

## 🔗 Links

- [Live Demo](https://t.me/your_bot_username)
- [Documentation](docs/api.md)
- [Issue Tracker](https://github.com/yourusername/sudocat-trading-bot/issues)

Project Link: [https://github.com/ebendttl/SudoTrade](https://github.com/ebendttl/SudoTrade)
