# ZYNZO AI Studio

Mobile-first AI YouTube production workspace.

## Deploy
Import this repo into Vercel and set `OPENAI_API_KEY` under Project Settings → Environment Variables. Never expose API keys in frontend code or commit them to GitHub. Ensure the API account has access and billing for the configured text, image and speech models. Then deploy.

## Included now
- Topic to script and 10-second scene storyboard
- Original title ideas and YouTube description
- AI thumbnail endpoint and narration endpoint
- Mobile UI, copy buttons and production-pack export

## Not yet automatic
This starter does not yet create video clips or render a finished MP4, and does not upload to YouTube. Those require a video-generation provider, rendering/storage worker and YouTube OAuth/Data API integration. AI image, text and speech use may incur charges. Review content and rights before publishing.
