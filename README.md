# Telegram bot template
A template for Telegram bots made with Python

### Installation instructions
1. Install [Poetry](https://python-poetry.org/) for managing dependencies
2. Create your Telegram bot by [speaking to Botfather](https://t.me/botfather)
3. Add your bot token to the environment variable: TELEGRAM_BOT_TOKEN (if you want to change the variable
name, you can find it in the file `telegram_bot_template/constants.py`)
4. Fork and clone the repository (and cd into it)
5. Create a virtual environment and install dependencies by running `python3 -m venv .venv` and `poetry install`
6. Ensure you are using the local Python with `poetry shell`
7. Run the bot with the command `bot` (this can be changed by modifying
the section `[tool.poetry.scripts]` in `pyproject.toml`). You can also use the `--debug` or `-d` flag to set log
level to debug (defaults to info).

### Adding new commands to your bot
Commands in `telegram_bot_template/extensions/commands/` are automatically loaded. Check out the example `start` command.
