# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Chinese-language hard science fiction novel project titled **《星尘纪元》** (Epoch of Stardust). It is a literary work, not a software project. The repository contains:

- **Novel chapters** written in Markdown (`.md`)
- **Outlines and world-building documents** (大纲/)
- **Science/technology setting documentation** (大纲/从地球到星辰.md)
- **Architecture and character design documents** (大纲/架构设计.md, 大纲/完整大纲.md)

## Repository Structure

```
wenming/
├── README.md                          # Project overview and progress dashboard
├── 大纲/                               # Outlines and world-building
│   ├── 完整大纲.md                     # 30-chapter detailed plot outline
│   ├── 架构设计.md                     # Volume planning, conflict arcs, character system
│   └── 从地球到星辰.md                 # Science/technology setting documentation
├── 正文/                               # Novel chapters (main text)
│   ├── 第一卷_奇点前夕/                # Volume 1: chapters + prologues + interlude
│   ├── 第二卷：太阳系纪元/              # Volume 2 (placeholder)
│   ├── 第三卷：星舰文明/                # Volume 3 (placeholder)
│   ├── 第四卷：银河时代/                # Volume 4 (placeholder)
│   └── 第五卷：永恒回归/                # Volume 5 (placeholder)
└── .git/                              # Git repository
```

## File Naming Convention

Chapters follow this pattern within each volume directory:
- `序章01-标题.md`, `序章02-标题.md` — Prologues
- `第01章-标题.md`, `第02章-标题.md` — Main chapters
- `间奏-标题.md` — Interludes (archive-style epilogues per volume)

## Volume Progress (as of 2026-05-26)

| Volume | Status | Chapters Written |
|--------|--------|-----------------|
| 第一卷：奇点前夕 | In progress | 序章01–序章02, 第01章–第05章 (6 chapters) |
| 第二卷：太阳系纪元 | Planned | — |
| 第三卷：星舰文明 | Planned | — |
| 第四卷：银河时代 | Planned | — |
| 第五卷：永恒回归 | Planned | — |

## Key Reference Documents

When editing or continuing the novel, consult these files for consistency:

- **`大纲/完整大纲.md`** — Detailed plot summary for all 30 chapters + interludes + epilogue. Use this to understand what happens in each chapter and maintain narrative continuity.
- **`大纲/架构设计.md`** — Character system, generational lineages, thematic arcs, and the "triple singularity" technology triangle. Use this for character voice, motivation, and symbolic consistency.
- **`大纲/从地球到星辰.md`** — Hard science setting: topology quantum computing, controlled fusion, brain-machine interfaces, and their technical interdependencies. Use this to ensure scientific plausibility.

## Narrative Conventions

- **Chronological tagging**: Each chapter opens with a precise year and location.
- **Multi-POV structure**: No single protagonist; each chapter follows a specific viewpoint character.
- **Interlude format**: Each volume ends with an "档案" (archive) interlude composed of fictional documents, news fragments, and diary excerpts.
- **Three inheritance lineages**: Characters are connected across generations through scientific, exploratory, and consciousness-symbiotic lineages (see 架构设计.md §五).
- **Tone**: Hard science fiction with philosophical depth. Technical rigor is balanced with emotional and existential themes.
