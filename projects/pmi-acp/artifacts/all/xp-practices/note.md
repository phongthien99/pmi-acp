# XP (Extreme Programming) Practices

## One-line Summary
XP Practices are the specific engineering and planning activities used by XP teams to deliver high-quality software iteratively — used throughout an XP project to enforce collaboration, quality, and adaptability.

## Objectives
- **What is it?** A set of practices (planning games, coding disciplines, testing techniques) that define how an XP team operates day-to-day.
- **What is it used for?** Structuring work, ensuring quality, sharing knowledge, and keeping the team aligned with customer needs.
- **When should you use it?** Throughout an XP project — from release planning at the start to refactoring and continuous integration during development.

## Key Points
- **Iteration = Sprint** in XP (1–4 weeks); **Release = multiple iterations** pushed to customers.
- **Test-Driven Development (TDD)** — write the test *before* the code; code is written to pass pre-defined tests.
- **Pair Programming** — two developers code together in real time; one types, one reviews — catching errors instantly.
- **Collective Code Ownership** — anyone can change any code; reduces bus-factor risk and increases visibility.
- **Continuous Integration** — code is merged and tested constantly to surface conflicts before they compound.

## Mental Model
Think of XP practices as a set of safety nets stacked on top of each other: TDD catches bad logic before it's written, pair programming catches errors as they're typed, continuous integration catches integration breaks immediately, and refactoring keeps the whole codebase clean over time.

## Connections
| XP Term | Scrum Equivalent |
|---|---|
| Iteration | Sprint |
| Release Planning | Product Roadmap / Release Planning |
| Iteration Planning | Sprint Planning |
| Customer Tests | Acceptance Criteria |
| Collective Code Ownership | Shared team responsibility |

- XP is **more engineering-practice focused** than Scrum, which is more **process/ceremony focused**.
- Both follow the same iterative cadence and value self-organizing teams.

## Real-world Example
A team building an invoicing system uses TDD: the customer defines the test — "create an invoice, send it, receive credit card payment." The team writes that test first, then codes the feature until it passes. Meanwhile, two developers use pair programming, and every feature is pushed to a test environment for the customer to validate before the full release goes out.

## Pitfalls
- Confusing **release planning** (multi-iteration, what goes to users) with **iteration planning** (single cycle, what the team builds next).
- Thinking TDD means testing after coding — it's the **opposite**: test first, code second.
- Assuming **collective code ownership** means no standards — coding standards are still required so code looks consistent regardless of who wrote it.
- Confusing **refactoring** with rewriting — refactoring removes junk/redundancy without changing functionality.
- Thinking **sustainable pace** means no overtime ever — short bursts are okay; *repeatable* long hours are not.

## Exam Tips
- **Iteration vs Sprint** — XP says iteration, Scrum says sprint. Same concept, different word. Don't be tricked by terminology.
- **TDD** — commonly tested as "when are tests written?" Answer: **before** the code.
- **Collective Code Ownership** — if a question asks about reducing risk when a developer leaves → this is the answer.
- **Pair Programming** — produces real-time code review; increases quality and knowledge sharing.
- **Metaphor** — used in XP to create shared understanding between technical and non-technical stakeholders. Trap: don't confuse with user stories (Scrum) or personas.
- **Small Releases** — released to **test environments** first, not directly to production.
- **Simple Design** — XP favors simplest possible design that works; complex designs should be replaced with simpler ones.

## Self-check
- What is the XP equivalent of a sprint, and how long is it?
- What makes Test-Driven Development different from traditional testing?
- What is collective code ownership, and why does it reduce project risk?
- What is the purpose of a metaphor in XP?
- What is the difference between release planning and iteration planning?
- What does refactoring mean, and when is it done?
- Why does XP emphasize sustainable pace?
