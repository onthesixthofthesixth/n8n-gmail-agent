# n8n Gmail Agent

An n8n AI Agent workflow that reads my latest 5 unread Gmail emails, summarises each in one line with an OpenAI chat model, and emails the five summaries back to me as a single message.

## Files
- `Unread_Email_Summariser.json`: the exported n8n workflow
- `docker-compose.yml`: runs n8n locally in Docker

## Run it
1. `docker compose up -d`
2. Open http://localhost:5678
3. Import the workflow JSON and connect your Gmail and OpenAI credentials
