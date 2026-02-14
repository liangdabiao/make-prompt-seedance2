# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a documentation repository for **Seedance 2.0** - 字节跳动的 AI 视频生成模型 (ByteDance's AI video generation model). The repository contains:

- **`structured-prompt.md`** - The main structured prompt guide (结构化提示语), a comprehensive reference for creating effective prompts for Seedance 2.0
- **`docs/`** - Source tutorial articles from various authors (藏师傅, 袋鼠帝, 小禾, 奋力) that were consolidated into the main guide

## Content Architecture

### Main Guide Structure (`structured-prompt.md`)

The guide is organized into numbered sections:

- **零 (Zero)** - Core philosophy and usage principles (核心理念)
- **一 (One)** - System role definition and step-by-step guidance flow
- **二 (Two)** - Detailed deep-dive questions (content, visual style, camera language, action/rhythm, sound design)
- **三 (Three)** - Prompt formulas and 16+ templates (模板一 through 模板十六)
- **四 (Four)** - Camera movement quick reference table
- **五 (Five)** - Mood/atmosphere keyword library
- **六 (Six)** - Multimodal reference syntax
- **七 (Seven)** - Special scene handling (character consistency, camera/action replication, video extension, plot modification, music timing)
- **八 (Eight)** - Example prompts (示例一 through 示例八)
- **九 (Nine)** - Output format requirements
- **十+** - Advanced topics: quality characteristics, special techniques, important notes, platform access, etc.

### Key Content Types

1. **Templates (模板)** - Reusable prompt structures for common video types:
   - Narrative stories, product showcases, character action, scenery travel
   - Video extension, video editing, short dramas, UI product demos
   - Space tours, character battles, talking head/播客, music beat matching

2. **Reference Tables** - Quick lookup for:
   - Camera movements (推/拉/摇/移 etc.)
   - Mood keywords (lighting, color tone, texture, emotion)
   - Usage scenarios, style keywords, effect keywords

3. **Examples (示例)** - Complete, copy-paste ready prompts

## Editing Guidelines

### When Updating `structured-prompt.md`

1. **Maintain Chinese-English balance** - The guide is primarily in Chinese with some English terms. Keep technical terms in both languages where helpful.

2. **Preserve structure** - The numbered section system is intentional. When adding new content:
   - Use appropriate template numbers (模板十七, 模板十八, etc.)
   - Use appropriate example numbers (示例九, 示例十, etc.)
   - Maintain the `## ` heading format

3. **Format consistency**:
   - Use code blocks (` ``` `) for prompts
   - Use tables for quick reference content
   - Use `【】` for labeled sections within prompts (e.g., `【风格】`, `【时长】`)

4. **Cross-references** - When adding new templates or examples, update:
   - Section 二十 (Complete directory index) - if adding major sections
   - Section 十八 (Quick reference card) - for new template types

### When Adding Content from `docs/`

The `docs/` folder contains source articles. When extracting content:

1. Look for **unique techniques, templates, or examples** not already in the main guide
2. **Reorganize into the appropriate section** rather than copying verbatim
3. **Credit patterns/templates** to their source author when distinctive

## Language Notes

- Primary language: **Simplified Chinese** (简体中文)
- Some English terms kept for: Platform names (Seedance, Fluent Design), technical camera terms, style keywords
- When translating between Chinese and English in prompts, provide both for clarity

## No Build/Test Process

This is a documentation-only repository. There are no:
- Build commands
- Test suites
- Linting
- Deployment processes

The "workflow" is simply: edit markdown files, commit changes.
