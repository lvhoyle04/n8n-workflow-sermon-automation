# Blog Draft Generation Workflow

This branch contains the workflow for generating keyword-optimized blog post drafts from sermon transcripts using a generative AI tool like OpenAI.

## Purpose

To repurpose sermon content into blog posts that drive search traffic and reach a broader online audience.

## Workflow Summary

- Input: Sermon transcript + keyword list
- Output: Blog post draft
- Tools: OpenAI API, n8n, Google Docs or WordPress

## Key Features

- Automatically extracts key ideas from transcript
- Optimizes content with provided SEO keywords
- Drafts posts in Markdown or HTML format
- Outputs to WordPress draft or Google Docs

## Files in This Branch

- `generate-blog-from-transcript.n8n.json`: Main workflow file
- `docs/notes-blog-drafts.md`: Explains the workflow steps
- `prompts/blog-post-generator.md`: Prompt used for blog generation

## Next Steps

- Automatically generate keywords from transcript
- Add support for tagging and excerpt generation
- Auto-schedule WordPress drafts for publishing
