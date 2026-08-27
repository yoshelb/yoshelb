![Hi, I'm Shelbey — Software Engineer · Designer · AI-assisted builder](header.svg)


 
Software Engineer with a nontraditional path — opera 🎤 → [shrimp content](https://www.tiktok.com/@yoshelb?is_from_webapp=1&sender_device=pc) 🦐 → full-stack 💻. I build thoughtful, well-designed web experiences. Lately: deep in AI-assisted workflows.
 
[Portfolio](https://shelbeycasalena.com/) &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/shelbey-casalena)
 
---
 
### What I'm building right now

**Agent Board**: my personal AI dev team, run from a Trello board. Trello instead of a homegrown board because it's free, has great apps, and is an API-ready source of truth, so there's nothing for me to build or host. Drop a card in To Do and a dispatcher spawns a Claude worker in an isolated git worktree; five reviewers judge the diff (one of them judges the rendered pixels), then an interactive merge loop boots each finished change in the browser so merging is a quick look and a yes. The whole thing is tuned to squeeze the most out of my Claude Max plan, with zero hosting costs. I'm now building the outer loop: sensors record the harness's own health, and a proposer reads that telemetry and files improvement cards back onto the board, working toward a system that improves and heals itself.
<br><sub>Python (stdlib only) · Claude Code · Trello API · git worktrees</sub>

![The factory: an inner loop that ships work, sensors feeding an append-only store, and an outer loop that studies and improves it](assets/factory.svg)

<p align="center">
  <img src="assets/trello-board.jpg" width="92%" alt="The live Trello board, mid-flight">
  <br><sub>the board (Agent Command Center) after an overnight run: the queue is cleared, six cards sit in Ready to Merge, two wait on human input</sub>
</p>

<table>
<tr>
<td width="46%">
<img src="assets/explainer.jpg" width="70%" alt="An explainer page built by the skill"><img src="assets/brainrot.jpg" width="28%" alt="Brainrot captions video">
</td>
<td>

**Explainers**

The factory ships faster than I can read every diff, so I've been thinking hard about how to keep myself genuinely in the loop. Explainers is one answer: a Claude Code skill that turns any of my projects into an interactive explainer page, with researched visual sections, audio briefings with word-synced captions over a looping brainrot video (inspo: pdf to brainrot), and a quiz to prove I actually absorbed it.

<sub>Claude Code skill · Gemini TTS · faster-whisper · canvas</sub>

</td>
</tr>
<tr>
<td width="46%">
<img src="assets/casa.jpg" alt="Casa dashboard on the Frame TV">
</td>
<td>

**Casa Command Center**

Turns a Samsung Frame TV into the household's ambient dashboard: calendar, chores, film watchlist, markets, even mushroom season. Rendered at 4K with headless Chromium, pushed to the TV in Art Mode, and editable by the house AI assistant over MCP.

<sub>Python · Postgres · MCP · headless Chromium</sub>

</td>
</tr>
<tr>
<td width="46%">
<img src="assets/familytasks.jpg" alt="Family Tasks app">
</td>
<td>

**[Family Tasks](https://family-tasks-production-9def.up.railway.app/)** ![live](https://img.shields.io/badge/live-2ea44f?style=flat-square) <sub>(working name, still waiting on a real one)</sub>

A family task app where every member can connect their own AI assistant to the same shared lists via MCP. The moat is completion history: "when did I last mow the lawn?" is a first-class query.

<sub>FastAPI · MCP · SvelteKit · Supabase</sub>

</td>
</tr>
<tr>
<td width="46%">
<img src="assets/gotothese.jpg" alt="GoToThese landing page">
</td>
<td>

**[GoToThese](https://www.gotothese.com/)** ![live](https://img.shields.io/badge/live-2ea44f?style=flat-square)

Collect and privately review places, make lists, and share them with friends and family.

<sub>Django REST · React · Google Places API · AWS S3</sub>

</td>
</tr>
<tr>
<td width="46%">
<img src="assets/campintent.jpg" alt="CampIntent campsite search">
</td>
<td>

**[CampIntent](https://www.campintent.com/)** ![live](https://img.shields.io/badge/live-2ea44f?style=flat-square)

Campsite availability finder for California: search 100+ campgrounds across recreation.gov and Reserve California, and get alerts when a weekend opens up.

<sub>FastAPI · React · Postgres · Railway</sub>

</td>
</tr>
</table>

### Tech I reach for
 
![Next.js](https://img.shields.io/badge/Next.js-dde9f5?style=flat-square&logo=next.js&logoColor=2d4a6b&labelColor=dde9f5)
![React](https://img.shields.io/badge/React-dde9f5?style=flat-square&logo=react&logoColor=2d4a6b&labelColor=dde9f5)
![TypeScript](https://img.shields.io/badge/TypeScript-dde9f5?style=flat-square&logo=typescript&logoColor=2d4a6b&labelColor=dde9f5)
![Python](https://img.shields.io/badge/Python-dde9f5?style=flat-square&logo=python&logoColor=2d4a6b&labelColor=dde9f5)
![Django](https://img.shields.io/badge/Django-dde9f5?style=flat-square&logo=django&logoColor=2d4a6b&labelColor=dde9f5)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-dde9f5?style=flat-square&logo=postgresql&logoColor=2d4a6b&labelColor=dde9f5)
![AWS](https://img.shields.io/badge/AWS-dde9f5?style=flat-square&logo=amazonwebservices&logoColor=2d4a6b&labelColor=dde9f5)
