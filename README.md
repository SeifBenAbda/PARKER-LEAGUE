<div align="center">

![Parker League](docs/assets/entry.gif)

# Parker League

**FIFA World Cup 2026 — Prediction Game**

Built for [PARKER](https://kick.com/parker_seifddine) · Powered by the KICKSO community on Kick

[![Players](https://img.shields.io/badge/2906_Players-ffd000?style=flat-square&labelColor=0b0b0b&color=ffd000)](https://github.com/SeifBenAbda/PARKER-LEAGUE)
[![Match Days](https://img.shields.io/badge/104_Match_Days-1a1a1a?style=flat-square&labelColor=0b0b0b&color=1a1a1a)](https://github.com/SeifBenAbda/PARKER-LEAGUE)
[![Status](https://img.shields.io/badge/Status-Live-10b981?style=flat-square&labelColor=0b0b0b)](https://github.com/SeifBenAbda/PARKER-LEAGUE)
[![Made by](https://img.shields.io/badge/Made_by-SeifBenAbda-2292A4?style=flat-square&labelColor=0b0b0b)](https://github.com/SeifBenAbda)

[![Open to Work](https://img.shields.io/badge/Open_to_Work-10b981?style=flat-square&labelColor=0b0b0b)](https://www.linkedin.com/in/seifeddinebenabda/)
[![Email](https://img.shields.io/badge/support@kickso.app-2292A4?style=flat-square&labelColor=0b0b0b)](mailto:support@kickso.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0b0b0b?style=flat-square&labelColor=0b0b0b&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/seifeddinebenabda/)

</div>

---

Parker League is a real-time prediction and bracket competition game for the FIFA World Cup 2026, integrated into [PARKER](https://kick.com/parker_seifddine)'s live streaming channel on Kick. Followers compete across 104 match days by voting on match predictions, guessing exact scores, and building full tournament brackets.

No real money. Community competition only.

---

## Features

- **Match Predictions** — vote on moderator-created events per match (winner, goals, cards, corners…)
- **Correct Score** — guess the exact final scoreline, 0–20 for each side
- **Bracket Challenge** — predict group standings, best 3rd-place ranking, and the full knockout tree
- **×2 Boost** — each player gets 2 boosts to double points on any match day they choose
- **Live Leaderboard** — 2,906 players ranked by points, with accuracy-based tiebreakers
- **Moderator Panel** — score predictions, set results, manage players, full audit log
- **Kick integration** — linked to follower status, subscriber and OG badges

---

## Screenshots

### Predictions — Available Matches

![Predictions](https://github.com/user-attachments/assets/7a3efb2f-684d-421f-b656-cafb182e2f79)

---

### Bracket — Group Stage

![Bracket Groups A–F](https://github.com/user-attachments/assets/1b7f498d-ef46-4806-a887-68598f6806b3)

![Bracket Groups G–L](https://github.com/user-attachments/assets/d1ff46fd-671c-4b8e-bf03-59f8a4c4efe2)

---

### Bracket — Best 3rd Place Ranking

![Best 3rd Place](https://github.com/user-attachments/assets/752a2a18-34a5-410f-ad19-414e2d8749cb)

---

### Leaderboard

![Leaderboard](https://github.com/user-attachments/assets/7fdf6cab-1eca-415b-a810-c1e45ba95e2a)

---

### Correct Score — Per Match Results

![Correct Score](https://github.com/user-attachments/assets/3fe0f9f4-8814-4b07-97bf-033b51b49a01)

---

### Player Profile

![Profile](https://github.com/user-attachments/assets/dd70e285-da30-4ee2-9002-9064c8dd6719)

---

### Moderator Panel

![Mod Panel](https://github.com/user-attachments/assets/971f5eee-362a-4ac8-b376-297840936ff4)

---

## How Points Work

| Mode | Points |
|------|--------|
| Prediction — common outcome | 10 pts |
| Prediction — unlikely outcome | 20 pts |
| Prediction — rare/precise | 30+ pts |
| Correct score | 15 pts |
| Group standings — 4/4 correct | 100 pts |
| Group standings — 2/4 correct | 50 pts |
| Best 3rd place — full ranking | up to 100 pts |
| Round of 32 winner | 50 pts |
| Round of 16 winner | 75 pts |
| Quarter Final winner | 100 pts |
| Semi Final winner | 150 pts |
| Final winner | 200 pts |

### Tiebreaker order (same points)

1. Prediction accuracy % — higher wins
2. Total votes cast — fewer wins
3. Correct score count — more wins
4. Join date — earlier wins

### The ×2 Boost

Every player gets **2 boosts** for the whole tournament. A boost doubles all points earned on that match day — predictions and correct score. Can be removed before the voting window closes. Unavailable on matchday 1 of the group stage for each team.

---

## Match Day Lifecycle

```
Upcoming  →  Open  →  Locked  →  Rewarded
```

| Status | What it means |
|--------|---------------|
| `Upcoming` | Match scheduled, voting not yet open |
| `Open` | Voting live — closes 10 min before kickoff |
| `Locked` | Match kicked off, no more votes |
| `Rewarded` | Results scored, points distributed |

---

## Roles

| Role | What they can do |
|------|-----------------|
| Participant | Vote on predictions, submit scores, submit bracket |
| Moderator | Create and score predictions, lock matches, set results |
| Owner | Everything — manage mods, adjust points, view audit logs |

Moderators can be restricted to specific groups (A–L). Knockout management is open to all mods.

---

## Tech Stack

**Frontend** — React, TypeScript, TanStack Query, Tailwind CSS, React Router v6, i18next (EN + AR)

**Backend** — NestJS, TypeORM, PostgreSQL, Redis, Socket.IO, SSE push for real-time leaderboard

**Platform** — Kick.com viewer identity, badges, and follower status

---

## Setup

> The game runs on a private deployment tied to the KICKSO channel. There is no public self-hosting guide at this time.

If you want to discuss the architecture or have questions, open an issue or reach out via GitHub.

---

## Author

Built by **[Seifeddine Ben Abda](https://github.com/SeifBenAbda)** for [PARKER](https://kick.com/parker_seifddine) and the KICKSO community.

---

## Open to Work

I'm currently available for freelance and full-time opportunities — fullstack development, real-time web apps, and platform integrations.

If you liked what you see here, feel free to reach out.

[![Open to Work](https://img.shields.io/badge/Open_to_Work-10b981?style=flat-square&labelColor=0b0b0b)](https://github.com/SeifBenAbda)
[![Email](https://img.shields.io/badge/support@kickso.app-2292A4?style=flat-square&labelColor=0b0b0b)](mailto:support@kickso.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0b0b0b?style=flat-square&labelColor=0b0b0b&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/seifeddinebenabda/)

---

<div align="center">

Parker League is part of **[KICKSO.APP](https://kickso.app)** — a streamers platform built for the Kick community.

Parker League · FIFA World Cup 2026

</div>
