# TG_BOT_GUIDE

# Hyperbolic AI Telegram Bot 🤖

A feature-rich Telegram bot integrating Hyperbolic.xyz's AI models for text generation, image creation, and audio synthesis.

- **Bot Link** : https://t.me/Hyperbolic25_Bot
## 📚 Features
- **Multi-Model Support**:
  - 📝 Text Generation (4 models)
  - 🖼️ Image Generation (2 models)
  - 🔊 Audio Synthesis (1 model)
- Secure API key management
- Interactive model selection
- Session-based interactions
- Easy switching between AI models

## 📋 Prerequisites
- Node.js v16+ 
- npm/yarn
- Telegram account & bot token
- [Hyperbolic.xyz](https://hyperbolic.xyz/) API key

## 📥 Installation
1. **Install Node.js and npm if not installed already**
```bash
curl -sSL https://raw.githubusercontent.com/zunxbt/installation/main/node.sh | bash
```
2. **Clone Repository**
```bash
rm -rf hyperbolic-bot && git clone https://github.com/zunxbt/hyperbolic-bot.git && cd hyperbolic-bot
```
3. **Install dependencies**
```bash
npm install axios@^1.8.3 dotenv@^16.4.7 telegraf@^4.16.3 telegraf-session-local@^2.1.1
```

4. **Install `screen` and `nano` package**
```bash
sudo apt update && sudo apt install -y screen nano
```

## ⚙️ Configuration
1. **Get Telegram Bot Token**
- Open Telegram and search for @BotFather
- Create new bot with /newbot
- Copy the provided HTTP API token

2. **Get Hyperbolic API Key**
- Sign Up or Log In at [Hyperbolic Website](https://hyperbolic.xyz)
- Go to Settings → API Keys
- Create/copy your API key

## 🛠️ Environment Set Up
- Create `.env` file using the below command
```bash
nano .env
```
- Now input your Telegram Bot Token
```bash
TELEGRAM_BOT_TOKEN=your_telegram_bot_token
```
- Now save this file using `Ctrl + X` and then `Y` and then press `Enter`

## ⚡ Run the bot
- Create a screen session
```bash
screen -S hyperbolic
```
- Now run the below command
```bash
node bot.js
```
- Now detach from this screen session using `Ctrl + A`, then press `D`

## 📜 Commands

| Command    | Description            |
|------------|------------------------|
| `/start`   | Start the bot          |
| `/switch`  | Change model           |
| `/remove`  | Remove API key         |
| `/help`    | Show commands          |

## 🔒 Security
- API keys stored only in session memory
- Keys automatically cleared with /remove command
- No persistent storage of credentials

## 🔒 HOW TO WRITE CODE IN COPIABLE FORMAT

![HOW TO WRITE CODE IN COPIABLE FORMAT](https://github.com/singhsarit/TG_BOT_GUIDE/blob/main/Screenshot%202025-03-18%20124144.png)
