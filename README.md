# Prompt-Quarry
My personal library of AI prompts for coding, writing, and more — organized by category, MIT licensed.

# ⛏️ Prompt-Quarry

A personal quarry of AI prompts — mined, refined, and organized by category. Every prompt here is written for production use: clear roles, explicit instructions, defined output formats, and guardrails against the most common failure modes (hallucination, vague answers, silent assumptions).

Free to use, fork, and adapt. MIT licensed.

---

## Why this repo exists

Most prompt collections online are one-liners ("act as an expert in X"). The prompts in this repo are structured, tested templates meant to produce **consistent, high-quality output** — not just a plausible-sounding first draft. Each one defines:

- A **role** with relevant expertise and behavioral guardrails
- A clear **task** and the **context** needed to do it well
- Explicit **instructions** that prevent common failure modes (guessing, hallucinating details, ignoring edge cases, padding output with filler)
- A defined **output format** so results are consistent and easy to use

## How to use these prompts

1. Open the `.md` file for the prompt you need.
2. Copy the full prompt into your AI tool of choice (Claude, ChatGPT, etc.).
3. Fill in the placeholders — anything in `{curly_braces}` — with your actual content (e.g. `{language}` → `Python`, `{paste_code}` → your code block).
4. Leave placeholders you don't have info for blank or delete that line; most prompts are written to handle missing optional context gracefully.

No special tooling required — these are plain-text prompts designed to work in any chat-based AI interface.

## Categories

| Category | Description | Prompts |
|---|---|---|
| [Software Development Templates](./Software%20Development%20Templates) | Code review, debugging, testing, architecture, and dev workflow prompts | 11 |
| [Content Writing Templates](./Content%20Writing%20Templates) | Blog posts, articles, editing, tone adjustment, long-form writing | Coming soon |
| [Data Analysis Templates](./Data%20Analysis%20Templates) | Data cleaning, exploration, reporting, and insight generation | Coming soon |
| [Business & Strategy Templates](./Business%20%26%20Strategy%20Templates) | Planning, decision frameworks, competitive analysis, pitches | Coming soon |
| [Education & Learning Templates](./Education%20%26%20Learning%20Templates) | Explainers, study guides, lesson planning, concept breakdowns | Coming soon |
| [Marketing & SEO Templates](./Marketing%20%26%20SEO%20Templates) | Campaign copy, SEO content, keyword strategy, ad copy | Coming soon |
| [Creative & Design Templates](./Creative%20%26%20Design%20Templates) | Brainstorming, creative writing, design briefs, naming | Coming soon |
| [Productivity & Operations Templates](./Productivity%20%26%20Operations%20Templates) | Workflow design, meeting notes, process docs, task planning | Coming soon |

## Software Development Templates

| Prompt | What it does |
|---|---|
| [Code Review](./Software%20Development%20Templates/Code%20Review.md) | Reviews code for bugs, security issues, and performance problems, ranked by severity |
| [API Design](./Software%20Development%20Templates/API%20Design.md) | Designs REST API endpoints with a full OpenAPI 3.0 spec, error handling, and rate limiting |
| [Debug Helper](./Software%20Development%20Templates/Debug%20Helper.md) | Diagnoses root causes from stack traces and proposes a verified fix |
| [Unit Test Generator](./Software%20Development%20Templates/Unit%20Test%20Generator.md) | Writes comprehensive unit tests covering happy paths, edge cases, and error handling |
| [SQL Query from Natural Language](./Software%20Development%20Templates/SQL%20Query%20from%20Natural%20Language.md) | Converts plain-English requests into optimized, dialect-correct SQL |
| [Regex Pattern Explainer](./Software%20Development%20Templates/Regex%20Pattern%20Explainer.md) | Breaks down regex patterns token-by-token and flags edge cases and backtracking risk |
| [Performance Optimisation Advisor](./Software%20Development%20Templates/Performance%20Optimisation%20Advisor.md) | Finds real bottlenecks and ranks fixes by actual impact, not guesswork |
| [Architecture Decision Record](./Software%20Development%20Templates/Architecture%20Decision%20Record.md) | Writes a full ADR with honest trade-offs and real alternatives considered |
| [Git Commit Message Generator](./Software%20Development%20Templates/Git%20Commit%20Message%20Generator.md) | Generates Conventional Commits messages from a diff |
| [Error Message Improver](./Software%20Development%20Templates/Error%20Message%20Improver.md) | Rewrites technical errors into clear, honest, user-facing messages |
| [Pull Request Description Generator](./Software%20Development%20Templates/Pull%20Request%20Description%20Generator.md) | Turns a diff into a PR description that explains the "why," not just the "what" |

*(More categories and prompts are added regularly — see the table above for what's live.)*

## Keywords

`ai prompts` `prompt engineering` `prompt library` `chatgpt prompts` `claude prompts` `llm prompts` `prompt templates` `prompt collection` `software development prompts` `code review prompt` `structured prompts` `production prompts` `awesome prompts`

## License

MIT — use these however you like, no attribution required (but appreciated).
