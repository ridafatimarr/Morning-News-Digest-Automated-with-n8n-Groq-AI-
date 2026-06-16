# Morning News Digest Automated with n8n & Groq AI
An AI-powered news intelligence workflow that automatically collects, filters, summarizes, and delivers the most important daily news articles as a concise morning briefing using n8n and Groq AI.
# 💡 What This Project Does

Every day at 7:00 AM (PKT), the system quietly runs in the background and:

* Pulls the latest headlines from Google News RSS
* Removes spam, clickbait, and unreliable stories
* Uses AI to summarize each article clearly and concisely
* Selects the most important 10 stories
* Sends everything in a clean, readable email

* No dashboards. No manual work. Just news that makes sense.

# How It Works (Behind the Scenes)
*  Scheduled Trigger (n8n)
The workflow automatically starts every morning.
*  News Collection
Latest articles are fetched from Google News RSS feeds.
*  Smart Filtering
Low-quality or clickbait content is filtered out.
*  AI Summarization (Groq LLaMA 3)
Each article is rewritten into a short, meaningful summary.
*  Email Builder
A clean HTML email is generated with top stories.
*  Delivery via Gmail
The final digest lands directly in your inbox.
# Tech Stack
Tool	What it does
* n8n	Automates the entire workflow
* Groq AI (LLaMA 3)	Summarizes news intelligently
* Google News RSS	Provides real-time news feed
* Gmail	Sends the final email digest
