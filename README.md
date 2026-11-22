<div align="center">

<img src="https://my-portfolio-seven-chi-94.vercel.app/opengraph-image" width="0" height="0" alt="" />

# Amine Mabrouk

**Full-stack engineer in Tunis.** I build web products end to end — database schema, API, interface, payments, deploy — and hand them over working.

<a href="mailto:amx72001@gmail.com"><img src="https://img.shields.io/badge/AVAILABLE_FOR_FREELANCE-2ea44f?style=for-the-badge&logo=gmail&logoColor=white" alt="Available for freelance work" /></a>
&nbsp;
<a href="https://my-portfolio-seven-chi-94.vercel.app"><img src="https://img.shields.io/badge/PORTFOLIO-4f46e5?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
&nbsp;
<a href="https://www.linkedin.com/in/amine-mabrouk"><img src="https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>

**You describe the product. I ship it — deployed, tested, documented.**

</div>

---

### What I actually do

Most freelancers sell you a frontend and disappear when the database gets hard. I take the whole thing:

**Schema → API → interface → payments → CI → deploy → handover.**

That means one person accountable for the product working, instead of three contractors pointing at each other. You get a live URL every week, not a status report.

I'm not a "prompt-to-app" shop. I use AI heavily to move faster — but I decide the architecture, what gets tested, and where the security boundary sits. Those decisions come with a written reason you can read later.

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
      <h3>🛒 Lumina — e-commerce storefront</h3>
      <p><i>The store an actual shop would run on, not the tutorial version.</i></p>
      <p><b>The problem:</b> "e-commerce demo" usually means product cards and a dead checkout button.</p>
      <p><b>What I built:</b> catalog, cart drawer, Stripe Checkout, verified reviews, and an admin console for order fulfillment. Relational PostgreSQL models behind it, plus an end-to-end test suite wired into CI so a redesign can't quietly break checkout. Built in ten days.</p>
      <p><code>Next.js</code> · <code>Supabase</code> · <code>Stripe</code> · <code>PostgreSQL</code> · <code>Playwright E2E</code></p>
      <p><b>171 commits</b> · 90+ pull requests · E2E suite green in CI</p>
      <p>
        <a href="https://ecommerce-website-puce-beta.vercel.app/"><img src="https://img.shields.io/badge/LIVE_DEMO-4f46e5?style=for-the-badge&logo=vercel&logoColor=white" alt="Live Demo" /></a>
        &nbsp;
        <a href="https://github.com/AmineMabrouk17/ecommerce-website"><img src="https://img.shields.io/badge/SOURCE-181717?style=for-the-badge&logo=github&logoColor=white" alt="Source Code" /></a>
      </p>
    </td>
  </tr>
</table>

**Also shipped:** [GameStore TN](https://gamestore-tn.cast-cue.workers.dev) — a marketplace for the Tunisian gaming scene (PES/eFootball, Free Fire), built local-first around how payments actually work here · [my portfolio](https://my-portfolio-seven-chi-94.vercel.app) · [more repos](https://github.com/AmineMabrouk17?tab=repositories)

---

### How I work with a client

**1. One call, then a scope.** We agree what ships in week one, week two, week three. You know the price before I write code.

**2. A live URL every week.** Every change arrives as a pull request with its own preview deploy and screenshots of what changed. You click it on your phone and judge for yourself — no "trust me, it's done".

**3. Tests where money and data live.** Checkout, auth and anything that writes to your database gets an automated test that runs in CI. If it breaks, I find out before you do.

**4. Handover that holds up.** Repo, environment variables, deploy steps and the decisions written down. You can hire anyone after me, and they'll understand the code — that's the point.

**On AI:** I use it daily and I'll tell you exactly where. What I don't delegate is the schema, the tests, the security boundaries, or the judgement about what your product actually needs.

---

### What I work with

| Layer | Tools I reach for |
|---|---|
| Frontend | **Next.js**, **React**, **TypeScript**, **Tailwind**, **Angular** |
| Backend | **Laravel**, **FastAPI**, **Python**, **Rust** (when the workload needs it) |
| Data | **PostgreSQL**, **Supabase + RLS**, **Cloudflare D1**, **ChromaDB** |
| Payments | **Stripe Checkout**, order and fulfillment flows |
| AI | **Gemini**, **Groq**, **OpenAI**, **Anthropic**, **RAG with citations**, streaming |
| Deploy & CI | **Cloudflare Workers**, **Vercel**, **Docker**, **GitHub Actions**, **Playwright** |

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=nextjs,react,ts,tailwind,angular,laravel,flask,python,rust,postgres,supabase,cloudflare,stripe,docker,git,githubactions&perline=8" />
  </a>
</p>

---

### Let's talk

Tell me the product, the deadline, and what "done" means to you. I'll tell you honestly whether I'm the right person, what it takes, and what it costs.

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
