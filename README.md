# ai-news-collectors — Aggregate and heat-rank the latest AI news

> Runs a multi-dimensional sweep across newsletters, communities, product launches, and research, then ranks everything by buzz. Delivers a sorted Chinese-language digest with source links.

[![OpenClaw Skill](https://img.shields.io/badge/OpenClaw-Skill-blueviolet)](https://github.com/NachaFromMars)

## Overview
ai-news-collectors is a research workflow that gathers AI news from a broad set of sources and ranks the results by heat (popularity and discussion volume). Instead of a single query, it runs 8–12 targeted searches spanning six distinct dimensions — from viral community threads to fresh research papers and funding announcements. The output is a concise, heat-sorted summary in Chinese with links back to each source.

## Features

The skill searches across six dimensions:
- **A) Newsletters & weekly roundups** — high-density curated digests
- **B) Community / viral** — Reddit, Hacker News, GitHub trending
- **C) Product launches & model updates** — new releases and announcements
- **D) Research papers** — arXiv, Hugging Face
- **E) Funding & business news** — investments, acquisitions
- **F) International** — Chinese AI ecosystem (Weibo, WeChat, Zhihu)

**Output:** Heat-sorted Chinese summary list with source links per item.

## Usage / Quick Start
Trigger with a natural-language news request. The skill executes 8–12 searches across all six dimensions and returns a ranked digest.

## Trigger Keywords (OpenClaw)
今天有什么AI新闻, 最近有什么火的AI产品, AI圈最近在讨论什么

## Related Skills
- [news-summary](https://github.com/NachaFromMars/news-summary) — general news summarization

---
Part of the [NachaFromMars](https://github.com/NachaFromMars) OpenClaw skill ecosystem.
