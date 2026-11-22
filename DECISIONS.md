# Decisions

## 2026-11-22 — Profile targets freelance clients, not recruiters

**Decision:** The README is written as a pitch to a client hiring one person for a whole product, not as a developer resumé.

**Why:** The user asked for it to be presented to freelance clients. Recruiter-facing content (language lists, achievements, contribution graph) does not answer "can this person deliver my product".

**Alternative considered:** A dual audience page. Rejected — it reads as neither and buries the hire-me call to action.

## 2026-11-22 — Four case studies chosen by commit count

**Decision:** Only BudgetIQ (222 commits), Cast n Cue (219), Lumina e-commerce (171) and crypto-stocks (152) appear as case studies; GameStore TN is a one-line mention and everything else is omitted.

**Why:** Selection was driven by `commits` and `languages` from the GitHub API. The user named MustacharAI, telegram-ci-notify, ThinkCode and gotn-shop as low investment, and the data agreed (3–72 commits).

**Alternative considered:** Showing every non-fork repo. Rejected — it dilutes four strong builds with ten thin ones.

## 2026-11-22 — Hero promise: empty repo to live URL

**Decision:** "I take web products from an empty repo to a live URL — database schema, API, interface, payments, and the CI that keeps it running."

**Why:** It states the scope with a beginning and an end that a non-technical client can picture, and it pairs with the badge line directly underneath.

**Alternative considered:** "One person owns your whole product" (accountability) and "products that actually go live" (speed). Both kept as the seam and process arguments instead.

## 2026-11-22 — Seam argument opens "What I actually do"

**Decision:** The section opens with "Projects break at the seams… There are no seams here." rather than a swipe at other freelancers.

**Why:** A diagnosis the client recognises from their own past projects reads as expertise; complaining about competitors reads as insecurity. It also sets up the `Schema → API → … → handover` line.

## 2026-11-22 — AI is stated once, as client anxiety

**Decision:** One paragraph — "Some clients hear AI and assume they're paying for prompts. Where it matters … the decisions are mine and documented." The duplicate "On AI:" line in the process section was deleted.

**Why:** Two weak mentions read as an apology; one firm mention reads as a boundary. Saying it twice also made the page self-conscious.

## 2026-11-22 — Six-service table kept, no rescue row

**Decision:** "What I can build for you" stays at its six rows (product from zero, live dashboards, AI, stores with money, Arabic/RTL, cheap-to-run apps).

**Why:** The user approved it as written. A rescue/legacy-project row was proposed and dropped because the page already carries nine sections.

## 2026-11-22 — Stack table lists only languages proven in public repos

**Decision:** "What I work with" became "Languages, and where to see them", restricted to TypeScript, JavaScript, Python, Rust, Go, Solidity, SQL/PostgreSQL, Bash and Astro/HTML/CSS. Laravel and Angular were removed.

**Why:** The user asked for the languages actually present in the repos. Aggregating `repos/*/languages` returns no PHP and no Angular, so a client who asks "show me" would have found nothing. Payments, AI providers, Workers/D1 and Docker moved to a "Services I integrate" line.

**Alternative considered:** Keeping Laravel/Angular under an "also worked with" note. Rejected for now — unverifiable claims are the first thing a technical client tests.

## 2026-11-22 — MustacharAI replaces Lumina as the fourth case study

**Decision:** The fourth card is MustacharAI (Arabic legal RAG, 72 commits), not Lumina e-commerce (171 commits). Lumina moves to the "Also shipped" line.

**Why:** The user chose it. It also proves two service rows Lumina only proves one of — "AI inside your product" (RAG with citations, provider switching) and "Arabic / RTL products" — which matters more for differentiating the page than a fourth Next.js storefront.

**Alternative considered:** Lumina kept as the payments proof (171 commits, Stripe, E2E in CI) and GameStore TN for the local-market angle. Lumina's payments proof is preserved by the "Also shipped" line so the Stripe row still has a link behind it.

## 2026-11-22 — Pricing stated as fixed milestones, not hourly

**Decision:** One italic line closes the process section: "Fixed-price milestones. You approve each one before it starts — no hourly surprises." No rates are published.

**Why:** "How do you charge?" is the second-call question, and an unanswered one reads as evasive. Milestone pricing answers it without committing to a number that depends on scope. Rates stay a conversation.

**Alternative considered:** A fifth process step and a full pricing section. Rejected — both turn a delivery page into a rate card, and the CTA already promises a quote after the brief.

## 2026-11-22 — CTA asks for budget, not for a call

**Decision:** The closing section invites one paragraph (what, when, roughly what you can spend) and promises a direct answer with a price — "not a sales call".

**Why:** A blank "contact me" pushes the work of writing the first message onto the client, and a human rarely sends it. Asking for a budget range up front filters out enquiries that were never going to pay, which is the main cost of freelancing.

**Alternative considered:** "I reply within one working day" and "two projects at a time". Both dropped — they are commitments only the user can make, and he did not confirm either.

## 2026-11-22 — Profile prose follows the unslop rules

**Decision:** The README prose was edited with the `unslop` skill: no em dashes, no contractions, no sentence over 25 words, no fragments, no inline bold labels inside paragraphs, no emoji in headings, and no binary-contrast or tailing-negation formulas.

**Why:** The user installed the skill and asked for the text to be cleaned. The draft carried the usual tells: em dashes in nearly every paragraph, "not X, it's Y" constructions, tailing negations such as "no hourly surprises", and emoji headings.

**Alternative considered:** Keeping the punchier fragments ("Projects break at the seams."). Rejected because the skill's sentence rules apply to prose outside quotes, and the same idea survives as a complete sentence.

## 2026-11-22 — Profile prose follows the unslop rules

**Decision:** The README prose was edited with the `unslop` skill: no em dashes, no contractions, no sentence longer than 25 words, no fragments, no inline bold labels in paragraphs, no emoji in headings, and no binary-contrast or tailing-negation formulas.

**Why:** The user installed the skill and asked for the profile text to be cleaned. The previous draft carried the usual tells: an em dash in most paragraphs, "not X, it's Y" constructions, tailing negations such as "no hourly surprises", and emoji card headings.

**Alternative considered:** Keeping the punchier fragments ("Projects break at the seams."). Rejected because the skill's sentence rules apply to all prose outside quotes, and the idea survives as a complete sentence.

## 2026-11-22 — Profile prose cleaned with the unslop skill

**Decision:** The README text now follows the `unslop` rules: no em dashes, no contractions, no fragment sentences, sentences of 25 words or fewer, no inline bold labels inside paragraphs, and no emoji in headings. The section heading "Let's talk" became "Talk to me".

**Why:** The user installed the skill and asked for the profile to be unslopped. The draft had the usual tells in almost every paragraph: em dashes as rhythm, "not X but Y" contrasts, tailing negations such as "no hourly surprises", and bold labels glued to the start of sentences.

**Alternative considered:** Keeping the short punchy fragments ("Projects break at the seams."). Rejected because the skill applies its sentence rules to all prose outside quotes, and the same claim survives as a complete sentence.

## 2026-11-22 — Humanizer pass on the profile prose

**Decision:** Five sentences were rewritten with the `humanizer` skill: the repeated "hands off" chain, a one-line closer, a "rather than" contrast in the Selected work intro, a heading-restating line above the languages table, and a clipped "no sales call" closer.

**Why:** The user installed the skill and asked for it. After the earlier unslop pass there were no dashes, fragments or stock words left, so only these five structural tells survived.

**Alternative considered:** Restoring contractions, which humanizer permits but unslop banned. Not applied, because the user asked only for the humanizer pass; offered separately.
