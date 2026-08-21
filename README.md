# AI News Summarizer using n8n and Google Gemini

An automated AI-powered news summarization system that collects
AI and technology news from RSS feeds, summarizes the content
using Google Gemini, and delivers a personalized newsletter
through Gmail.

## Problem Statement

Professionals spend significant time visiting multiple websites
to stay updated with the latest AI and technology news.

This project automates the entire process of collecting,
summarizing, and delivering important news.

## Solution

The AI News Summarizer automatically:

1. Runs at a scheduled time using n8n
2. Fetches news articles from RSS feeds
3. Aggregates the collected articles
4. Sends the content to Google Gemini
5. Generates concise summaries
6. Organizes AI and technology news
7. Sends the final newsletter through Gmail

## Technologies Used

- n8n
- Google Gemini
- Google AI Studio
- Google Cloud
- Gmail API
- RSS Feeds
- OAuth 2.0

## Workflow

Schedule Trigger
        ↓
RSS Feed
        ↓
Aggregate Articles
        ↓
Google Gemini
        ↓
Generate Summary
        ↓
Gmail
        ↓
Daily Newsletter

## Features

- Automated daily news collection
- Multiple RSS feed support
- AI-powered summarization
- Categorization of AI and technology news
- Concise newsletter generation
- Automated Gmail delivery
- OAuth 2.0 authentication

## News Categories

### AI News

The workflow collects and summarizes AI-related news.

### Technology Updates

The workflow also collects broader technology-related news.

## Example Output

AI NEWS

HEADLINE IN ALL CAPS

Summary of what happened and why it matters.

Link: Article URL

TECHNOLOGY UPDATES

HEADLINE IN ALL CAPS

Summary of the technology news.

Link: Article URL

## Setup

### Prerequisites

- n8n account
- Google account
- Google Cloud project
- Gemini API access
- Gmail API
- RSS feed URLs

### Import Workflow

1. Open n8n
2. Create a new workflow
3. Import `workflow/ai-news-summarizer.json`
4. Configure Google credentials
5. Configure RSS feeds
6. Configure Gmail
7. Activate the workflow

## Security

No API keys, OAuth secrets, passwords, or private credentials
are included in this repository.

Credentials must be configured separately in n8n.

## Future Improvements

- Add more news categories
- Add duplicate article detection
- Add article ranking
- Add personalized topics
- Add HTML email formatting
- Add Telegram/Slack delivery
- Add database storage for previously processed articles

## Author

Harshitha D Bangera
