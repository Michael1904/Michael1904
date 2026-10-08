<!-- GitHub profile README: shown on github.com/Michael1904 because the
     repository is named after the account. Pictures live in assets/. -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:052e16,50:166534,100:22c55e&height=180&section=header&text=Michael&fontSize=60&fontColor=ffffff&fontAlignY=36&desc=Full-Stack%20Developer&descAlignY=58&descSize=20" width="100%" alt="Michael — Full-Stack Developer" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3200&pause=900&color=4ADE80&center=true&vCenter=true&width=600&lines=TypeScript+%C2%B7+Next.js+%C2%B7+Node.js;Python+services+and+automation;PostgreSQL+from+schema+to+production" alt="TypeScript · Next.js · Python · PostgreSQL" />

</div>

<img align="right" width="230" src="assets/tree.svg" alt="" />

### About

Full-stack developer. I build web products end to end — database, server logic, integrations and UI — with **TypeScript / Next.js**, **Python** and **PostgreSQL**.

Focused on systems that stay correct under failure: server-side validation, safe retries, transactional writes.

<br clear="right" />

<div align="center">

<img src="assets/waves.svg" width="100%" alt="" />

<img src="https://skillicons.dev/icons?i=ts,js,nextjs,react,nodejs,express,tailwind,threejs,py,postgres,sqlite,docker,linux,git&theme=dark&perline=14" alt="Tech stack" />

</div>

### Projects

#### 🌐 Community Platform &nbsp;![private](https://img.shields.io/badge/private-30363d?style=flat-square)

A full-stack web platform for an online gaming community — the single place where members sign in, shop, manage their profile and find documentation.

- **Identity** — OAuth sign-in with roles pulled from the community's chat server
- **Commerce** — storefront with server-side pricing; short order codes are reconciled against incoming payments, and unpaid orders expire on their own
- **Profiles** — real-time 3D character rendering with a cosmetics wardrobe
- **Knowledge base** — rich-text editor with revision history and protection against overwriting concurrent edits
- **Analytics** — playtime, activity heatmaps, streaks and leaderboards computed from session logs
- **Moderation** — sanctions tied to a ruleset, where each rule decides whether a sanction can be resolved self-service

![Next.js](https://img.shields.io/badge/Next.js-0d1117?style=flat-square&logo=nextdotjs&logoColor=4ade80)
![TypeScript](https://img.shields.io/badge/TypeScript-0d1117?style=flat-square&logo=typescript&logoColor=4ade80)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0d1117?style=flat-square&logo=postgresql&logoColor=4ade80)
![Three.js](https://img.shields.io/badge/Three.js-0d1117?style=flat-square&logo=threedotjs&logoColor=4ade80)

#### 💳 Payment Fulfilment System &nbsp;![private](https://img.shields.io/badge/private-30363d?style=flat-square)

An event-driven service that turns a payment into a delivered purchase with no manual work.

- Picks up payment notifications and verifies the amount against the stored order before granting anything
- Delivers entitlements to the game server over a remote-console protocol and assigns community roles
- Tracks subscription terms: reminders before expiry, automatic revocation when a term ends
- Routes items that need a human decision through approval workflows that survive restarts

![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=4ade80)
![asyncio](https://img.shields.io/badge/asyncio-0d1117?style=flat-square&logo=python&logoColor=4ade80)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0d1117?style=flat-square&logo=postgresql&logoColor=4ade80)
![REST](https://img.shields.io/badge/REST_API-0d1117?style=flat-square&logo=json&logoColor=4ade80)

#### 🛡️ Chat Moderation Bot &nbsp;![private](https://img.shields.io/badge/private-30363d?style=flat-square)

Automated moderation for a community chat server — catches violations in real time and keeps moderators in control.

- Layered detection: normalised word lists, pattern matching and LLM classification (Gemini) with a confidence threshold
- Graduated sanctions — warnings escalate to timeouts — with one-click moderator actions
- Persistent moderation log and an approval flow for warnings requested by trusted members
- Word lists reload on the fly, without a restart

![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=4ade80)
![Gemini](https://img.shields.io/badge/Gemini_AI-0d1117?style=flat-square&logo=googlegemini&logoColor=4ade80)
![SQLite](https://img.shields.io/badge/SQLite-0d1117?style=flat-square&logo=sqlite&logoColor=4ade80)
![Discord API](https://img.shields.io/badge/Discord_API-0d1117?style=flat-square&logo=discord&logoColor=4ade80)

<br/>

<p align="center">
  <img src="https://raw.githubusercontent.com/Michael1904/Michael1904/output/github-snake.svg" alt="Contribution graph" width="100%" />
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:22c55e,50:166534,100:052e16&height=100&section=footer" width="100%" alt="" />
