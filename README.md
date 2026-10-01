uni-announcements-bot/
├── config.json          # Target URLs, WhatsApp recipient numbers, and check frequency
├── tracker.json         # Local data file to store processed announcement IDs
├── scraper.py           # Logic to fetch and parse the HTML page
├── notifier.py          # Logic to handle WhatsApp messaging logic
├── storage.py           # Read/write methods for tracker.json
├── main.py              # Core execution loop orchestrating Scrape -> Filter -> Notify -> Save
├── requirements.txt     # Dependency list (or package.json if using Node.js)
└── .env                 # API keys or session tokens (keep out of git)