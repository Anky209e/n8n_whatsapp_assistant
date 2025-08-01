# WhatsApp + Google Drive Automation Bot (n8n)

This workflow receives WhatsApp commands via Twilio (like `LIST /folderId`), fetches file listings from Google Drive, and replies with formatted results.

## ✅ Features
- WhatsApp webhook via Twilio
- Command parser for `LIST /folder`
- Google Drive folder file listing
- Beautiful WhatsApp replies

## 📦 How to Use
1. Import `whatsapp_drive_bot.json` into your n8n instance
2. Configure:
   - Google Drive OAuth credentials
   - Twilio Auth (Basic Auth in HTTP node)
   - Replace webhook URL with your own if self-hosted

