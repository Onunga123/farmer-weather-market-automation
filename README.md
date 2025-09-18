# 🌦 n8n Farm Advisory Automation

This project is a fully automated farm advisory system built using [n8n](https://n8n.io).

## 📋 Features
- Fetches real-time weather data from [OpenWeather](https://openweathermap.org/)
- Pulls latest crop market prices from [Google Sheets](https://docs.google.com/spreadsheets/)
- Combines both into one advisory message
- Sends alerts via:
  - WhatsApp using [Twilio](https://www.twilio.com/)
  - Email using [Brevo](https://www.brevo.com/)

## ⚙️ How It Works
- Runs automatically every 6 hours
- Gives weather-based farming advice (irrigation, harvesting, storm prep)
- Highlights best crop and market price

## 📁 Files
- `weather-market-automation.json` — the n8n workflow

## 🚀 Usage
1. Import the JSON file into your n8n instance
2. Add credentials for:
   - Twilio (WhatsApp)
   - Brevo (Email SMTP)
   - Google Sheets
   - OpenWeather API Key
3. Activate the workflow
