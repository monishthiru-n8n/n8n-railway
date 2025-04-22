# n8n AI-Powered Stoic YouTube Shorts Automation

This project auto-generates faceless YouTube Shorts with:
- AI-generated Stoic quotes (OpenRouter)
- AI background images (Replicate)
- Random background music
- Daily CRON schedule at 6 PM
- YouTube upload via API

## 🚀 Deploy on Railway

1. Push this repo to GitHub.
2. Go to https://railway.app and create a new project from your GitHub repo.
3. Set environment variables from `.env.example` in Railway.
4. In Settings → Deploy:
   - Install Command: npm install
   - Start Command: npx n8n
5. Done! Visit your n8n UI at the Railway-provided URL.

Import the included workflow from the `workflow.json` file.