<h1 align="center">Namandeep Singh Virdi</h1>

<p align="center">
  <b>Systems &amp; full-stack engineer</b><br>
  Real-time backends · Node · Python · React
</p>

<p align="center">
  <a href="mailto:nvirdi567@gmail.com"><img src="https://img.shields.io/badge/Email-nvirdi567%40gmail.com-A31545?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <!-- TODO: paste your LinkedIn URL between the quotes below -->
  <a href="#"><img src="https://img.shields.io/badge/LinkedIn-Connect-2C5670?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <!-- TODO: paste your LeetCode profile URL between the quotes below -->
  <a href="#"><img src="https://img.shields.io/badge/LeetCode-Profile-A8600F?style=flat-square&logo=leetcode&logoColor=white" alt="LeetCode"></a>
</p>

---

## About

I build things that have to stay correct when more than one person is using them.

My main project is a real-time, two-player deduction game running on a **server-authoritative
state machine** — the solution never reaches a client until the reveal, so the game is
cheat-resistant by construction rather than by obscurity. Both sides import a **shared rules
layer**, so the client and server can't drift apart as the game grows.

I care about the parts that usually get skipped: tests for the lifecycle paths that actually
break, architecture decisions written down while they're still fresh, and knowing when a
system should abstain instead of guessing wrong.

Engineering student in Bangalore.

---

## Selected work

### [Whispers at Ravenhurst](https://github.com/Naman9245/whispers-at-ravenhurst)
**Real-time two-player deduction game.** `Node.js` `Socket.io` `React` `Canvas 2D`

Two detectives race to solve the same procedurally generated murder from a mix of shared
and private evidence. Accusations are scored on the *reasoning* behind them, not just speed.

- **Server-authoritative anti-cheat** — the solution is never sent to a client until the reveal
- **Shared rules layer** imported by both client and server, so game logic can't diverge
- **Solvability validator** — every generated case is proven solvable before it ships to players
- **Disconnect detection with a reconnect grace window**, so a dropped connection doesn't end the match
- Rendered on a raw HTML5 canvas — no game engine
- Test suites covering room lifecycle, movement, interrogation, accusation and case validation

### Diagnostic Price Transparency
**Hyperlocal medical test price comparison for Bengaluru.** `Python`

The scraping isn't the hard part — **name normalisation** is. Published test names are
inconsistent across labs, and the core problem is resolving them onto a canonical taxonomy,
or **abstaining** when confidence is too low. A wrong match on a medical price is worse than
no match at all.

### Liquid Sky
**Two production restaurant sites.** `TypeScript` `React` `Node` `SQLite`

The dark variant runs on a **zero-dependency Node + SQLite backend** serving live pricing,
sold-out state, and recorded bookings — no framework, no ORM, deliberately. The light variant
is React 19 + Vite with a WhatsApp booking hand-off.

### AURA FIT AI
**Full-stack AI fitness platform.** `Next.js 15` `FastAPI` `PostgreSQL`

JWT authentication, a Postgres-backed API, and optional Gemini Vision integration for
food analysis.

---

## Tech

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

**Backend**
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socketdotio&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

**Frontend**
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Data &amp; tooling**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Naman9245&show_icons=true&hide_border=true&title_color=A31545&icon_color=2C5670&count_private=true" alt="GitHub stats" height="150">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Naman9245&layout=compact&hide_border=true&title_color=A31545&langs_count=6" alt="Top languages" height="150">
</p>
