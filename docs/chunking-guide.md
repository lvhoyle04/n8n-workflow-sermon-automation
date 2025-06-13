# Chunking Guide for Large Audio Files

## Why Chunk Audio Files?

Many audio-to-text transcription services (like OpenAI’s Whisper API) have file size limits — for example, 25MB per file. If your sermon MP3 is larger than that, it must be split into smaller segments (called "chunks").

## Chunking Methods

### 1. Manual (Pre-upload)

Use a free tool like [Audacity](https://www.audacityteam.org/) to:
- Import the MP3
- Split it into 5–10 minute segments
- Export each segment as a new MP3 file

### 2. Automated (Future Option)

Consider scripting with:
- Python + `pydub`
- FFmpeg CLI
- A node in n8n that splits large files (future enhancement)

## Recommendation

Until automation is added, manually chunk any file over 20MB before uploading for transcription.
