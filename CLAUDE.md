# CLAUDE.md — Clarity Principle

## What This Project Is

Clarity Principle (clarityprinciple.ai) is a concept — a named principle for building a live explainability layer into enterprise and SaaS applications. It is not a product, not a library, not a framework. It is an idea that changes how business logic is understood by everyone who interacts with a system, not just engineers.

The core insight: when deterministic business logic is paired with LLM-powered narration, a system can explain what it decided and why — in real time, in the language of the business, without building separate infrastructure. The LLM does not make decisions. It narrates decisions the deterministic system already made.

## The Problem It Solves

Business logic in software is invisible to everyone except the engineers who wrote it. Documentation rots. Logs are unreadable to non-engineers. Product managers spend enormous time translating between business intent and system behavior. Every requirement refinement starts from scratch because nobody can see what the system is actually deciding.

The Clarity Principle makes business logic visible as a live artifact — generated at the moment a decision happens, inside the production application, in language any stakeholder can read and react to.

## The Quoting System Example

A quoting system receives a customer request. The system applies pricing rules, inventory logic, and customer tier calculations. Alongside the generated quote, there is a narrative tab explaining: why this price, how stock was allocated, which customer segment was matched, which rule determined the discount. The business stakeholder reads this and immediately sees an edge case that was never discussed. A requirement refinement that would have taken weeks surfaces in seconds. Data quality issues that were invisible in the output become visible in the explanation.

## Target Audience

- Product managers at enterprise and SaaS companies
- CTOs and engineering leaders
- Senior software engineers working on business-critical systems
- Business stakeholders who are technically curious

## The Four Values

1. **Accelerated conversation** — immediate, human-readable account of why a decision was made
2. **Live audit trail** — every decision documented at the moment it happens, compliance-ready
3. **Visible business logic** — legible to anyone, not just engineers
4. **Internal adoption and advocacy** — when people understand how the system works, they trust and advocate for it

## What This Site Does

The website serves four goals:

1. Help visitors understand the concept clearly
2. Provide the quoting system as a concrete example
3. Show where the AI agent implementations are going (coming soon section)
4. Connect visitors to the GitHub repo and to the founder

## Design Principles

- Clean and minimal — let the concept breathe
- Strong typography carries the weight, not decoration
- No startup pitch energy — this is thought leadership
- The writing is the design
- Dark/light neutral palette, generous whitespace
- Single scrolling page at launch

## Site Structure at Launch

1. **Hero** — the principle stated clearly and boldly. One sentence that lands.
2. **The Problem** — why business logic has always been invisible and what that costs
3. **The Principle** — what the Clarity layer is and how it works
4. **Example** — the quoting system walkthrough, concrete and specific
5. **The Four Values** — what it delivers for product managers and engineering teams
6. **Coming Soon** — AI agents for Claude Code and Cursor that help implement the principle
7. **GitHub** — link to the open source repo
8. **About** — the founder, the personal brand, how to follow or connect

## Voice and Tone

- Confident but not arrogant
- Concrete before abstract — always lead with the example, not the theory
- Speaks to product managers first, engineers second
- No jargon unless it earns its place
- Short sentences. Strong verbs.

## Technical Setup

- GitHub Pages, plain HTML/CSS
- No frameworks, no build pipeline
- Single index.html file at launch
- Mobile responsive
- Fast loading — no heavy assets

## Future Additions

- AI agent for Claude Code (system prompt + usage guide)
- AI agent for Cursor
- Additional domain examples beyond quoting systems
- Community contributions

---

## First Claude Code Session Prompt

Paste this when you start your first Claude Code session inside the repo.

> I am building clarityprinciple.ai — a single page concept website that lives on GitHub Pages. Read the CLAUDE.md file first for full context before doing anything else.
>
> Here is what I need you to build:
>
> A single index.html file. Clean, minimal, beautifully typeset. No frameworks, no build pipeline, everything in one file including CSS. Mobile responsive.
>
> The page has these sections in order:
>
> 1. **Hero** — A bold, clear statement of the principle. Something like: "Business logic should explain itself." or "Every decision your system makes should be legible to everyone who matters." Then a one paragraph description of what the Clarity Principle is. A single CTA button pointing to the GitHub repo.
>
> 2. **The Problem** — Two to three short paragraphs. Documentation rots. Logs are for engineers. Product managers are the translation layer and that costs time and momentum. When the system makes a decision, nobody outside engineering knows why.
>
> 3. **The Principle** — Explain the Clarity layer clearly. Deterministic system makes the decision. LLM narrates it. The result is a live artifact — not documentation, not a log, but an explanation generated at the moment the decision happens, inside the production application.
>
> 4. **The Example** — The quoting system. Make this feel concrete and real. Show the before — quote generated, nothing explained. Show the after — quote generated, narrative tab alongside it explaining why this price, how stock was allocated, which customer segment matched. Show what this surfaces: the edge case nobody discussed, the data quality issue that was invisible, the requirement refinement that took weeks now taking seconds.
>
> 5. **The Four Values** — Four clean cards or sections. Accelerated conversation. Live audit trail. Visible business logic. Internal adoption. Each with a one sentence headline and two sentences of explanation.
>
> 6. **Coming Soon — AI Agents** — A section that signals what is being built. An explainability agent for Claude Code and one for Cursor. These agents read your codebase, identify where business decisions are being made, and suggest exactly where a Clarity layer should be added. Show this as coming soon with a GitHub link to follow for updates.
>
> 7. **GitHub** — Clean section pointing to the open source repo. One line of context, one button.
>
> 8. **About** — Short. The founder's name, one sentence bio, LinkedIn and GitHub links. This is personal brand — keep it human, not corporate.
>
> Design direction:
>
> - Clean and minimal — the writing carries the weight
> - Dark neutral background or crisp white — no gradients, no decoration
> - One strong accent color — deep blue or near-black
> - Large, confident typography for headings
> - Generous whitespace throughout
> - The page should feel like something a thoughtful CTO would trust immediately
>
> Start by reading CLAUDE.md, then build the full index.html in one pass. Ask me any questions about content before you start building.
