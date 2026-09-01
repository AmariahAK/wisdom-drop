<div align="center">

# [~] Wisdom-Drop

**A curated anthology of daily wisdom — resilience, growth, and the examined life**

</div>

<p align="center">
  <a href="https://github.com/AmariahAK/wisdom-drop/actions/workflows/daily-quote.yml"><img src="https://github.com/AmariahAK/wisdom-drop/actions/workflows/daily-quote.yml/badge.svg" alt="Daily Quote"></a>
  <a href="#"><img src="https://img.shields.io/badge/quotes%20published-354-2d4b3e?style=flat" alt="Quotes Published"></a>
  <a href="#"><img src="https://img.shields.io/badge/quotes%20queued-177-5a7d6e?style=flat" alt="Quotes Queued"></a>
  <a href="#"><img src="https://img.shields.io/badge/year-2026-8b9dc3?style=flat" alt="Year 2026"></a>
</p>

> **Wisdom-Drop** is an automated daily-quote anthology. Each day at 6am UTC, a GitHub Action publishes a hand-curated quote — drawn from philosophy, literature, stoicism, and original voice — to the archive. It is a quiet, steady practice: one insight, one day at a time.

---

<!-- today-quote-start -->

### * Today's Quote — September 1, 2026

<table>
<tr><td>

> "Do not spoil what you have by desiring what you have not; remember that what you now have was once among the things you only hoped for."
> — Epicurus

</td></tr>
</table>

<p align="right"><sub>Tags: Gratitude / Contentment / Mindfulness</sub></p>

<!-- today-quote-end -->

---

<details>
<summary>[+] <strong>Table of Contents</strong> (click to expand)</summary>

- [Today's Quote](#-todays-quote)
- [Project Overview](#-project-overview-)
- [How It Works](#-how-it-works-)
- [Quote Categories](#-quote-categories-)
- [The Archives](#-the-archives-)
- [Upcoming Quotes](#-upcoming-quotes-)
- [Contributing](#-contributing-)

</details>

---

## [i] Project Overview

**Wisdom-Drop** is a daily practice of curation and reflection. Each day, a single quote is published from a growing queue — spanning Stoic philosophy, existential thought, samurai wisdom, mindfulness, faith, and the original voice of **Amariah Abishai**.

The project is both a personal discipline and a public offering: a slow-growing garden of ideas meant to ground, challenge, and inspire. It runs entirely on GitHub Actions with zero infrastructure — a cron job, a JSON queue, and markdown files.

---

## [*] How It Works

1. **Quotes are queued** in [`upcoming-quotes.json`](upcoming-quotes.json) with a date, tags, author, and quote body.
2. **Every day at 6am UTC**, the [GitHub Action](.github/workflows/daily-quote.yml) picks the quote scheduled for that date.
3. **The quote is appended** to the yearly archive ([`2026/2026.md`](2026/2026.md)), today's quote on this page is updated, and the entry is removed from the queue — all committed automatically.

> 354 quotes published so far. 177 more queued and counting.

---

## [>] Quote Categories

Themes that emerge from the collection across **both years** (2025 & 2026):

```
Wisdom-Drop Categories
|
+-- Mindfulness & Inner Peace
:   +-- Presence / Stillness
:   +-- Patience / Acceptance
:   +-- Gratitude / Contentment
|
+-- Courage & Resilience
:   +-- Perseverance / Grit
:   +-- Vulnerability / Authenticity
:   +-- Growth Through Adversity
|
+-- Stoicism & Ancient Wisdom
:   +-- Discipline / Self-Mastery
:   +-- Perspective / Mortality
:   +-- Samurai / Bushido / Strategy
|
+-- Personal Growth
:   +-- Habits / Identity
:   +-- Self-Discovery / Purpose
:   +-- New Beginnings / Change
|
+-- Faith & Trust
:   +-- Spiritual Encouragement
:   +-- Trust-the-Process
:   +-- Surrender / Guidance
|
+-- Execution & Discipline
:   +-- Consistency / Routine
:   +-- Focus / Productivity
:   +-- Kaizen / Continuous Improvement
|
+-- Wisdom & Philosophy
:   +-- Legacy / Perspective
:   +-- Intellectual Humility
:   +-- Human Nature / Character
|
+-- Nature & Balance
:   +-- Adaptability / Flow
|
+-- Voice of Origin
    +-- Amariah Abishai (original wisdom)
```

---

## [=] The Archives

Published quotes are organized by year and quarter.

| Year | File | Quotes | Era |
|------|------|--------|-----|
| **2026** (current) | [`2026/2026.md`](2026/2026.md) | 210+ and counting | Structured, philosophical voice — Stoicism, existentialism, Eastern wisdom |
| **2025** (inaugural) | [`2025/2025.md`](2025/2025.md) | 156 | Informal experimentation — developer wisdom, pop culture, faith, early format |

The 2026 archive grows daily — each new quote appears at the bottom of Q3 and also updates the today's-quote section at the top of this page.

---

## [~] Upcoming Quotes

The full queue lives in [`upcoming-quotes.json`](upcoming-quotes.json) — 177 quotes scheduled ahead. Each entry has a date, author, quote body, and tags. New quotes are added to the end of the queue as inspiration strikes.

---

## [~] Contributing

This is a personal curation project, but suggestions are welcome. If you have a quote you'd love to see featured, open an issue with:

- The quote text
- The author
- Suggested tags (2–3 themes)

All quotes are reviewed for fit and originality before joining the queue.
