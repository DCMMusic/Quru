# F-Droid Search Bot

A Telegram bot for searching Apps in [F-Droid](https://f-droid.org/) repo

Made with [Pyrogram Smart Plugins](https://docs.pyrogram.org/topics/smart-plugins)

## Requirements

- Python 3.6 or higher
- A [Telegram API key](//docs.pyrogram.org/intro/setup#api-keys)
- A [Telegram bot token](//t.me/botfather)

## Run

1. `virtualenv venv` to create a virtual environment
2. `venv/bin/pip install -U -r requirements.txt` to install the requirements
3. Create a new `config.ini` file, copy-paste the following and replace the
   values with your own. Exclude or include plugins to fit your needs.
   Create `config.py` and add constants that are specified in module docstrings
   of enabled plugins.
   ```
   [pyrogram]
   api_id = 1234567
   api_hash = 0123456789abcdef0123456789abcdef
   bot_token = 123456:ABC-DEF1234ghIkl-zyx57W2v1u123ew11

   [plugins]
   root = plugins
   ```
4. Run with `venv/bin/python bot.py`
5. Stop with <kbd>CTRL+C</kbd>

## License

AGPL-3.0-or-later
