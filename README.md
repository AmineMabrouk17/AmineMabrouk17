<div align="center">

<img src="https://my-portfolio-seven-chi-94.vercel.app/opengraph-image" width="0" height="0" alt="" />

# Amine Mabrouk

**Full-stack engineer in Tunis.** I take web products from an empty repository to a live URL. That covers the database schema, the API, the interface, payments, and the CI that keeps it running.

<a href="mailto:amx72001@gmail.com"><img src="https://img.shields.io/badge/AVAILABLE_FOR_FREELANCE-2ea44f?style=for-the-badge&logo=gmail&logoColor=white" alt="Available for freelance work" /></a>
&nbsp;
<a href="https://my-portfolio-seven-chi-94.vercel.app"><img src="https://img.shields.io/badge/PORTFOLIO-4f46e5?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
&nbsp;
<a href="https://www.linkedin.com/in/amine-mabroukk/"><img src="https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>

**You describe the product. I ship it, tested and deployed, and hand it over working.**

</div>

---

### What I actually do

Most projects fail where two people hand work to each other. The designer hands off to the frontend developer, who hands off to the backend developer, who hands off to whoever deploys. I do all of it, so there is no handoff to lose a requirement in.

**Schema → API → interface → payments → CI → deploy → handover.**

One person is accountable for the whole product. Every week you get a live URL you can open and judge.

Some clients hear "AI" and assume they are paying for prompts. The architecture, the tests, the security boundaries and the decision about what your product needs are mine, and I document them in the repository.

---

### What I can build for you

| You need | What I deliver |
|---|---|
| **A product, from zero** | Schema and migrations, authentication, role-based access, API, interface and deploy. You get working software in weeks. |
| **A dashboard on live data** | WebSocket and market feeds, charts, alerts, and caching that survives real traffic. |
| **AI inside your product** | Chat assistants and RAG that cite their sources, with streaming answers and four providers: Gemini, Groq, OpenAI and Anthropic. |
| **An online store that takes money** | Stripe checkout, orders, admin fulfillment, verified reviews and stock handling, including the admin screens nobody enjoys building. |
| **Arabic and RTL products** | Right-to-left interfaces and Tunisian market constraints handled from the first screen. |
| **An app that stays cheap to run** | Cloudflare Workers and D1, serverless deploys, Docker on a VPS when you need it, and CI that catches breakage before your users do. |

---

### Selected work

These products are live, and the source is public. The commit counts show that I keep shipping after launch rather than opening a repository once.

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3>BudgetIQ, an AI finance app</h3>
      <p><i>Type a sentence and the budget updates itself.</i></p>
      <p>Budget apps fail because logging every expense is tedious, and most people quit in the second week. A conversational assistant turns "I spent 45 dinars on groceries" into a confirmed transaction and an updated dashboard. The app tracks income, expenses and assets, plans a salary, and handles several currencies. Row-level security in PostgreSQL keeps each user's data separate, and you can self-host it against your own Supabase project.</p>
      <p><code>Next.js 16</code> · <code>React 19</code> · <code>Supabase + RLS</code> · <code>Gemini / OpenRouter</code> · <code>Recharts</code></p>
      <p>222 commits over 3.5 months, 180+ pull requests</p>
      <p>
        <a href="https://budgetiq-two.vercel.app"><img src="https://img.shields.io/badge/LIVE_DEMO-4f46e5?style=for-the-badge&logo=vercel&logoColor=white" alt="Live Demo" /></a>
        &nbsp;
        <a href="https://github.com/AmineMabrouk17/BudgetIQ"><img src="https://img.shields.io/badge/SOURCE-181717?style=for-the-badge&logo=github&logoColor=white" alt="Source Code" /></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>Crypto and Stocks, a live market terminal</h3>
      <p><i>It shows live prices without polling.</i></p>
      <p>Most market dashboards poll a public API every few seconds and fall apart under real traffic. Here crypto prices stream from Binance over WebSockets, and server-side proxies serve Yahoo Finance quotes for stocks and ETFs. The terminal draws live charts, keeps price alerts in the browser, and shows crowd odds from Polymarket. A separate Rust service runs on a VPS, and the repository carries ADRs, a glossary and a decision log so the reasoning survives.</p>
      <p><code>Next.js</code> · <code>WebSocket</code> · <code>Rust</code> · <code>Turborepo</code> · <code>lightweight-charts</code> · <code>Vitest</code></p>
      <p>152 commits, 70+ pull requests, Rust and TypeScript monorepo</p>
      <p>
        <a href="https://crypto-stocks-web-taupe.vercel.app"><img src="https://img.shields.io/badge/LIVE_DEMO-4f46e5?style=for-the-badge&logo=vercel&logoColor=white" alt="Live Demo" /></a>
        &nbsp;
        <a href="https://github.com/AmineMabrouk17/crypto-stocks"><img src="https://img.shields.io/badge/SOURCE-181717?style=for-the-badge&logo=github&logoColor=white" alt="Source Code" /></a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Cast n Cue, an edge-hosted app</h3>
      <p><i>I built it because the existing tool annoyed me.</i></p>
      <p>Trackers make episode-level watchlists painful, and most of them need a server you pay for. Cast n Cue tracks episodes, searches TMDB and Trakt, and takes half-star ratings. Private notes autosave while you type, and a roulette picks what to watch next. The app runs on Cloudflare Workers and D1 with Better Auth, so it stays fast and cheap at any traffic level.</p>
      <p><code>Next.js</code> · <code>Cloudflare Workers</code> · <code>D1</code> · <code>Better Auth</code></p>
      <p>219 commits, 70+ pull requests</p>
      <p>
        <a href="https://cast-cue.cast-cue.workers.dev"><img src="https://img.shields.io/badge/LIVE_DEMO-F38020?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Live Demo" /></a>
        &nbsp;
        <a href="https://github.com/AmineMabrouk17/Cast-Cue"><img src="https://img.shields.io/badge/SOURCE-181717?style=for-the-badge&logo=github&logoColor=white" alt="Source Code" /></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>MustacharAI, an Arabic legal assistant</h3>
      <p><i>It cites the article it used.</i></p>
      <p>Tunisian legal codes sit in PDFs written in formal Arabic. Generic chatbots answer confidently, cite nothing, and sound certain about the wrong article. A retrieval pipeline covers about 15 legal codes and 3,500 articles. Arabic-aware embeddings live in ChromaDB, and the RTL interface streams a citation with every answer. Voice input and spoken answers are included, and you choose the provider: Groq, Gemini, or your own OpenRouter key from the interface.</p>
      <p><code>FastAPI</code> · <code>ChromaDB</code> · <code>sentence-transformers</code> · <code>Next.js</code> · <code>RTL Arabic</code></p>
      <p>72 commits, Python and TypeScript, live</p>
      <p>
        <a href="https://mustachar-ai.vercel.app"><img src="https://img.shields.io/badge/LIVE_DEMO-4f46e5?style=for-the-badge&logo=vercel&logoColor=white" alt="Live Demo" /></a>
        &nbsp;
        <a href="https://github.com/AmineMabrouk17/MustacharAI"><img src="https://img.shields.io/badge/SOURCE-181717?style=for-the-badge&logo=github&logoColor=white" alt="Source Code" /></a>
      </p>
    </td>
  </tr>
</table>

I also built [Lumina](https://ecommerce-website-puce-beta.vercel.app/), a storefront with Stripe checkout, verified reviews and an admin console. [GameStore TN](https://gamestore-tn.cast-cue.workers.dev) is a marketplace for the Tunisian gaming scene built around how payments work here. My [portfolio](https://my-portfolio-seven-chi-94.vercel.app) and [other repositories](https://github.com/AmineMabrouk17?tab=repositories) are public.

---

### How I work with a client

**1. One call, then a scope.** We agree what ships in week one, week two and week three. You know the price before I write code.

**2. A live URL every week.** Each change arrives as a pull request with its own preview deploy and screenshots. You open it on your phone and judge it yourself.

**3. Tests where money and data live.** Checkout, authentication, and anything that writes to your database gets a test that runs in CI. When something breaks, I learn before you do.

**4. Handover that holds up.** You get the repository, the environment variables, the deploy steps and the recorded decisions. Anyone you hire later can read the code and understand it.

*We work on fixed-price milestones. You approve each one before it starts, so the invoice never grows while you wait.*

---

### Languages, and where to see them

Every line points at a repository you can open.

| Proven in my repos | Where |
|---|---|
| **TypeScript · React · Next.js · Tailwind** | BudgetIQ, Lumina, Cast n Cue, crypto-stocks |
| **Python** | BudgetIQ assistant backend, MustacharAI (FastAPI), CI scripts |
| **Rust** | crypto-stocks market service, Dockerised on a VPS |
| **Go** | gotn-shop, a pluggable store scraper |
| **Solidity** | TrustlessEscrow, Foundry, deployed on Sepolia |
| **SQL / PostgreSQL** | row-level security policies and migrations in BudgetIQ and Lumina |
| **Bash / Shell** | telegram-ci-notify, plus CI in every repository |
| **Astro · HTML · CSS** | landing pages and this portfolio |

I integrate Stripe Checkout, Gemini, Groq, OpenAI, Anthropic, Cloudflare Workers and D1, Supabase, Playwright, Docker and GitHub Actions.

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=nextjs,react,ts,js,tailwind,python,rust,go,solidity,postgres,supabase,cloudflare,stripe,docker,git,githubactions&perline=8" />
  </a>
</p>

---

### Talk to me

Send one short paragraph: what you are building, when you need it, and roughly what you can spend. I will answer with whether I am the right fit, what it takes and the price. You do not get a sales call.

<a href="mailto:amx72001@gmail.com"><img src="https://img.shields.io/badge/EMAIL_ME-amx72001@gmail.com-2ea44f?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
&nbsp;
<a href="https://www.linkedin.com/in/amine-mabroukk/"><img src="https://img.shields.io/badge/CONNECT_ON_LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>

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
