# n8n_automation workflows

This repository contains three AI-powered automation workflows built using :contentReference[oaicite:0]{index=0}. These workflows integrate Telegram, Gmail, Google Calendar, and OpenAI to automate messaging, email handling, and event scheduling.

---

## Workflows Included

### 1. TelegramBot.json — AI Telegram Chatbot
- Receives messages from Telegram
- Uses OpenAI to generate intelligent replies
- Sends responses back automatically

**Use case:** Personal AI assistant, chatbot automation

---

### 2. EmailAgent.json — AI Email Assistant
- Reads emails from Gmail
- Generates professional summaries
- Sends formatted responses if needed

**Use case:** Email summarization, inbox automation

---

### 3. AddCalendarEvent.json — AI Calendar Scheduler
- Accepts scheduling requests via Telegram
- Extracts event details using AI
- Creates events in Google Calendar automatically

**Use case:** Automated meeting scheduling

---

## Requirements

- n8n (cloud or self-hosted)
- OpenAI API key
- Telegram Bot credentials
- Gmail OAuth2 credentials
- Google Calendar OAuth2 credentials

---

## Setup Instructions

1. Open n8n dashboard  
2. Click **Workflows → Import from File**  
3. Import:
   - `TelegramBot.json`
   - `EmailAgent.json`
   - `AddCalendarEvent.json`
4. Add your credentials in n8n
5. Activate workflows
