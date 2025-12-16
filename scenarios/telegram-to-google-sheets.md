# Telegram → Google Sheets Automation

## Overview
This automation captures messages from a Telegram bot and automatically logs them into Google Sheets.

It is useful for:
- Lead collection
- Order tracking
- Content submissions
- Simple data capture workflows

---

## Tools Used
- Telegram Bot
- Make.com
- Google Sheets

---

## Workflow Description
1. A user sends a message (text or image) to a Telegram bot
2. Make.com receives the message
3. The data is parsed and formatted
4. A new row is added to Google Sheets

---

## Key Configuration Notes
- Telegram bot token is stored securely in Make.com
- Google Sheets access is authenticated using Google OAuth
- Error handling is added to prevent duplicate entries

---

## Common Issues & Fixes
- Messages not appearing → Check webhook / polling trigger
- Empty rows → Verify field mapping in Make.com
- Permission errors → Reconnect Google account

---

## Outcome
This automation removes manual data entry and provides real-time logging of Telegram messages into Google Sheets.
