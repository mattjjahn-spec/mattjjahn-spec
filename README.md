## Matt Jahn

**Senior Product Leader and hands-on AI builder.** I scaled edge-AI to ~18,000 Starbucks locations, owned a greenfield rules engine that helped position TUNE for acquisition, and now build agentic AI systems that compress the SDLC from months to days. I ship the products, not just the specs.

Portfolio: [mjportfolio.dev](https://mjportfolio.dev) · [LinkedIn](https://www.linkedin.com/in/matt-jahn-94626494/) · matt.j.jahn@gmail.com

### What's pinned

These are small, focused tools abstracted from a larger private job-search pipeline I built solo. Each has a README that tells the product-thinking story behind it.

- **job-match-scorer** — Explainable, local resume-vs-JD matching with no LLM call. TF-IDF cosine plus a keyword demand-coverage blend and a legal/EEO boilerplate stripper. Why local-first and auditable beats a black-box model for high-volume triage.
- **job-funnel-analytics** — SQL analytics and an A/B experiment readout over a synthetic job-search funnel. CTEs, window functions, percentiles, plus a PM experiment memo (hypothesis, guardrails, decision).
- **resume-mcp** — A Model Context Protocol server exposing structured resume tools to AI agents over stdio, with local semantic search over my work history. Connects to Claude Desktop and Cursor.
- **workday-finder** — Locates any company's Workday careers tenant by distinguishing HTTP 422 from 404 from 200 across datacenters, then sweeping career-site slugs. A small detective story in HTTP status codes.
- **markdown-resume-pdf** — Markdown to ATS-friendly PDF resume renderer via headless Chromium (real fonts, real text layer, page-break control).

### How I build

Claude Code, MCP servers, and multi-agent review loops (parallel reviewers, a coordinator that triages). The repos above are the proof, not just the claim.
