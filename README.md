**GrainBot** is a Python-powered Discord bot that automatically fetches, stores, and displays grain prices (wheat, corn, soybeans, and canola) from multiple grain elevator locations near Ryder, North Dakota. It provides daily updates, historical graphs, and GPT-powered analysis—all organized neatly in Discord channels.

---

## Features

- **Daily Price Updates**  
  Scrapes and posts daily commodity prices per location (e.g., TriGen Ryder, CHS Garrison) to dedicated text channels.

- **Historical Graphing**  
  Tracks price trends over time and auto-posts graphs in a separate channel.

- **GPT-Based Q&A**  
  Lets users ask questions like “Which location has the most stable wheat prices?” using OpenAI’s GPT-3.5 API.

- **Market Overview Reporting**  
  Cross-location comparisons showing top prices, trends, and value insights each day.

---

## Channel Structure (per Location)

Each grain elevator gets its own Discord category with:

- `#daily-prices` – Daily scraped price list
- `#price-graphs` – Auto-generated visual trends
- `#ask-the-bot` – GPT-powered question-and-answer

A shared **Market Overview** category shows:

- `#top-prices-daily` – Best price by commodity
- `#price-comparison` – Side-by-side prices across all elevators
- `#market-analysis` – GPT cross-location insights

---

## Setup Instructions

1. **Clone the Repo**
   ```bash
   git clone https://github.com/yourusername/grainbot.git
   cd grainbot

2. Install Dependencies

pip install -r requirements.txt


3. Set Up Your .env File

DISCORD_TOKEN=your_discord_bot_token
OPENAI_API_KEY=your_openai_api_key


4. Run the Bot

python bot.py




---

Data Sources

Currently integrated with:

TriGen Ag Partners – Ryder

Additional elevators to be added (CHS, Max Farmers, etc.)


Note: Some data may require JavaScript scraping (Selenium) or API access.


---

Stretch Goals (In Progress)

Admin dashboard to manage elevator listings

SMS or email alerts when prices cross user-defined thresholds

Web-based frontend for easier price visualization



---

Contributing

Pull requests are welcome! If you have suggestions for new features or locations, feel free to open an issue or fork the project.
