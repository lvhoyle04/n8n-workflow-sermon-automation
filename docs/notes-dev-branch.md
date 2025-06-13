# Dev Branch Helper Notes

This document tracks what’s currently being built, tested, or integrated in the `dev` branch.

---

## 📌 Purpose of This Branch

This branch is used to combine and test workflows from all feature branches before they are finalized and merged into `main`. It’s where bugs get worked out, prompts are refined, and edge cases are handled.

---

## 🔧 Currently Being Worked On

### ✅ Transcription Workflow
- ✅ Connected to OpenAI Whisper API
- ⏳ Still needs automated chunking for 25MB+ audio files
- ⏳ Reviewing semantic paragraph splitting

### ✅ Blog Draft Workflow
- ✅ Accepts transcripts
- ✅ Runs blog generation using OpenAI
- ⏳ Output formatting and SEO keyword integration under review

### ✅ Shorts Workflow
- ⌛ Testing OpusClip and Pictory integration
- ⏳ Waiting for confirmation on which tool to standardize
- ⏳ May add a manual middleware review step before upload

---

## 📁 Files Being Actively Updated

| File Name                             | Status          |
|--------------------------------------|------------------|
| `transcription-workflow.n8n.json`    | Integrating final error handling |
| `generate-blog-from-transcript.n8n.json` | Under formatting review |
| `youtube-shorts-generator.n8n.json`  | Running clip-length validation |

---

## 🛠️ Next Steps in Dev

- Combine all workflows into one test suite
- Add shared environment variables or constants (e.g. API keys, chunk limits)
- Confirm all outputs write cleanly to middleware (Google Docs or Airtable)
- Prepare individual pull requests from each working workflow into `main`

---

## 📓 Notes

- Do not merge this branch into `main` directly
- Use this space to log what you're trying, what's breaking, and what you're fixing
