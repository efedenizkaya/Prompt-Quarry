# Software Development Templates

Structured prompts for the full lifecycle of writing, reviewing, testing, documenting, and shipping code — built to give consistent, evidence-based output instead of vague or hallucinated answers.

[← Back to main README](../README.md)

## Prompts

| Prompt | What it does |
|---|---|
| [API Design](./API%20Design.md) | Designs REST API endpoints with a full OpenAPI 3.0 spec, error handling, and rate limiting rules |
| [Architecture Decision Record](./Architecture%20Decision%20Record.md) | Writes a full ADR with honest trade-offs and real alternatives considered |
| [CI/CD Pipeline Generator](./CI-CD%20Pipeline%20Generator.md) | Generates a CI/CD pipeline config (GitHub Actions, GitLab CI, etc.) matched to your stack and deploy target |
| [Code Documentation Generator](./Code%20Documentation%20Generator.md) | Documents functions, classes, and modules — focused on what actually needs explaining, not restating the obvious |
| [Code Review](./Code%20Review.md) | Reviews code for bugs, security issues, and performance problems, ranked by severity |
| [Code-to-Diagram Explainer](./Code-to-Diagram%20Explainer.md) | Turns code or a system description into an accurate Mermaid.js diagram plus a written walkthrough |
| [Database Migration Script Writer](./Database%20Migration%20Script%20Writer.md) | Writes safe up/down migrations, with special care for large tables and zero-downtime requirements |
| [Debug Helper](./Debug%20Helper.md) | Diagnoses root causes from stack traces and proposes a verified fix, not a guess |
| [Dependency/Package Upgrade Analyzer](./Dependency-Package%20Upgrade%20Analyzer.md) | Assesses upgrade risk against real changelog evidence and your actual usage of the package |
| [Design Pattern Advisor](./Design%20Pattern%20Advisor.md) | Recommends a design pattern only when one genuinely fits — otherwise says so |
| [Error Message Improver](./Error%20Message%20Improver.md) | Rewrites technical errors into clear, honest, user-facing messages without leaking internals |
| [Git Commit Message Generator](./Git%20Commit%20Message%20Generator.md) | Generates Conventional Commits messages from a diff |
| [Legacy Code Modernizer](./Legacy%20Code%20Modernizer.md) | Modernizes old syntax/idioms while preserving behavior — flags anything that isn't purely mechanical |
| [Logging Strategy Advisor](./Logging%20Strategy%20Advisor.md) | Recommends what to log, at what level, and flags sensitive data that should never be logged |
| [Performance Optimisation Advisor](./Performance%20Optimisation%20Advisor.md) | Finds real bottlenecks and ranks fixes by actual impact, not guesswork |
| [Pull Request Description Generator](./Pull%20Request%20Description%20Generator.md) | Turns a diff into a PR description that explains the "why," not just the "what" |
| [Refactoring Advisor](./Refactoring%20Advisor.md) | Identifies genuine code smells with concrete cost, and skips changes that are purely stylistic |
| [Regex Pattern Explainer](./Regex%20Pattern%20Explainer.md) | Breaks down regex patterns token-by-token and flags edge cases and catastrophic backtracking risk |
| [SQL Query from Natural Language](./SQL%20Query%20from%20Natural%20Language.md) | Converts plain-English requests into optimized, dialect-correct SQL |
| [Test Coverage Gap Analyzer](./Test%20Coverage%20Gap%20Analyzer.md) | Finds meaningful test gaps and weak assertions in an existing test suite — not just coverage percentage |
| [Unit Test Generator](./Unit%20Test%20Generator.md) | Writes comprehensive unit tests covering happy paths, edge cases, and error handling |

## How to use

1. Open the prompt file you need.
2. Copy the full contents into your AI tool (Claude, ChatGPT, etc.).
3. Fill in the `{placeholders}` with your actual code, context, or requirements.
4. Leave optional placeholders blank if you don't have that info — most prompts handle missing context gracefully and will state their assumptions rather than guess silently.
