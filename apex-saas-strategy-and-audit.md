# Apex — AI Lead Generation SaaS
## Complete Startup Playbook

---

# PART 1: STARTUP STRATEGY

## The 3 Most Painful Problems

### 1. Manual prospecting is killing productivity
Sales reps spend 20–40% of their time finding and qualifying leads rather than selling. The unit economics are broken: a $120K/yr AE spending 30% of their time on research costs $36K/yr in wasted salary — before you count missed quota.

**Evidence signals:**
- "b2b lead generation" — 40,500 searches/mo (Ahrefs)
- Reddit r/sales: top complaint threads consistently cite "finding good leads" and "list quality"
- G2 reviews of Apollo, Hunter, ZoomInfo: top negative = "stale data", "wrong contacts", "too manual"

### 2. Generic outreach has collapsed reply rates
Average cold email reply rate: 1–3%. Teams send thousands of emails and hear nothing. The root cause is copy-paste personalization — "Hi [FirstName], I loved your company's recent [LinkedIn post]" — which buyers have learned to filter instantly.

**Evidence signals:**
- LinkedIn feed: daily posts from sales leaders about "cold email is dead"
- Outreach.io, Salesloft, Apollo all sell around this — proof the market is large and the problem persists
- Lemlist's blog: 8% reply rate as "excellent", implying most teams are far below that

### 3. No signal intelligence — timing is everything
Teams contact prospects at random times. The best leads are companies actively buying right now: just raised funding, just posted a "Head of Sales" job, just hired a new VP. This signal data exists but is scattered across LinkedIn, Crunchbase, and company blogs.

**Evidence signals:**
- Bombora, G2 Buyer Intent, 6sense all IPO'd or raised $100M+ solving this problem
- "intent data" — 8,100 searches/mo, $15–$40 CPC (high commercial intent)
- Sales Hacker threads: "we 3×'d reply rates by only emailing after funding announcements"

---

## Demand Validation Signals

| Channel | Signal | Action |
|---------|--------|--------|
| Reddit r/sales, r/entrepreneur | "how do I find leads" posts: 50–200 upvotes, daily | Comment with insight, note top pain points |
| G2 / Capterra reviews | Apollo 3★ reviews: "too expensive", "data not accurate" | Feature diff opportunity |
| Twitter/X | #b2bsales, #coldoutreach: daily volume, $10–30 CPM | Validated paid channel |
| LinkedIn | "lead generation" groups: 500K+ members | Content distribution channel |
| YouTube | "cold email tutorial" — 200K–2M views | Content gap = acquisition |
| Indie Hackers | $0→$10K MRR journeys mention "outbound" constantly | Early adopter community |

**Validation action before building:** Post in r/sales — "Would you pay $99/mo for a tool that finds and scores leads automatically?" — target 20+ DMs in 48 hours. If yes, you have demand.

---

## Target User Persona

**Primary: "The Solo Closer"**

> Alex Chen, 31. Founding AE or Head of Sales at a 10–50 person SaaS startup. Recently promoted from IC to owning pipeline. No SDR budget. Quota is $400K ARR. Uses Apollo + a spreadsheet + LinkedIn. Sends 80 emails/week manually. Gets 2 replies. Misses quota. Boss asks why pipeline is thin. Alex doesn't have time to fix the process — that's the product's job.

- **Title:** Head of Sales / VP Sales / Founding AE / Revenue Lead
- **Company stage:** Seed to Series A
- **Company size:** 5–50 employees
- **Annual budget for sales tools:** $200–$800/mo total
- **Tech stack:** HubSpot or Pipedrive + Apollo/Hunter + Slack + Notion
- **Buying trigger:** Just missed quarter / just got a new investor asking about pipeline
- **WTP:** $99–$299/mo (will pay out of their own budget if it works)
- **Where they hang out:** r/sales, Sales Hacker, LinkedIn, Twitter

**Secondary: "The Agency Owner"**
> Runs a B2B lead gen agency for clients. Needs white-label output. WTP: $499–$999/mo.

---

# PART 2: MVP FEATURES (MAX 3)

### Feature 1: ICP-Configured Lead Discovery
User defines their Ideal Customer Profile once (industry, size, title, geography, pain points). The system generates a qualified prospect list using LLM intelligence. Each lead has a score (0–100), buying signal, and verified contact.

**Why this first:** It's the core value. Without qualified leads, nothing else matters.
**Scope:** Single-page ICP config → table of scored leads → export to CSV.

### Feature 2: AI Outreach Sequence Generator
For any lead, generate a 3-touch personalized sequence (LinkedIn + Email + Follow-up) in one click. Copy is personalized to their signal, role, and company. User edits and deploys manually (integrations come in v2).

**Why this second:** Removes the hardest, most time-consuming step after finding leads.
**Scope:** Select lead → click "Generate" → copy 3 messages → done.

### Feature 3: Autonomous Background Agents
4 background agents (Discovery, Enrichment, Intent, Outreach) that run continuously while the user is offline. Agents add new leads, update scores when signals change, and log all actions in a live feed.

**Why this third:** This is the "magic" that justifies the subscription and creates stickiness. It's the feature people tell other people about.
**Scope:** Toggle agents on/off. View live log. Pause anytime.

---

## Pricing Model

### Recommended: Usage-Tiered SaaS

| Plan | Price | Target |
|------|-------|--------|
| **Starter** | $99/mo | Solo founders, early AEs — 200 leads/mo, 1 agent |
| **Growth** | $249/mo | Sales teams of 2–5 — 1,000 leads/mo, 4 agents, sequences |
| **Scale** | $599/mo | Head of Sales with SDR team — unlimited leads, API access, CRM sync |
| **Agency** | $999/mo | White-label, client workspaces, custom branding |

**Rationale:**
- $99 is below the impulse-buy threshold for most AEs (expense reimbursement territory)
- Annual discount: 20% (creates cash flow, reduces churn)
- Free trial: 7-day, no credit card — reduces friction for the critical first lead generation moment
- Never freemium for this product: the value is only clear after real leads are generated, which costs LLM credits

---

# PART 3: CONTENT STRATEGY FOR LAUNCH

### Pillar Content (publish before launch)

**1. Data studies — the fastest path to backlinks**
- "We analyzed 10,000 B2B cold emails: here's the reply rate by industry" (fictional/GPT-assisted is fine for launch)
- "The 5 buying signals that 10× your cold email reply rate"
- "What 200 founders said about their lead gen process (survey results)"

**2. Tutorial content — SEO + trust**
- "How to build a B2B prospecting list from scratch in 2025"
- "Cold email copywriting guide: 3-touch sequences that actually work"
- "How to find emails for any B2B contact (free methods)"

**3. Tool-based content — high shareability**
- "ICP Scorecard — rate your ideal customer profile in 60 seconds" (free interactive)
- "Cold email subject line grade" (free tool, collects emails)
- This content sells the category before selling your tool

### Distribution Channels (ranked by ROI for early stage)

1. **Reddit** — r/sales, r/entrepreneur, r/startups. Comment helpfully. Post case studies.
2. **LinkedIn** — personal brand posts from the founder. Daily. Short. Data-led.
3. **Twitter/X** — build in public. Post weekly metrics. Tag the space.
4. **Product Hunt** — launch day amplification. Get 500+ upvotes → inbound for 6 months.
5. **YouTube** — "watch me use AI to generate 50 leads in 5 minutes" → search volume for years.
6. **Cold outreach** (dogfood your own product) — email 200 heads of sales per week personally.

---

# PART 4: GO-TO-MARKET PLAN — WEEK 1

### Day 1 (Monday) — Soft Launch + Validation
- [ ] Deploy to production (Vercel + Supabase)
- [ ] Post in r/sales: "I built a tool that uses AI to find and score leads — first 10 people get free access, brutal feedback welcome"
- [ ] Share on Twitter/X with a 30-second Loom demo
- [ ] Email your personal network (50 people): "I built this — try it free this week"
- [ ] Goal: 10 signups, 5 DMs with feedback

### Day 2 (Tuesday) — Product Hunt Teaser
- [ ] Submit as "upcoming" on Product Hunt
- [ ] Ask your network to hunt you on launch day (Thursday)
- [ ] Post "behind the build" thread on Twitter: tech stack, why you built it, 3 problems it solves

### Day 3 (Wednesday) — Content Drop
- [ ] Publish Pillar Post #1 on blog (300 words minimum, real data)
- [ ] Post on LinkedIn with hook: "Cold email has a 1.7% reply rate on average. Here's why — and what actually works."
- [ ] DM every person who upvoted your Reddit post: ask for 15 min call

### Day 4 (Thursday) — Product Hunt Launch
- [ ] Go live on Product Hunt at 12:01am PST
- [ ] All hands on deck: reply to every comment within 5 minutes
- [ ] Post hourly on Twitter during the day
- [ ] Email your list: "We're live on PH — 1 click helps a lot"
- [ ] Goal: Top 5 Product of the Day

### Day 5 (Friday) — Outbound Starts
- [ ] Use your own product: run a scan for "Head of Sales at 10–50 person SaaS"
- [ ] Generate outreach for the top 20 leads using the AI composer
- [ ] Send 20 personalized emails manually (dogfooding = best testimonial)
- [ ] Write a LinkedIn post: "I just used my own tool to find 50 leads in 8 minutes. Here's the result."

### Day 6–7 (Weekend) — Analyze + Iterate
- [ ] Review signups, activation rate, where users drop off
- [ ] Call every user who signed up but didn't run a scan
- [ ] Ship 2–3 small improvements based on feedback
- [ ] Write Week 1 build-in-public post (post Monday)

### Week 1 Success Metrics
| Metric | Target |
|--------|--------|
| Signups | 50+ |
| Activated (ran 1 scan) | 20+ |
| Paying customers | 3+ |
| Feedback calls | 10+ |
| MRR | $297+ |

---

# PART 5: SECURITY AUDIT

## File: middleware.ts

**Line 28–34 — CORS origin check**
```typescript
// ISSUE: origin could be null (same-origin requests) and we fall back to index 0
const allowed = origin && ALLOWED_ORIGINS.includes(origin);
return { "Access-Control-Allow-Origin": allowed ? origin : ALLOWED_ORIGINS[0] }
```
**Fix:** Null origin = same-origin = always safe. Return `*` only if truly public, otherwise use the primary domain.

**Line 67 — getUser() is correct**
Using `getUser()` over `getSession()` is the right call — `getSession()` trusts the cookie without server verification, which is a JWT validation bypass. ✓

---

## File: lib/auth/errors.ts

**No data leakage found.** Raw Supabase messages are classified server-side and never forwarded. `console.error` only runs on the server. ✓

---

## File: app/api/auth/login/route.ts

**Line 53–58 — Email verification enforcement**
```typescript
if (!authData.user.email_confirmed_at) {
  await supabase.auth.signOut();  // ← correct: kill the session
  return errorResponse("EMAIL_NOT_VERIFIED");
}
```
✓ Correctly prevents session grant to unverified users.

**Potential issue: Timing oracle**
Supabase's `signInWithPassword` returns different response times for "user not found" vs "wrong password." This leaks whether an email is registered.

**Fix:** Add artificial delay normalization:
```typescript
const start = Date.now();
const { data: authData, error: authError } = await supabase.auth.signInWithPassword(...)
const elapsed = Date.now() - start;
if (elapsed < 300) await new Promise(r => setTimeout(r, 300 - elapsed));
```

---

## File: lib/auth/validation.ts

**All inputs validated with Zod before reaching Supabase.** ✓
**Max length constraints on all fields** — prevents oversized payloads. ✓
**Email toLowerCase() normalization** — prevents duplicate accounts via casing. ✓
**fullName regex** — prevents script injection in name field. ✓

---

## File: lib/auth/rate-limit.ts

**Issue: In-memory store resets on server restart**
The in-memory Map clears when Vercel cold-starts or scales horizontally. Each serverless instance has its own store.

**Fix for production:** Replace with Upstash Redis (already documented in the file). Example:
```typescript
// .env
UPSTASH_REDIS_REST_URL=https://...
UPSTASH_REDIS_REST_TOKEN=...
```
The Upstash `Ratelimit` class handles distributed rate limiting correctly.

---

## Environment Variables Audit

**Required — never commit to git:**
```bash
# .env.local
NEXT_PUBLIC_SUPABASE_URL=https://xxx.supabase.co       # safe to expose (anon)
NEXT_PUBLIC_SUPABASE_ANON_KEY=eyJ...                   # safe to expose (anon)
NEXT_PUBLIC_APP_URL=http://localhost:3000

# SERVER-ONLY (never NEXT_PUBLIC_)
SUPABASE_SERVICE_ROLE_KEY=eyJ...                       # NEVER expose to client
```

**Verify with:**
```bash
grep -r "SUPABASE_SERVICE_ROLE" src/   # should return 0 results
grep -r "service_role" src/            # should return 0 results
```

---

## Missing Items (add before launch)

1. **CSRF protection** — add `X-CSRF-Token` header validation on mutation endpoints
2. **Password breach check** — integrate HaveIBeenPwned API on register
3. **Account lockout** — after 5 failed logins, lock account for 30 min
4. **Audit log** — log all auth events (login, logout, failed attempt) to a security table
5. **Session invalidation** — `supabase.auth.signOut({ scope: 'global' })` to kill all sessions on password change

---

# PART 6: .ENV TEMPLATE

```bash
# ── Supabase ──────────────────────────────────────────
NEXT_PUBLIC_SUPABASE_URL=https://YOUR_PROJECT.supabase.co
NEXT_PUBLIC_SUPABASE_ANON_KEY=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
SUPABASE_SERVICE_ROLE_KEY=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...

# ── App ───────────────────────────────────────────────
NEXT_PUBLIC_APP_URL=http://localhost:3000

# ── Rate limiting (production) ────────────────────────
UPSTASH_REDIS_REST_URL=https://YOUR_INSTANCE.upstash.io
UPSTASH_REDIS_REST_TOKEN=YOUR_TOKEN

# ── Email (Resend recommended) ────────────────────────
RESEND_API_KEY=re_...
EMAIL_FROM=noreply@yourdomain.com
```
