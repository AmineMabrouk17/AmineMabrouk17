<div align="center">

<img src="https://my-portfolio-seven-chi-94.vercel.app/opengraph-image" width="0" height="0" alt="" />

# Amine Mabrouk

**Full-stack engineer in Tunis.** I take web products from an empty repo to a live URL — database schema, API, interface, payments, and the CI that keeps it running.

<a href="mailto:amx72001@gmail.com"><img src="https://img.shields.io/badge/AVAILABLE_FOR_FREELANCE-2ea44f?style=for-the-badge&logo=gmail&logoColor=white" alt="Available for freelance work" /></a>
&nbsp;
<a href="https://my-portfolio-seven-chi-94.vercel.app"><img src="https://img.shields.io/badge/PORTFOLIO-4f46e5?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
&nbsp;
<a href="https://www.linkedin.com/in/amine-mabrouk"><img src="https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>

**You describe the product. I ship it — tested, deployed, handed over working.**

</div>

---

### What I actually do

**Projects break at the seams.** Designer to frontend, frontend to backend, backend to whoever deploys — that's where things get lost. There are no seams here.

**Schema → API → interface → payments → CI → deploy → handover.**

**One person is accountable for the whole product — and every week you get a live URL, not a status report.**

Some clients hear "AI" and assume they're paying for prompts. Where it matters — schema, tests, security, what your product actually needs — the decisions are mine and documented.

---

### What I can build for you

| You need | What I deliver |
|---|---|
| **A product, from zero** | Schema and migrations, auth, role-based access, API, UI, deploy. Working software in weeks, not a Figma file |
| **A dashboard on live data** | WebSocket and market feeds, charts that don't lie, alerts, caching that survives real traffic |
| **AI inside your product** | Chat assistants and RAG that cite their sources, streaming answers, multi-provider (Gemini · Groq · OpenAI · Anthropic) so you never depend on one vendor |
| **An online store that takes money** | Stripe checkout, orders, admin fulfillment, verified reviews, stock handling — end to end, including the boring admin screens |
| **Arabic / RTL products** | Right-to-left interfaces and Tunisian-market constraints handled from the first screen, not bolted on at the end |
| **An app that stays cheap to run** | Cloudflare Workers + D1, serverless deploys, Docker on a VPS when you need it — and CI that catches breakage before your users do |

---

### Selected work

Real products, still running, with the source public. The commit counts are there because I keep shipping after launch — not because I opened the repo once.

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3>💰 BudgetIQ — AI finance app</h3>
      <p><i>Type a sentence, get a budget that updates itself.</i></p>
      <p><b>The problem:</b> budget apps fail because logging every expense is tedious. People quit in week two.</p>
      <p><b>What I built:</b> a conversational assistant that turns "I spent 45 dinars on groceries" into a confirmed transaction and an updated dashboard. Income, expenses and assets with a salary planner, multi-currency handling, and a data model locked down per user with PostgreSQL row-level security — self-hostable against your own Supabase project, no ads, no data harvesting.</p>
      <p><code>Next.js 16</code> · <code>React 19</code> · <code>Supabase + RLS</code> · <code>Gemini / OpenRouter</code> · <code>Recharts</code></p>
      <p><b>222 commits</b> over 3.5 months · 180+ pull requests</p>
      <p>
        <a href="https://budgetiq-two.vercel.app"><img src="https://img.shields.io/badge/LIVE_DEMO-4f46e5?style=for-the-badge&logo=vercel&logoColor=white" alt="Live Demo" /></a>
        &nbsp;
        <a href="https://github.com/AmineMabrouk17/BudgetIQ"><img src="https://img.shields.io/badge/SOURCE-181717?style=for-the-badge&logo=github&logoColor=white" alt="Source Code" /></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>📈 Crypto & Stocks — live market terminal</h3>
      <p><i>Real-time data, done properly: no polling, no stale prices.</i></p>
      <p><b>The problem:</b> market dashboards poll a public API every few seconds, then fall apart the moment traffic arrives.</p>
      <p><b>What I built:</b> Binance WebSocket streaming for crypto, server-side proxies for Yahoo Finance stocks and ETFs, live charts, browser-native price alerts, and market signals from Polymarket crowd odds. A separate Rust service on a VPS handles the backend work — with ADRs, a glossary and a decision log in the repo, so the "why" survives.</p>
      <p><code>Next.js</code> · <code>WebSocket</code> · <code>Rust</code> · <code>Turborepo</code> · <code>lightweight-charts</code> · <code>Vitest</code></p>
      <p><b>152 commits</b> · 70+ pull requests · Rust + TypeScript monorepo</p>
      <p>
        <a href="https://crypto-stocks-web-taupe.vercel.app"><img src="https://img.shields.io/badge/LIVE_DEMO-4f46e5?style=for-the-badge&logo=vercel&logoColor=white" alt="Live Demo" /></a>
        &nbsp;
        <a href="https://github.com/AmineMabrouk17/crypto-stocks"><img src="https://img.shields.io/badge/SOURCE-181717?style=for-the-badge&logo=github&logoColor=white" alt="Source Code" /></a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🎬 Cast n Cue — edge-hosted app</h3>
      <p><i>A product I built because the existing tool annoyed me.</i></p>
      <p><b>The problem:</b> trackers make episode-level watchlists painful, and most of them run on a server you have to pay for.</p>
      <p><b>What I built:</b> episode-level tracking with search, half-star ratings, private notes that autosave without eating keystrokes, and a "what do I watch next" roulette. The whole thing runs on the edge — Workers + D1 — with Better Auth, so it stays fast and cheap at any traffic level.</p>
      <p><code>Next.js</code> · <code>Cloudflare Workers</code> · <code>D1</code> · <code>Better Auth</code></p>
      <p><b>219 commits</b> · 70+ pull requests</p>
      <p>
        <a href="https://cast-cue.cast-cue.workers.dev"><img src="https://img.shields.io/badge/LIVE_DEMO-F38020?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Live Demo" /></a>
        &nbsp;
        <a href="https://github.com/AmineMabrouk17/Cast-Cue"><img src="https://img.shields.io/badge/SOURCE-181717?style=for-the-badge&logo=github&logoColor=white" alt="Source Code" /></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>⚖️ MustacharAI — Arabic legal assistant</h3>
      <p><i>RAG that cites the article instead of inventing one.</i></p>
      <p><b>The problem:</b> Tunisian legal codes sit in PDFs written in formal Arabic. Generic chatbots answer confidently and cite nothing — which is worse than no answer when the question is legal.</p>
      <p><b>What I built:</b> a retrieval pipeline over ~15 legal codes (~3,500 articles), Arabic-aware embeddings in ChromaDB, and an RTL interface that streams citations for every answer. Voice in, spoken answers out, and a provider you choose yourself — Groq, Gemini, or your own OpenRouter key from the UI.</p>
      <p><code>FastAPI</code> · <code>ChromaDB</code> · <code>sentence-transformers</code> · <code>Next.js</code> · <code>RTL Arabic</code></p>
      <p><b>72 commits</b> · Python + TypeScript · live</p>
      <p>
        <a href="https://mustachar-ai.vercel.app"><img src="https://img.shields.io/badge/LIVE_DEMO-4f46e5?style=for-the-badge&logo=vercel&logoColor=white" alt="Live Demo" /></a>
        &nbsp;
        <a href="https://github.com/AmineMabrouk17/MustacharAI"><img src="https://img.shields.io/badge/SOURCE-181717?style=for-the-badge&logo=github&logoColor=white" alt="Source Code" /></a>
      </p>
    </td>
  </tr>
</table>

**Also shipped:** [Lumina](https://ecommerce-website-puce-beta.vercel.app/) — a storefront with Stripe checkout, verified reviews and an admin console · [GameStore TN](https://gamestore-tn.cast-cue.workers.dev) — a marketplace for the Tunisian gaming scene, built local-first around how payments actually work here · [my portfolio](https://my-portfolio-seven-chi-94.vercel.app) · [more repos](https://github.com/AmineMabrouk17?tab=repositories)

---

### How I work with a client

**1. One call, then a scope.** We agree what ships in week one, week two, week three. You know the price before I write code.

**2. A live URL every week.** Every change arrives as a pull request with its own preview deploy and screenshots of what changed. You click it on your phone and judge for yourself — no "trust me, it's done".

**3. Tests where money and data live.** Checkout, auth and anything that writes to your database gets an automated test that runs in CI. If it breaks, I find out before you do.

**4. Handover that holds up.** Repo, environment variables, deploy steps and the decisions written down. You can hire anyone after me, and they'll understand the code — that's the point.

*Fixed-price milestones. You approve each one before it starts — no hourly surprises.*

---

### Languages, and where to see them

No skills list you have to take on faith — every line points at a repo you can open.

| Proven in my repos | Where |
|---|---|
| **TypeScript · React · Next.js · Tailwind** | BudgetIQ, Lumina, Cast n Cue, crypto-stocks |
| **Python** | BudgetIQ assistant backend, MustacharAI (FastAPI), CI scripts |
| **Rust** | crypto-stocks market service — Dockerised on a VPS |
| **Go** | gotn-shop — pluggable store scraper |
| **Solidity** | TrustlessEscrow — Foundry, deployed on Sepolia |
| **SQL / PostgreSQL** | row-level security policies and migrations in BudgetIQ and Lumina |
| **Bash / Shell** | telegram-ci-notify, plus CI in every repo |
| **Astro · HTML · CSS** | landing pages and this portfolio |

**Services I integrate:** Stripe Checkout · Gemini, Groq, OpenAI, Anthropic · Cloudflare Workers + D1 · Supabase · Playwright · Docker · GitHub Actions

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=nextjs,react,ts,js,tailwind,python,rust,go,solidity,postgres,supabase,cloudflare,stripe,docker,git,githubactions&perline=8" />
  </a>
</p>

---

### Let's talk

Send one short paragraph: what you're building, when you need it, and roughly what you can spend. You'll get an answer with whether I'm the right fit, what it takes, and the price — not a sales call.

<a href="mailto:amx72001@gmail.com"><img src="https://img.shields.io/badge/EMAIL_ME-amx72001@gmail.com-2ea44f?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
&nbsp;
<a href="https://www.linkedin.com/in/amine-mabrouk"><img src="https://img.shields.io/badge/CONNECT_ON_LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>

---

### GitHub

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="./github-snake.svg" />
    <img alt="github contribution snake animation" src="./github-snake.svg" width="100%" />
  </picture>
  <br /><br />
  <a href="https://github.com/AmineMabrouk17">
    <img src="./streak.svg" width="49%" alt="Streak Stats" />
  </a>
  <a href="https://github.com/AmineMabrouk17">
    <img src="./stats.svg" width="49%" alt="Stats" />
  </a>
</div>

<br />

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=AmineMabrouk17&color=00f2fe&style=flat-square&label=PROFILE+VIEWS" />
</p>
