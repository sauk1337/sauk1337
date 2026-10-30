<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1f6feb,100:f78166&height=180&section=header&text=sauk&fontSize=64&fontColor=ffffff&fontAlignY=36&desc=Eggdrop%20%C2%B7%20Tcl%20%C2%B7%20IRC%20bots%20for%20QuakeNet&descAlignY=58&descSize=18" width="100%" alt="sauk" />

<a href="https://github.com/sauk1337">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1200&color=58A6FF&center=true&vCenter=true&width=620&lines=Building+modern+Eggdrop+scripts+in+pure+Tcl;Async+HTTP%2C+no+freezes%2C+no+API+keys+needed;Anti-takeover+%26+CHALLENGEAUTH+for+QuakeNet;Live+football+on+IRC+%E2%9A%BD" alt="Typing SVG" />
</a>

<br/>

<img src="https://komarev.com/ghpvc/?username=sauk1337&style=flat-square&color=1f6feb&label=profile+views" alt="profile views" />
<img src="https://img.shields.io/github/followers/sauk1337?style=flat-square&color=f78166&logo=github" alt="followers" />
<img src="https://img.shields.io/badge/IRC-QuakeNet-58a6ff?style=flat-square&logo=libera.chat&logoColor=white" alt="QuakeNet" />
<img src="https://img.shields.io/badge/habla-espa%C3%B1ol%20%7C%20English-2ea043?style=flat-square" alt="languages" />

</div>

---

### `> whois sauk`

```irc
* sauk is ~sauk@github.com/sauk1337 * sauk
* sauk using *.quakenet.org QuakeNet IRC Server
* sauk :Tcl · Eggdrop · IRC bots · security
* sauk :Writes Eggdrop scripts that are fast, safe and readable
* sauk End of /WHOIS list.
```

I build **IRC bots and Eggdrop scripts in Tcl**, mostly for **QuakeNet**. I like taking old,
battle-tested IRC tooling and bringing it up to date: asynchronous web requests, real security
(CHALLENGEAUTH, SSRF-safe fetching, SHA-256-verified updates), tests, clean docs and output
that still looks right in old mIRC clients.

- 🛡️ Channel services & anti-takeover protection with Q integration
- 🌐 Utility bots: IP intel, anti-proxy gates, YouTube, RSS, GitHub tracking, reminders
- ⚽ Live sports on IRC: goal alerts, radio-style commentary, prediction pools
- 🤖 LLM answers on IRC through the Claude API or a local model
- 📚 Every script ships with a header, a manual and an install guide (EN / ES)

---

### 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

#### ⚽ [matchday](https://github.com/sauk1337/matchday)
Live sports for Eggdrop: instant goal alerts, **radio-style match commentary**, a prediction
game with leaderboards, standings, line-ups, player profiles, win probabilities and a web
dashboard. **No API key, no database.**

![Tcl](https://img.shields.io/badge/Tcl-8.6-1f6feb?style=flat-square)
![License](https://img.shields.io/github/license/sauk1337/matchday?style=flat-square&color=2ea043)
![Stars](https://img.shields.io/github/stars/sauk1337/matchday?style=flat-square&color=f78166)

</td>
<td width="50%" valign="top">

#### 🛡️ [service.tcl](https://github.com/sauk1337/service.tcl)
Channel service and **anti-takeover protection** for QuakeNet: mass-deop/kick detection,
Q `RECOVER`, CHALLENGEAUTH (HMAC-SHA-256), spamscan, linked-bot defence and
SHA-256-verified updates from GitHub releases. Continuation of r0t3n's classic script.

![Release](https://img.shields.io/github/v/release/sauk1337/service.tcl?style=flat-square&color=1f6feb)
![License](https://img.shields.io/github/license/sauk1337/service.tcl?style=flat-square&color=2ea043)
![Stars](https://img.shields.io/github/stars/sauk1337/service.tcl?style=flat-square&color=f78166)

</td>
</tr>
<tr>
<td colspan="2" valign="top">

#### 🧰 [eggdrop-quakenet-utils](https://github.com/sauk1337/eggdrop-quakenet-utils)
A modern toolbox for a QuakeNet utility bot, **18 scripts** usable one by one or as a single file:
anti-proxy/VPN/Tor gate, full IP lookups (ASN, RDAP, DNSBL), weather, crypto, DNS, YouTube and
SSRF-safe link titles, channel stats with an HTML page, reminders, RSS/Atom feeds, a GitHub
profile tracker, Wikipedia, dictionary, countdowns and `!ask` AI answers. Fully asynchronous,
with a test harness and a build step.

![Tcl](https://img.shields.io/badge/Tcl-8.6-1f6feb?style=flat-square)
![Eggdrop](https://img.shields.io/badge/Eggdrop-1.9%20%7C%201.10-f78166?style=flat-square)
![Stars](https://img.shields.io/github/stars/sauk1337/eggdrop-quakenet-utils?style=flat-square&color=f78166)

</td>
</tr>
</table>

<details>
<summary><b>📺 What it looks like on IRC</b></summary>

```irc
<Matchday> ⚽ GOAL! Real Madrid 1-0 Sevilla — Mbappé 23' [LALIGA]
<Matchday> ⏸ Half-time: Real Madrid 1-1 Sevilla (Mbappé 23' | En-Nesyri 44' (pen)) [LALIGA]
<Matchday> ♛ Pool Real Madrid 3-1 Sevilla: exact (+3): pepe · right result: ana (+1)

<utilbot>  YouTube :: Kase O - Silencio (Channel: 7711zZ | Duration: 6:03 | Views: 6.7M)
<utilbot>  Weather :: Madrid, ES (Now: Partly cloudy, 21.3C | Humidity: 40% | Wind: 12 km/h NE)
<utilbot>  GitHub :: torvalds released torvalds/linux v6.20 (Name: Linux 6.20)
```

</details>

---

### 🛠️ Tech stack

<div align="center">

![Tcl](https://img.shields.io/badge/Tcl-1f6feb?style=for-the-badge&logo=tcl&logoColor=white)
![Eggdrop](https://img.shields.io/badge/Eggdrop-f78166?style=for-the-badge&logo=gnubash&logoColor=white)
![IRC](https://img.shields.io/badge/IRC-30363d?style=for-the-badge&logo=libera.chat&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![JSON](https://img.shields.io/badge/REST%20%2F%20JSON-000000?style=for-the-badge&logo=json&logoColor=white)
![Claude](https://img.shields.io/badge/Claude%20API-D97757?style=for-the-badge&logo=anthropic&logoColor=white)

</div>

---

### 📊 GitHub stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=sauk1337&show_icons=true&hide_border=true&theme=github_dark&include_all_commits=true&count_private=true" alt="stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sauk1337&layout=compact&hide_border=true&theme=github_dark" alt="top languages" />

<img src="https://streak-stats.demolab.com?user=sauk1337&theme=github-dark-blue&hide_border=true" alt="streak" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=sauk1337&theme=github-compact&hide_border=true&area=true" width="100%" alt="activity graph" />

</div>

<!-- Snake: generated by .github/workflows/snake.yml -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/sauk1337/sauk1337/output/github-snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/sauk1337/sauk1337/output/github-snake.svg" alt="contribution snake" width="100%" />
</picture>

---

### 💡 Principles

| | |
|---|---|
| ⚡ **Never block the bot** | Every web request is asynchronous. |
| 🔐 **Secure by default** | Passwords never leave the bot, links are fetched SSRF-safe, updates are hash-verified. |
| 🔑 **Zero-config** | Free APIs with no key first; keys only for optional extras. |
| 📖 **Documented** | Headers in every script, manuals, install guides in English and Spanish. |

---

<div align="center">

**💬 Find me on QuakeNet** · ⭐ Star a repo if your bot uses it · 🐛 Issues and PRs welcome

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:f78166,50:1f6feb,100:0d1117&height=100&section=footer" width="100%" alt="" />

</div>
