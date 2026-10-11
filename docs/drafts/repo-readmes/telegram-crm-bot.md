<!-- About: Telegram bot that collects leads into a simple Google Sheets CRM (n8n). -->
<!-- Topics: telegram-bot, n8n, google-sheets, crm, automation -->

# Telegram CRM Bot

A Telegram bot that collects client requests and stores them in **Google Sheets** as a lightweight CRM. Built with **n8n**. Made as a draft for a fitness trainer's lead handling.

> Draft / demo project. Before publishing, remove any real names, phone numbers, tokens and sheet IDs.

## How it works
```
Telegram → n8n (Telegram Trigger) → validate + format → Google Sheets row → confirmation message
```

## Stack
Telegram Bot API · n8n · Google Sheets

## Run it yourself
1. Create a bot with @BotFather and get the token.
2. Import the workflow into n8n, add Telegram and Google Sheets credentials.
3. Create a sheet with columns: [TODO: e.g. Date, Name, Contact, Request, Status].
