# BuiltForm Marketplace

The marketplace for BuiltForm plugins, for Claude Code and Codex.

## Install

### Claude Code

```
/plugin marketplace add github:builtform/marketplace
/plugin install launchpad@builtform        # free, public
/plugin install growth-toolkit@builtform   # paid, private (see the access section below)
```

Restart Claude Code after install.

### Codex

```bash
codex plugin marketplace add builtform/marketplace
codex plugin add launchpad@builtform
```

Start a new Codex session, then run `$launchpad:lp help`. LaunchPad is the plugin available on Codex today; Growth Toolkit is Claude Code only. Details, the verified command list, and the differences from Claude Code are in [LaunchPad: How It Works, Codex](https://github.com/builtform/launchpad/blob/main/docs/guides/HOW_IT_WORKS.md#codex).

To update on Codex, run `codex plugin marketplace upgrade builtform`, then `codex plugin add launchpad@builtform` again.

## Plugins

### LaunchPad

Autonomous AI coding harness for spec-driven software delivery. Greenfield and brownfield. Free, open source. Full docs and source at [github.com/builtform/launchpad](https://github.com/builtform/launchpad).

The listing follows the `stable` branch of the LaunchPad repository. That branch moves forward to each release only after the release checks pass, so both hosts always install the latest verified release.

### Growth Toolkit (paid)

Strategic growth workflows for your company, wired in as Claude Code agents and skills. One slash command per workflow produces a structured artifact you can immediately act on, edit, or hand to your team. No methodology lookups, no framework reading, no manual translation — the toolkit operationalizes the work.

**What it covers — every stage of growing a company:**

- **Customer discovery** — interview guides that surface real problems without leading the conversation
- **Positioning** — what makes you different, who you're for, what category you compete in
- **Sales pitch** — first-call storyboard that opens with the buyer's world, not your product
- **Offer construction** — the offer you sell, its components, naming, scarcity, and guarantees
- **Lead generation** — strategy for getting in front of buyers across warm outreach, content, cold outreach, and paid ads
- **Pricing & monetization** — the money model: attraction offers, upsells, downsells, continuity
- **Web copy** — page-by-page copy for landing, pricing, about, feature, and product pages
- **Content** — editorial calendars, content briefs, distillation strategy
- **Funnel design** — top/mid/bottom funnel mapping, leakage diagnostics, customer journey
- **Acquisition** — channel testing, SEO, paid ads, attribution architecture
- **Retention** — keeping the customers you win
- **Launch** — sequencing the moment you go live

Everything is already wired as agents and skills. You don't read about the methodology — you run the command, the artifact gets written to your repo, and you move on.

**Access:** This is a paid plugin. The source lives in the private `builtform/growth-toolkit` repository.

To request access, open an issue using the [Request Growth Toolkit access](https://github.com/builtform/marketplace/issues/new?template=request-access.yml) template. Once approved, your GitHub account is granted read access to the private repo, and the install command above succeeds. Until then, the install fails on the GitHub auth check — no plugin files leave the private repo.

A `sales@` email channel is coming soon and will be listed here when it's live.

## What this repo is

This repo holds the marketplace listing only — no plugin code lives here. Each plugin's source, issues, and documentation live in its own repo:

- LaunchPad → [github.com/builtform/launchpad](https://github.com/builtform/launchpad) (public)
- Growth Toolkit → `builtform/growth-toolkit` (private, access on request)

## License

MIT — see [LICENSE](LICENSE).
