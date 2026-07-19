# Hi, I'm Dushyanth

Product Manager focused on building tools that reduce friction for professionals who spend too much time on admin work and not enough time on the actual work they trained for.

I approach product from evidence first — problem interviews, behavioral research, workaround analysis — before writing a single requirement.

---

## Featured Projects

### [SessionBrief](https://github.com/Dushyanth-Ships/sessionbrief) — Pre-session briefing tool for therapists

Solo therapists see 15–30 clients per week on back-to-back schedules. Before each session they have 5 minutes, at best, to recall where they left off. The most common workaround is asking clients "where do you want to start today?" — which transfers the therapist's memory failure to the client at the moment they are most vulnerable.

SessionBrief stores session notes per client and generates a one-page brief before each appointment, drawn entirely from the therapist's own notes — with every item traceable to its source.

**What's in the repo:**
- Field research across 18+ practitioner sources (Reddit, clinical forums, journalism)
- PRD v1 and v2 with three independent professional reviews (engineer, Director of Product, senior PM)
- **[Live demo](https://notes-app-54dfg.netlify.app/)** — runs in the browser, no install needed

### [AI Gift Recommendation System](https://github.com/Dushyanth-Ships/gift-recommender) — Gifting engine for a fast-fashion retail app

A fast-fashion retailer hit a growth ceiling after 10x expansion in three years — its teenage self-purchase market was saturated. Users already had social graphs inside the app, saved payment methods, and were discussing style preferences with friends. The opportunity was to monetize that existing social behavior through gifting.

This PRD defines an AI recommendation engine that turns self-purchasers into gifters, targeting 150K new gifters and $5M+ in gifting GMV within the first 60 days of the holiday season.

**What's in the repo:**
- [PRD (PDF)](https://github.com/Dushyanth-Ships/gift-recommender/raw/master/Dushyanth_Gift_Recommendation_PRD.pdf) — original document
- Hybrid recommendation engine design: collaborative + content-based filtering with explicit exogenous/autoregressive data classification
- Time-series demand forecasting model for inventory planning
- 6 user stories covering gift feed, occasion notifications, executive dashboard, weekly stakeholder email, purchase intent capture, and social gifting attribution
- 60-day success metrics with targets and rationale

### [Sentinel](https://github.com/Dushyanth-Ships/sentinel-ai) — Privacy-first in-car AI assistant

In-car AI assistants need location, contacts, calendar, and driving patterns to be useful — and none of that should leave the vehicle to be trustworthy. Most products choose usefulness and hope users don't read the privacy policy. Sentinel resolves the tension by making privacy the primary architectural constraint.

Built on a hybrid on-device + Anthropic Claude API architecture: sensitive data stays local or is stripped of PII before any cloud call. The cloud LLM never sees identifying information — it receives an anonymized, RAG-grounded query and returns a response capped at 150 tokens for driver safety.

**What's in the repo:**
- [Deck (PDF)](https://github.com/Dushyanth-Ships/sentinel-ai/raw/master/Dushyanth_Sentinel_AI_Car_Assistant_Deck.pdf) — original document
- 4-layer hybrid architecture with explicit data classification (on-device vs. cloud) for every data type
- Cloud API vs. self-hosted LLM trade-off analysis with privacy mitigation design
- RAG retrieval + output filtering pipeline targeting 95%+ factual accuracy
- Safety constraints: 150-token limit, voice-only, attention monitoring, offline fallback
- Success metrics across privacy, quality, and safety dimensions

---

## How I Work

- Start with workarounds. What are people doing today instead of using a product? Sticky notes, open-ended openers, Sunday catch-up blocks — these are physical prototypes of the product that should exist.
- Evidence before opinions. Every PRD claim traces to a real source. If the research doesn't support it, it goes to open questions, not requirements.
- Ship fewer things reliably. A brief with three verified items beats a brief with ten suspect ones.

---

## Skills

`Product strategy` `User research` `PRD writing` `Prioritization` `Prototyping` `AI product development` `HIPAA/compliance scoping`

---

## Get in touch

- Email: dushyanthkg@gmail.com
- [LinkedIn](https://www.linkedin.com/in/dushyanth-k-g-410504103)
