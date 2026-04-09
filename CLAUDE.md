# Project Guide

## Vision

This repository is a research baseline for studying Kerala's development. It collects
primary source material from political parties, governments, and organizations working
in Kerala, making it accessible and structured for researchers, journalists, and
citizens.

## Scope

The repository covers (or plans to cover):

- **Election manifestos** — from all major fronts across elections
- **Government orders and policies** — GOs, policy documents, white papers
- **Budgets** — state budgets, economic reviews
- **Institutional reports** — from academic, economic, and social institutions
- **Organizational documents** — from NGOs, cooperatives, trade unions, and other bodies
- **Development indicators** — statistics and data on Kerala's progress

## Repository Structure

Organize files by category, then by time period:

```
manifestos/2026_assembly_elections/
budgets/2025-26/
policies/education/
reports/economic_review/2025/
statistics/
```

### File Naming

- Use `<source>-<language>.<ext>` for documents (e.g., `ldf-mal.pdf`, `nda-eng.pdf`)
- Use descriptive names for derived data (e.g., `ldf-mal-video-transcripts.md`)
- Keep names lowercase with hyphens

## Content Guidelines

- Prefer primary sources (original documents) over third-party summaries
- Include both Malayalam and English versions when available
- Extract text from non-machine-readable formats (scanned PDFs, videos) into
  structured, searchable formats (.md, .json, .txt)
- When summarizing, be factual and descriptive — this is a research resource,
  not an advocacy project
- Present material from all political fronts and viewpoints without editorial bias

## Tools and Techniques

For extracting content from Malayalam audio/video/PDFs:

- **Gemini API** (`GEMINI_API_KEY` env var) — Malayalam transcription from audio,
  on-screen text extraction from video, document understanding
- **yt-dlp** — downloading video/audio from YouTube
- **pyzbar + pdf2image** — QR code extraction from PDFs
- **ffmpeg** — video frame extraction and audio processing

## Adding New Content

When adding a new document or dataset:

1. Place it in the appropriate directory, creating subdirectories as needed
2. Add an entry in the relevant section of `README.md` with a brief summary
3. If the source is a PDF with embedded media (QR codes, links), extract and
   include the linked content
4. If the source is in Malayalam only, provide English summaries where practical
