# YouTube Shorts Generation Workflow

This branch contains the n8n workflow for automatically generating YouTube Shorts from full-length sermon videos.

## Purpose

To improve content engagement and reach new audiences through short-form video content.

## Workflow Summary

- Input: MP4 file or YouTube URL
- Output: Short MP4 clips under 60 seconds
- Tools: OpusClip, Pictory, Vizard, n8n

## Key Features

- Detects high-interest sermon moments (via AI)
- Cuts and renders short video clips
- Supports upload as unlisted Shorts to YouTube
- Compatible with middleware for manual review before publishing

## Files in This Branch

- `youtube-shorts-generator.n8n.json`: Main automation workflow
- `docs/notes-shorts-workflow.md`: Overview of the Shorts pipeline
- `tools/shorts-platform-comparison.md`: Pros and cons of various AI tools used

## Next Steps

- Add subtitle generation for each short
- Improve clip title generation using sermon metadata
- Automate thumbnail creation
