# Hangul — Korean Learning Tool

[🇨🇳 中文](README_CN.md)

An all-in-one Korean self-study tool: vocabulary flashcards, grammar quizzes, and shadowing practice. Open in your browser, no signup required.

## Usage

**Live site (recommended):** [itzak89.github.io/hangul](https://itzak89.github.io/hangul/)

> Vocabulary and Grammar modules work directly. Shadowing requires audio download — use the local setup.

Run locally:

```bash
git clone https://github.com/itzak89/hangul.git
open index.html            # Vocabulary + Grammar ready
python3 server.py          # Shadowing module (port 8766, requires yt-dlp)
```

## Features

**Vocabulary**
- 381 TOPIK 4-6 words, flashcard + typing input modes
- Filter by level / category, adjustable daily quota
- Daily review & intensive review (localStorage)
- Keyboard navigation (Enter to flip, arrow keys to switch)

**Grammar**
- 27 grammar study cards (accordion) + 27 fill-in-the-blank quizzes
- Instant feedback, filter by level / category

**Shadowing**
- Paste YouTube URL + VTT subtitles, auto-download audio
- Audio player with synced subtitle highlighting, click to jump
- "Learned" markers (deduped by video ID + content hash)

**Global**
- EN/CN bilingual UI toggle · daily streak tracker

## Tech

Vanilla HTML/CSS/JS, vocabulary/grammar data embedded as JSON. Shadowing module requires Python server + yt-dlp.
