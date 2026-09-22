<div align="center">

<!-- ═══════════════════════════════════════════════════════════════
     TODO: 下面 4 处标了 <-- EDIT 的是我不知道的真实信息，请自己填。
     其余内容全部来自仓库实际数据，是准确的。
     ═══════════════════════════════════════════════════════════════ -->

# 👋 Hey, I'm ZYHUO

### Self-hosted API gateways · Telegram agents · proxy tooling

`Go` · `TypeScript` · `Rust` · `Vue 3` · `Electron`

</div>

---

## 🧩 What I build

I like infrastructure that runs on hardware I own — API gateways that turn
subscription-based AI accounts into something usable, chat agents that behave
less like command-line toys and more like participants, and panels for the
proxy/networking layer underneath it all.

| | |
|---|---|
| **🛰️ API gateways** | OpenAI-compatible reverse proxies, multi-account pooling, quota accounting |
| **🤖 Chat agents** | Telegram bots with real behaviour models, not just `!command` handlers |
| **📊 Ops panels** | Go + Vue 3 dashboards with auth, traffic stats, one-click deploy |

---

## 🚀 Projects

### ⭐ [dashGO](https://github.com/ZYHUO/dashGO) — ★ 11
A modern proxy-panel management system. **Go** backend + **Vue 3** frontend,
sing-box core underneath. SQLite (default) or MySQL, JWT auth, SQL-injection
hardening, real-time traffic stats, Docker Compose one-liner.

> ⚠️ Currently ships **without a license** — being fixed. Until then, treat it as
> all-rights-reserved.

### ⭐ [NyatBot](https://github.com/ZYHUO/nyat-bot) — ★ 9
A Telegram group-chat agent. Not a bot that answers when poked — an agent that
hangs out, reads the room, and only speaks when it has something worth saying.

Pressure / envelope / reflex "trench" body layer, behavioural anti-ad with
group-owner opt-in, Meta+Subagent main path with per-task send budgets, and a
flag census that fails the build if a dead switch comes back. **MIT licensed.**

### 🖥️ [CLIProxy-Quota-Tray](https://github.com/ZYHUO/CLIProxy-Quota-Tray) — ★ 1
Windows & Linux tray app for [CLIProxyAPI](https://github.com/router-for-me/CLIProxyAPI).
Watch per-OAuth-account quota windows, estimate usage-queue cost, see live
OpenAI / Claude status. Terminal-dark UI, embedded JetBrains Mono.

### 📰 [tg-newsbot](https://github.com/ZYHUO/tg-newsbot) — ★ 1
Telegram channel news push. Polls RSS/Atom → dedupes → LLM Chinese summary →
publishes. ~40 verified feeds across 6 categories, per-source intervals.

### ⛏️ [minecraft-grok-bot](https://github.com/ZYHUO/minecraft-grok-bot)
Many independent Grok minds × many Minecraft bodies. Soul-configurable agents
(`souls/andy.toml`), `gbot spawn -name Andy`, multiple concurrent bodies.

### 🗄️ [nyatdb](https://github.com/ZYHUO/nyatdb)
Rust embedded page engine for NyatBot.

### 🔁 [workbuddy2api](https://github.com/ZYHUO/workbuddy2api)
Turn Tencent CodeBuddy accounts into an OpenAI-compatible API. OAuth login,
account-pool rotation, circuit breaking + cooldown, session stickiness,
scheduled keep-alive.

> ⚠️ Unofficial gateway — self-host / authorised-account use only.

---

## 🛠️ Stack

```
Backend     Go · Rust · TypeScript · Node.js
Frontend    Vue 3 · Vite · Electron
Data        SQLite · MySQL · Cloudflare KV / Workers
AI          OpenAI / Claude / Grok (xAI) · StepFun
Infra       Docker Compose · sing-box · vless subscription tooling
```

---

## 📈 Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=ZYHUO&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&text_color=C9D1D9" alt="GitHub Stats" height="165" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=ZYHUO&theme=tokyonight&hide_border=true&background=0D1117&ring=58A6FF&fire=1F6FEB&currStreakLabel=58A6FF" alt="Streak" height="165" />

</div>

<div align="center">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ZYHUO&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9" alt="Top Languages" height="150" />

</div>

---

<div align="center">

<!-- ═══════════ EDIT THESE FOUR LINES ═══════════
     我不知道你的真实姓名 / 所在地 / 联系方式 / 个人站，
     这几行是占位符，不会对外暴露假信息，但会显示成空链接。
     请替换成真实内容，不想要的直接删掉对应那一行。 -->

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:YOUR_EMAIL_HERE)
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/YOUR_TG_HERE)
[![Blog](https://img.shields.io/badge/Blog-FF5722?style=for-the-badge&logo=blogger&logoColor=white)](https://YOUR_BLOG_HERE)

</div>

<br>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=ZYHUO&style=for-the-badge&color=1F6FEB" alt="Profile views" />
</div>

<div align="center">
<sub>⭐ If one of my projects saved you some time, a star genuinely helps it get found.</sub>
</div>
