<!-- GitHub profile README: shown on github.com/Michael1904 because the
     repository is named after the account. -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e1b4b,50:4c1d95,100:7c3aed&height=180&section=header&text=Michael&fontSize=60&fontColor=ffffff&fontAlignY=36&desc=Full-Stack%20Developer&descAlignY=58&descSize=20" width="100%" alt="Michael — Full-Stack Developer" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3200&pause=900&color=A78BFA&center=true&vCenter=true&width=640&lines=TypeScript+%C2%B7+Next.js+%C2%B7+Node.js;Python+services+and+automation;PostgreSQL+data+modelling;From+schema+to+production" alt="TypeScript · Next.js · Node.js · Python · PostgreSQL" />

</div>

## About

Full-stack developer working mainly with **TypeScript / Next.js** on the web side and **Python** for backend services and automation, with **PostgreSQL** underneath.

I build products end to end: data model and migrations, server logic and APIs, integrations with third-party platforms, and the interface on top. I care about systems that stay correct when things go wrong — server-side validation instead of trusting the client, idempotent operations that are safe to retry, transactional writes, and documentation that lets the next person maintain the code without guessing.

- 🌐 Web applications with server rendering, OAuth sign-in and role-based access
- ⚙️ Event-driven services that turn external events (payments, chat activity) into reliable actions
- 🗄️ Relational schemas, query design and database operations in Docker on Linux
- 📄 Technical specifications and handover docs for other developers

## Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,nextjs,react,nodejs,express,tailwind,threejs&theme=dark" alt="Web stack" /><br/>
  <img src="https://skillicons.dev/icons?i=py,postgres,sqlite,docker,linux,git,github,vscode&theme=dark" alt="Backend and tooling" />
</p>

## Selected work

### Game community platform · *private*
Full-stack web platform for an online gaming community, built on Next.js and PostgreSQL.
- OAuth sign-in with role-based permissions pulled from the community's chat platform
- Storefront with server-side pricing and short order codes reconciled against incoming payments; unpaid orders expire automatically
- Player profiles with real-time 3D character rendering and a cosmetics wardrobe (Three.js)
- Collaborative knowledge base with a rich-text editor, revision history and conflict detection on concurrent edits
- Activity analytics computed from session logs: totals, contribution heatmap, streaks, leaderboards
- Rule-based moderation model: sanctions reference a ruleset, and each rule decides whether a sanction is eligible for self-service resolution
- Data split across purpose-specific databases, with idempotent schema migrations applied on startup

`TypeScript` `Next.js` `React` `PostgreSQL` `Three.js` `Auth.js`

### Payment fulfilment service · *private*
Event-driven bot that automates fulfilment of digital purchases.
- Parses incoming payment notifications and verifies the paid amount against the stored order before granting anything
- Delivers entitlements to the game server over a remote-console protocol and assigns community roles
- Manages subscription lifecycles: expiry reminders and automatic revocation when a term ends
- Routes items that need human review through persistent approval workflows that survive restarts

`Python` `asyncio` `PostgreSQL` `REST`

### Automated chat moderation · *private*
Moderation bot for a community chat server.
- Multi-layer detection: normalised word lists, pattern matching and AI-based classification with a confidence threshold
- Graduated sanctions — warnings escalate to timeouts — with one-click moderator actions and a persistent moderation log
- Warning requests from trusted members go through an approval workflow
- Word-list changes hot-reload without a restart

`Python` `NLP` `Discord API`

### [Hotel booking platform](https://github.com/Michael1904/MAUS)
Bilingual (EN/UK) hotel website with room search, availability filters and online booking.
- Next.js front end with a separate Express REST API
- JWT authentication with hashed passwords and validated input
- Email notifications, guest reviews and ratings, contact form with an embedded map

`TypeScript` `Next.js` `Tailwind` `Express` `SQLite` `JWT`

### [Telecom billing database](https://github.com/Michael1904/PostgreSQL)
Relational model for a telephone exchange: subscribers, phone numbers, tariffs and call records.
- Normalised schema with `CHECK` and foreign-key constraints enforcing business rules at the database level
- Reproducible environment with Docker Compose (PostgreSQL + pgAdmin)
- Python CLI for seeding data and producing formatted reports

`PostgreSQL` `Python` `psycopg2` `Docker`

## Activity

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Michael1904/Michael1904/output/github-snake-dark.svg" />
    <img src="https://raw.githubusercontent.com/Michael1904/Michael1904/output/github-snake.svg" alt="Contribution graph" width="100%" />
  </picture>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7c3aed,50:4c1d95,100:1e1b4b&height=100&section=footer" width="100%" alt="" />
