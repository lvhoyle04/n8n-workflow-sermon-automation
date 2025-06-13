# Transcription Workflow

This branch contains the n8n workflow for transcribing sermon audio (MP3 files) into clean, paragraph-formatted text using a speech-to-text API.

## Purpose

Transcripts help improve accessibility, search engine visibility, and content reuse (e.g., for blogs or social posts).

## Workflow Summary

- Input: MP3 file URL
- Output: Full-text transcript (cleaned and formatted)
- Tools: OpenAI Whisper API (or Deepgram), n8n, semantic text splitter

## Key Features

- Accepts remote MP3 URLs via HTTP
- Supports file size limits through manual chunking
- Can integrate semantic paragraph splitting
- Optionally stores transcript in middleware (e.g., Google Docs)

## Files in This Branch

- `transcription-workflow.n8n.json`: Main n8n flow file
- `docs/chunking-guide.md`: Explains how to split large MP3s
- `docs/notes-transcription.md`: Overview and limitations of the workflow

## Next Steps

- Automate chunking for large audio files
- Add transcript language detection
- Enable multiple output destinations (Docs, WordPress, etc.)
