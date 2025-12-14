# Travel Booking Automation (n8n)

## Problem
Manual handling of travel inquiries leads to delays and lost leads.

## Solution
This workflow:
- Captures booking requests
- Validates travel dates
- Fetches pricing
- Sends confirmation via Email / WhatsApp
- Stores data in Google Sheets / CRM

## Workflow Steps
1. Webhook trigger
2. Data validation
3. API integration
4. Notification
5. Storage

## How to Import
- n8n → Import Workflow → Upload JSON

## Environment Variables

Set the following environment variables in n8n:

```env
TAVILY_API_KEY=your_api_key_here
SERPAPI_KEY=your_serpapi_key_here
GMAIL_FROM_ADDRESS=your_email@example.com