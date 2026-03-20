☁️ Weather Forecast Telegram Bot
A feature-rich Telegram bot developed in Python that provides real-time weather updates and visual forecasts using the wttr.in service. It features interactive dialogues, ASCII art, and a collection of fascinating weather facts.

🌟 Key Features
Current Weather (/w): Get a detailed text-based report of the current weather in any city.

Visual Forecast (/pw): Receive a generated PNG image showing the weather forecast for the next few days.

Weather Facts (/fact): Over 15+ intriguing facts about meteorology and natural phenomena.

Interactive UI: Uses Telegram stickers, emojis, and ASCII art for a better user experience.

Conversation Handling: Smooth city input flow with the ability to /cancel at any time.

Console Branding: Features a custom "PurpleCat" startup sequence with colored logs.

🛠 Tech Stack
Language: Python 3.x

API Wrapper: python-telegram-bot (v13.x)

HTTP Client: requests

Styling: colorama (for terminal output)

Weather Source: wttr.in

📋 Commands
Command	Description
/start	Welcome message and initial instructions.
/w	Request current weather for a specific city.
/pw	Get a multi-day visual weather forecast (Image).
/fact	Displays a random interesting weather fact.
/help	Shows the command list and help menu.
/cancel	Stops the current city input process.
