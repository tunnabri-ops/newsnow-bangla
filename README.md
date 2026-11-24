# 📰 newsnow-bangla

[![News](https://img.shields.io/badge/type-news%20reader-blue)](https://github.com/tunnabri-ops/newsnow-bangla)
[![Language](https://img.shields.io/badge/UI-Bangla-orange)](https://github.com/tunnabri-ops/newsnow-bangla)

**Bangla news reader — Prothom Alo, BBC Bangla, bdnews24 and Jagonews24 in one place.**

> বাংলা সংস্করণ নিচে আছে। / Bangla version below.

## ✨ Features

- **4 Bangla news sources** in `bangla-sources.json`:
  - Prothom Alo — `https://www.prothomalo.com/feed/`
  - BBC Bangla — `https://www.bbc.com/bengali/index.xml`
  - bdnews24.com — `https://bdnews24.com/rss`
  - Jagonews24 — `https://www.jagonews24.com/rss/rss.xml`
- **Starter page** — `index.html` links straight to each outlet so you can read right away
- **Add-Feed planned** — add your own RSS URL from the UI instead of only the fixed list

## 🚀 How to use

1. Open `index.html` in a browser and pick an outlet to read.
2. To change sources, edit `bangla-sources.json` — each entry needs a `name` and a feed `url`.

## ⚠️ Honest limits

- The static page is a starter and guide — it does **not** pull the feeds into the page by itself.
- The full news app is server-based: running it needs a server (Docker).

## 🇧🇩 বাংলা

**নিউজ বাংলা — বাংলার ৪টি বড় সংবাদমাধ্যম এক জায়গায়।**

- `index.html` খুলে পছন্দের পত্রিকা/চ্যানেল খুলে পড়ুন
- নতুন সোর্স যোগ করতে `bangla-sources.json` সম্পাদনা করুন

## 📄 License

MIT — use it however you like; credit is appreciated.
