# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project status

No code exists yet — this directory currently contains only design mockups (`design/*.png`). The user is about to build this as static HTML file(s). There is no git repo, build tooling, package manager, or test setup configured yet; don't assume any of these exist without checking first.

## What this project is

A "Pink Beam Type Test" — a BuzzFeed-style personality quiz landing page promoting the song release 코미 Solo〈사랑의 핑크 빔〉("Pink Beam of Love") releasing 2026.09.28. The design mockups (all Korean filenames) lay out the intended flow:

- `첫 화면.png` — landing screen with a "테스트 시작하기" (start test) CTA
- `질문1.png` – `질문10.png` — the quiz's 10 question screens (binary/A-vs-B choice style, progress bar at top)
- `결과1.png` – `결과4.png` — result/type reveal screens (4 possible outcome types)
- `곡발매 홍보 페이지.png` / `곡발매 홍보 페이지1.png` — the song-release promo screen shown after the quiz completes (progress bar at "SCAN COMPLETE · 100%"), with a "내 TYPE 확인하기" CTA into the result. **Note: these two files are byte-identical duplicates** (same content/size) — treat as one screen when implementing; no functional distinction between them yet.

Visual style: pink/white K-pop idol aesthetic, anime-style character art, heart/sparkle motifs, a top progress bar tracking quiz advancement.

## Working in this repo

- Treat `design/*.png` as the authoritative visual spec — match layout, copy (Korean text), and progress-bar/CTA behavior shown in each screen when implementing.
- When the user starts adding HTML/CSS/JS files, update this CLAUDE.md with actual build/run instructions and file structure — none exist yet to document.
