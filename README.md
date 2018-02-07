# TelegramBotBash
A simple script to send messages using Telegram bot.
Based on monit2telegram.

## Requirements
* Bash
* CURL
* Telegram Bot

## Usage

Put `tlgSend.sh` and `tlg.conf.example` to `/home/user` and make them 

executable, rename `tlg.conf.example`.

Put your `Telegram Bot Token` and `Chat ID` in `tlg.conf`.

Your can test TelegramBotBash script by running this command.
```console
# tlgSend.sh -c /home/user/tlg.conf -m "Test msg"
Sending message 'Test msg' to 15867544
Done!
#
```
And check your Telegram.
