# kbot
A Telegram bot for printing its version!)

t.me/den_svarovsky_bot
@den_svarovsky_bot

## Installation

Required Go packages:

    github.com/spf13/cobra
    gopkg.in/telebot.v4


Clone the repository:
```bash
git clone https://github.com/yourusername/kbot.git
cd kbot
```

Set up your Telegram Bot Token:
```bash
export TELE_TOKEN="your_telegram_bot_token"
```

Build the application:
```bash
go build -ldflags "-X="github.com/DionisZ/kbot/cmd.appVersion=v1.0.2
```


## Usage

Start the bot:
```bash
./kbot start
```


## Available Commands

- `/s hello` - Get a greeting from the bot


## License

This project is licensed under the MIT License - see the LICENSE file for details.