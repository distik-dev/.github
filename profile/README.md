<p align="center">
  <img src="./assets/hero.png" alt="Distik — AI code review that reads the PR, not the diff" width="100%" />
</p>

<h1 align="center">Distik</h1>

<p align="center">
  <strong>AI code review that reads the PR, not the diff.</strong>
</p>

<p align="center">
  <a href="https://distik.dev">distik.dev</a> &nbsp;·&nbsp;
  <a href="https://docs.distik.dev">Docs</a> &nbsp;·&nbsp;
  <a href="https://app.distik.dev">Open the app</a> &nbsp;·&nbsp;
  <a href="https://distik.dev/pricing">Pricing</a>
</p>

---

Reviewing a 2,000-line AI-generated pull request by skimming a flat diff misses intent, risk, and the dependency order between changes. Distik replaces that workflow with a structured review surface: it ingests every PR, decomposes it into chapters labeled with intent and risk, and lets you approve per chapter.

Distik never trains on your code. Source diffs are sent to Anthropic for chapter generation under contractual no-training terms; structured chapter analysis is cached, raw diffs are not.

## What's inside

| | |
|---|---|
| **Chapter decomposition** | Every PR is broken into 4–8 dependency-ordered chapters, each with a one-line intent and a risk label. |
| **Per-chapter approval** | Approve, request changes, or comment chapter-by-chapter. Comments post under your VCS identity, not as a bot. |
| **Keyboard-driven review** | Move between chapters, mark approved, and jump to the next risk without leaving the keyboard. |
| **Multi-VCS** | GitHub, GitLab, and Bitbucket — Cloud, Enterprise, and Self-Hosted. Web-only review surface at v1. |

## Built for teams shipping AI-generated PRs

Distik runs as a web application at [app.distik.dev](https://app.distik.dev) for engineering teams reviewing pull requests authored by Cursor, Claude Code, Copilot, and similar tools. 14-day no-card trial, then $30/seat/month or $240/seat/year.

## Find us

- **Website** — [distik.dev](https://distik.dev)
- **Documentation** — [docs.distik.dev](https://docs.distik.dev)
- **App** — [app.distik.dev](https://app.distik.dev)
- **Pricing** — [distik.dev/pricing](https://distik.dev/pricing)
- **X / Twitter** — [@distikdev](https://x.com/distikdev)

<p align="center">
  <sub>Distik <code>/ˈdɪs.tɪk/</code> — code review for AI-generated PRs.</sub>
</p>
