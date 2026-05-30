# Jakob Jarefjäll

Fifteen years in digital. Back to building from imagination, the way I used to with Lego.

Long-form writing at lifeaccordingtojay.com, with a hand-built Ghost theme and a small Node CLI handling the editorial workflow into Ghost.

Most of my work lives behind client confidentiality or on LinkedIn. What sits here is the smaller stuff: tools I built for myself, things noticed in passing, the occasional pipeline.

## Coffee Breaks

In-between nimble things. Built in twenty minutes, useful in twenty seconds.

- claude-code-uhoh-hook: drop-in notification hook for Claude Code https://gist.github.com/Jarefjaell/fc725b635c8284e94d10ac9a71e3a39d
- ghost-admin-cli: small Node CLI for moving content between disk and Ghost via the Admin API, with snapshots and dry-runs https://github.com/Jarefjaell/ghost-admin-cli
- life-according-to-jay-theme: the vanilla CSS and JS theme behind the blog, no frameworks https://github.com/Jarefjaell/life-according-to-jay-theme

## Projects

Bigger builds with budgets and milestones.

- **BurnerCookie** (Firefox extension, public alpha): per-domain control over tracker storage, with awareness of the persistence patterns common identity vendors rely on. Sits alongside, not in place of, third-party cookie blocking. Live at github.com/Jarefjaell/burnercookie
- **Mimer** (personal infrastructure, v2.5 in production): Python tool that ingests Claude.ai data exports into a secret-scrubbed local archive Claude can read via MCP. Cross-conversation recall across projects, SHA256-verified manifest, deep search, weekly snapshot backups, 110-test suite. Named after the Norse well of wisdom. The source Skald reads from. lifeaccordingtojay.com/the-well-i-had-to-dig-to-find-myself/
- **Heimdall** (operating model, in use): Notion-based layer for running multiple AI-assisted projects in parallel. Projects and Tasks databases, manifesto, weekly reviews. Wired to Claude Code agent teams via MCP. Surfaces silent project stalls and protects writing work from build noise.
- **Skald** (scheduled tool, early build): runs weekly against Mimer, surfaces 1 to 3 pitches per pass (identifying friction and cross project similarites through time), then does a research pulse-check on the survivors and writes the result to a Notion board and a local file. MVP runs by hand, headed for a scheduled Cowork task.
- **Bifrost** (research, on hold): session-based local AI workspace unifying LM Studio, SD Forge, and XTTS. Designed around the session as the persistent object holding text, images, audio, and service state. Master's-thesis scope
