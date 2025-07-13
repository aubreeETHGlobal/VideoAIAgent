# ETHGlobal AI Event Video Automation

---

## 🚀 Overview

This project is a **fully-automated, AI-powered workflow** for ETHGlobal event videos.  
It transforms hours of manual work into minutes using a team of AI agents to generate:

- Summaries
- Chapters
- Keywords
- YouTube and Drive links
- Partner notification messages

All outputs are beautifully and automatically filled into a **presentable Google Sheet** with clickable hyperlinks.  
No copy-paste or reformatting is needed.

---

## 🎯 Problem We Solved

Collaborating on ETHGlobal event content used to mean:

- Juggling video uploads, transcripts, links, and summaries by hand
- Writing YouTube chapters, descriptions, keywords manually
- Creating partner outreach one-by-one
- Spreadsheets with ugly, unclickable URLs

This cost us **3–4+ hours per 10 videos** and wasted valuable team time.

---

## 💡 Solution

With our AI pipeline:

- **One upload:** Drop a video and transcript Google Doc in "Video Uploads" and "Transcripts" on Google Drive
- **Instant magic:**
  - AI agents auto-detect new videos
  - Parse event/speaker/partner info from file names (no manual entry)
  - Extract YouTube links, summary, chapters, keywords
  - Fill a Sheet row with all info, using human-friendly hyperlinks/buttons
  - Draft a ready-to-send notification for partners (Telegram/email)
- **Scalable:** Works for 1 or 100 videos—same number of clicks
- **Presentable:** All deliverables are ready for sharing or publishing

---

## ⚡️ Why This Matters

- **Saves 90%+ operational time**
- **Zero copy/paste**
- **Error-proof data**
- **Instantly shareable across teams/partners**
- Beautiful, scalable, and "plug and play" for new events

---

## 🛠️ How To Use

1. **Prepare folders:**  
   - `Video Uploads` (for edited .mp4 files)  
   - `Transcripts` (matching Google Docs, title matches video)
   - Both shared with the Google service account

2. **Prepare your event videos and transcripts:**  
   - Transcript Doc title must exactly match the video.

3. **Run the agent:**  
   - Click "Run" in the Python/Replit project.
   - Within seconds, you’ll get:
       - A clickable Google Sheet row for every video
       - Summaries, chapters, keywords, notification drafts, and all links

4. **Share, publish, notify partners:**  
   - Use the Sheet’s links/messages to blast out to partners, YouTube, etc.

---

## 📋 Example Sheet Outputs

| Date Uploaded | Video Title | Event Name | Speaker(s) | Partner Organization | [Watch Video](#) | [View Transcript](#) | [Watch on YouTube](#) | Summary | Chapters | Keywords | Telegram Message | Notes |
|---------------|-------------|------------|------------|---------------------|------------------|---------------------|-----------------------|---------|----------|----------|------------------|-------|

(Columns shown as label, actual sheet contains clickable hyperlinks and message text)

---

## ✨ Demo Script (for Hackathon/Judges)

1. **Show "before":** Screenshot or description of manual process.
2. **Show Drive folders and Sheet—empty.**
3. **Upload** a video/transcript (or use your batch).
4. **Click "Run"** on Replit.
5. **Refresh Sheet**—point out hyperlinks, AI summary, telegram message.
6. **Highlight** time/output difference.
7. **Q&A:** Focus on code-free batching, extensibility ("Want YouTube auto-publishing? It's plug-and-play!").

---

## 🏆 Advanced/Edge Features

- SEO-optimized titles/hashtags (AI)
- Automated impact/engagement score (AI)
- Analytics tab for top speakers, partners, keywords
- Handles all video formats (solo, fireside, etc.)
- Batch-ready for 1 or 100+ assets

---

## 🧑‍💻 Setup/Dependencies

- Python 3.x (Replit, or local with `gspread`, `google-api-python-client`, `openai`)
- OpenAI API key (for GPT, stored as `OPENAI_API_KEY` in secrets)
- Google service account (for Drive/Docs/Sheets, plus enabled APIs)
- Service account credentials in `creds.json`, saved in your project

---

## ❤️ Made with love by Aubree at ETHGlobal  
Feedback, PRs and collaboration welcome!
