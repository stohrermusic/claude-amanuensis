# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What This Is

A single-page HTML guide for Claude Amanuensis — a conversation memory system for Claude Code. Users visit the GitHub Pages site, copy the setup prompt, and paste it into Claude Code to generate the full system.

**This repo contains only the guide, not the generated system.**

## Structure

```
index.html    # The complete guide (GitHub Pages serves this)
README.md     # Repo overview
```

## Deployment

GitHub Pages serves `index.html` directly from the `main` branch. Push to main → site updates automatically (takes 1-2 minutes).

## Key Sections in index.html

- **Setup prompt** (id: `setup-prompt`) — The "magic words" users copy to generate the system
- **API key instructions** — Windows and Mac/Linux setup steps
- **Rate limiting info** — Explains the 30-second batching for free tier
- **Commands reference** — `aman search`, `aman topic`, `aman remember`

## When Editing

- The setup prompt must stay in sync with intended system behavior
- Test the Copy button works after changes to the prompt-box
- Keep the floating TOC links in sync with section IDs
