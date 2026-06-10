# Edge Journal

> A structured trading journal for ES · NQ · YM futures traders.  
> Built as a single HTML file. No installation. No server. Your data stays yours.

---

## What it is

Edge Journal is a mobile-first journaling app built around one idea: **outcomes don't tell you if you traded well — process does**.

After each trading session, the app walks you through a decision flowchart that classifies every trade (or missed trade) not by whether you made money, but by whether you followed your process. A lucky win where you broke your rules is logged differently from a clean loss where you did everything right. Over time, that distinction is what separates developing traders from consistently profitable ones.

Alongside the live review workflow, the app includes a full **backtesting log** so you can study historical price action and build conviction in your setups — all in the same place, searchable, with stats that track both.

---

## Features

### 📋 Live Trade Review — the flowchart
Every session starts with one question: *win, loss, or no trade?*  
From there, a two-step decision tree determines the process quality of the trade and routes you to one of six outcome categories:

| Category | Meaning |
|---|---|
| **Good Win** | Followed the plan, market rewarded it |
| **Bad Win** | Deviated from the plan, got lucky |
| **Good Loss** | Followed the plan, market didn't cooperate |
| **Bad Loss** | Deviated from the plan, paid for it |
| **Good Pass** | Conditions weren't there, correctly stayed out |
| **Bad Pass** | Valid setup was there, missed it |

Each category surfaces three specific reflection questions. Your answers are saved, searchable, and reviewable at any time.

### 📊 Backtest Log
Log every replayed trade with full context:
- Date, session (London / NY AM / NY PM / Asia)
- Instrument (ES / NQ / YM) and direction (Long / Short)
- Daily bias and daily profile
- Entry, target, and stop prices — **R:R calculated automatically**
- Outcome (Win / Loss / BE)
- Screenshot reference and free-form notes

### 🔍 Search & Filter
Filter both logs independently by instrument, outcome type, session, date range, and keyword — with **match highlighting** so you can see exactly where a word appears in your notes.

### 📈 Stats
Two dashboards — one for live trades, one for backtesting:
- Good process rate and win rate
- Outcome breakdown
- Instrument usage and selection bias (Weakest vs Strongest)
- Backtest performance by session and by daily profile

### ☁ Google Drive Sync
All data lives in a private file on your own Google Drive, invisible to other apps. Works **offline-first** — saves locally, syncs when connected. Full step-by-step setup guide is built into the app's Settings tab, including troubleshooting for every common error.

### 🌗 Light & Dark mode
One tap to switch. Preference is remembered.

---

## Getting started

1. Download `edge_journal.html`
2. Host it on **GitHub Pages** (free) — the app needs to run on HTTPS for Google sync to work
3. Open the URL in Chrome on your Android
4. Tap the address bar → **Add to Home Screen** — it will behave like a native app
5. Optional: follow the setup guide in ⚙ Settings to enable Google Drive sync

> **Offline use:** if you skip the Drive sync, the app works fully offline and stores everything in Chrome's local storage. Export a JSON backup regularly from the Settings tab.

---

## Instrument support

Designed for traders who work with the three correlated US equity index futures — selecting the **weakest or strongest** of the trio as the trade vehicle. Every entry records which instrument was taken and why, so you can identify patterns in your instrument selection over time.

| Instrument | Full name |
|---|---|
| **NQ** | Nasdaq-100 E-mini |
| **ES** | S&P 500 E-mini |
| **YM** | Dow Jones E-mini |

---

## Data & privacy

- All data is stored in your browser's local storage and optionally in your own Google Drive account
- No analytics, no tracking, no third-party servers
- The Google Drive integration uses the `drive.appdata` scope — the app can only see its own file, not the rest of your Drive
- Export your full dataset at any time as a plain JSON file from Settings

---

## Tech

A single `.html` file — no framework, no build step, no dependencies.  
Vanilla HTML, CSS, and JavaScript. Runs in any modern browser.

---

*Built for the daily loop: Plan → Execute → Review → Repeat.*
