# Clarity Principle

Make business logic visible through traceability and narration.

## What is this?

The Clarity Principle is a design principle for enterprise and SaaS applications. It is not a product, not a library, not a framework. It is an approach to making business logic legible to everyone who interacts with a system, not just the engineers who wrote it.

The principle is built on two layers. First, **business traceability**: record which business rules fired, under what conditions, and what the outcome was. This is valuable on its own. Second, **narration**: an LLM reads the traceability data and transforms it into a human-readable explanation. The LLM does not make decisions. It narrates what the deterministic system already decided. Narration is optional. It amplifies traceability but is not required.

This is not a new concept. Rules engines like Drools have provided traceability for years. What is new is that LLMs make narration cheap and accessible, so the full value of business traceability becomes practical for everyday enterprise applications.

## The two layers

**Business traceability** — Record which rules fired, under what conditions, and what the outcome was. This is separate from technical observability. It answers: "Which business rule applied and why?"

**Narration** — An LLM reads the traceability data and generates a human-readable explanation. Non-technical stakeholders can read it without translation. This layer is optional.

## Who it's for

- Product managers who spend too much time translating between business intent and system behavior
- CTOs and engineering leaders looking for built-in explainability
- Senior engineers working on business-critical systems
- Business stakeholders who need to understand what the system decided and why

## The website

Visit [clarityprinciple.ai](https://farabiinnovations.github.io/clarity-principle/) for a full walkthrough of the concept, concrete examples, and the adoption path.

## Repo structure

```
index.html    — the single-page website (HTML + CSS, no frameworks)
CLAUDE.md     — project context and instructions for AI-assisted development
README.md     — this file
```

## Coming soon

AI agents for **Claude Code** and **Cursor** that read your codebase, identify where business decisions are being made, and suggest exactly where a Clarity layer should be added. Follow this repo for updates.

## Contributing

Contributions are welcome. If you have ideas for new domain examples, improvements to the site, or thoughts on the principle itself, open an issue or submit a pull request.

## Author

**Rabea Abdelwahab** — [LinkedIn](https://www.linkedin.com/in/rabeaabdelwahab/) · [GitHub](https://github.com/farabiinnovations)

## License

MIT
