<!-- About: AI booking assistant demo: checks availability and books appointments via the Altegio API (n8n + OpenAI). -->
<!-- Topics: n8n, openai, ai-assistant, booking, altegio, automation, chatbot -->

# Altegio AI Booking Assistant

A demo AI assistant that talks to clients in chat, checks free slots and creates bookings through the **Altegio API**. Built with **n8n** and **OpenAI**.

> Demo project by [Morrowen State](https://morrowenstate.com). Not a client deployment.

## What it does
- Answers questions about services and prices
- Checks available time slots in Altegio
- Creates a booking once the client confirms
- [TODO: add or remove points so the list matches what the workflow actually does]

## How it works
```
Client message → n8n webhook → OpenAI (understands the request)
              → Altegio API (services, free slots, booking) → reply to client
```

## Stack
n8n · OpenAI API · Altegio API · [TODO: chat channel, e.g. Telegram / website widget]

## Run it yourself
1. Import `workflow.json` into n8n.
2. Add credentials: OpenAI API key, Altegio partner token and user token, company ID.
3. Activate the workflow and send a test message to the webhook.

## Screenshots / demo
[TODO: add a screenshot of the workflow and a short chat video]
