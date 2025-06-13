# Transcription Workflow Overview

This workflow converts sermon audio (MP3 format) into clean, paragraph-formatted text using an audio-to-text service.

## Workflow Steps

1. Get MP3 file URL (uploaded to SermonAudio or other storage)
2. Send to OpenAI Whisper API (or another transcription API)
3. Receive full transcript
4. (Optional) Use semantic splitting to divide into readable paragraphs
5. Save transcript for use in blog posts, sermon metadata, or social posts

## Current Limitations

- File size limits (25MB for OpenAI API)
- Manual chunking required for large files
- Transcript accuracy depends on audio quality

## Next Steps

- Add auto-chunking node
- Add language detection or speaker tagging
