Cloudflare Serverless Unban Bot

A production ready Telegram bot built with aiogram 3 and Python 3.11 for group spam management and blacklist exports.

Features
Automated group spam detection
Cloudflare Workers zero cost hosting guidance
Blacklist data export tools

Local Setup
1. Clone the repository.
2. Create a virtual environment: python3.11 -m venv venv && source venv/bin/activate
3. Install dependencies: pip install -r requirements.txt
4. Copy .env.example to .env and insert your BOT_TOKEN.
5. Run the bot: python main.py

Deployment Guide
Deploy easily on Render or Koyeb using a standard Python web service or background worker.
