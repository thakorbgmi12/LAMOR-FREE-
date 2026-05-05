# Telegram Bot

A Telegram bot for managing attack requests with admin approval system, MongoDB database, and external API integration.

## Features Lamor Gaming BOT

- 🔐 User approval system with expiration dates
- 👑 Admin commands for user management
- 📊 Attack statistics and logging
- 🚫 Blocked ports validation
- 💾 MongoDB database for persistent storage
- 🔄 24/7 deployment ready (Railway, Heroku, etc.)

## Prerequisites

- Python 3.11 or higher
- MongoDB database (Atlas or local)
- Telegram Bot Token (from @BotFather)
- External API endpoint with authentication key

## Environment Variables Setup

Create a `.env` file in the root directory with the following variables:

```env
BOT_TOKEN = "8575268232:AAGMCI4-kYDS8JzPNJ1MY0RCyYFlOU5zBWk"
MONGODB_URI = "mongodb+srv://thakorbgmi12_db_user:qx21sg6gDWRqGnMw@cluster0.getqxcf.mongodb.net/?appName=Cluster0"
DATABASE_NAME = "akku1733"
API_URL = "https://vehicular-perpetual-profile.ngrok-free.dev/attack"
API_KEY = "akku_pc"
ADMIN_IDS = [5399774279]
```
