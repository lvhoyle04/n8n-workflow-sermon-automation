# 📖 Sermon Publishing Automation with n8n

A fully automated pipeline to publish, transcribe, blog, and promote sermons using [n8n](https://n8n.io), REST APIs, and AI tools. This project was developed as part of my 13-week internship focused on streamlining sermon media workflows for church and ministry platforms.

---

## 🔧 Purpose

This project automates the full sermon publishing workflow from recording to outreach, reducing human workload and increasing consistency across platforms like WordPress, YouTube, and SermonAudio.

---

## ⚙️ Key Features

- 🎙 **Sermon Ingestion**: Detects new uploads on SermonAudio
- 📝 **Transcription**: Sends audio to AI transcription (e.g. Whisper or AssemblyAI)
- ✍️ **Blog Post Generation**: Automatically generates and uploads sermon blog posts
- 📣 **Social Media Posts**: Creates social captions for platforms like Facebook or X
- 🎬 **YouTube Uploads**: Publishes full sermons and auto-generated Shorts
- ✅ **Human Approval Integration**: Optionally routes content for human review

---

## 🗂 Workflow Overview

1. **Trigger**: Detect new sermon on SermonAudio
2. **Transcribe**: Send audio to AI transcription service
3. **Post Creation**: Generate and upload blog + WordPress post
4. **Promote**: Auto-create social content and schedule
5. **Video Upload**: Upload to YouTube with SEO metadata
6. **Shorts**: Auto-generate YouTube Shorts from transcript highlights

---

## 🛠 Tools Used

- 🧩 [n8n](https://n8n.io/) – Automation platform
- 🧠 OpenAI / Whisper – AI transcription & content generation
- 🎥 YouTube Data API – Uploading full videos and Shorts
- 🖋 WordPress REST API – Creating and updating blog posts
- 📊 Google Sheets – Logging progress and content queue

---

## 🧪 Getting Started

1. Clone the repo
2. Install and launch n8n
3. Set up API credentials in `.env` or within n8n
4. Import the included workflow file (`workflow.json`)
5. Test with a dummy sermon audio or run full process

---

## 🧾 Internship Context

This project was created during my internship at Five More Talents (5MT), where I was tasked with:
- Researching and designing the workflow
- Writing automation logic in n8n
- Integrating APIs from various platforms
- Documenting the process for non-technical users

---

## 📄 License

MIT License

---

## ✉️ Contact

**Lukas Hoyle**  
Cybersecurity Major | Anderson University (SC)  
linkedin.com/in/lukas-hoyle-411003325


