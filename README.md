# shell-bot-telegram Project

This project contains a bot implemented in Python. The bot is designed to perform certain tasks based on the settings configured.

## Features

1. **Logging**: The bot has a logging feature that helps in debugging and tracking the bot's activities.

2. **Settings Validation**: The bot validates the settings to ensure it is configured correctly. If the bot is public and does not have CMD_WHITE_LIST or ONLY_SHORTCUT_CMD set, it raises a ValueError.

## Installation

Follow the steps below to install and run the bot:

1. Clone the repository:

   ```
   git clone https://github.com/3Kmfi6HP/shell-bot-telegram.git
   ```

2. Navigate to the project directory:

   ```
   cd shell-bot-telegram
   ```

3. Install the required dependencies:

   ```
   pip install -r requirements.txt
   ```

4. Run the bot:

   ```
   python bot.py
   ```

Please ensure to update the settings.py file with the correct configurations before running the bot.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
