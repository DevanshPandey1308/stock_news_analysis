# 📈 Stock News WhatsApp Alert System

A Python automation that tracks daily stock price movements and sends related news updates directly to WhatsApp using the Twilio API. When the stock price changes more than 1%, the script fetches the top 3 news articles and delivers them as formatted WhatsApp alerts.

🚀 Features
- Fetches daily stock prices using Alpha Vantage  
- Detects significant price changes  
- Retrieves latest company news from NewsAPI  
- Sends WhatsApp alerts via Twilio  
- Uses `.env` for secure credential handling

🔧 Setup
1.Install dependencies:
pip install -r requirements.txt

2.Create a .env file:
STOCK_API_KEY=YOUR_ALPHA_VANTAGE_KEY
NEWS_API_KEY=YOUR_NEWSAPI_KEY
TWILIO_SID=YOUR_TWILIO_SID
TWILIO_AUTH_TOKEN=YOUR_TWILIO_AUTH_TOKEN
TWILIO_PHONE=whatsapp:+1415XXXXXXX
MY_PHONE=whatsapp:+91XXXXXXXXXX

3.Run the script:
python main.py

📂 Project Structure
main.py
requirements.txt
README.md
whatsapp_screenshot.jpg


*Built by DEVANSH PANDEY*

