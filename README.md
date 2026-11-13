# Podcast Teaser Editing Skill

Most podcast trailers are cut by gut feel. This one isn't — it's built from the exact ratios (trailer length, statement counts, pattern-interrupt placement) a creator extracted from hundreds of hours of his own top-performing videos, then validated live against *The Diary of a CEO*'s real trailer.

This isn't a vague "make it punchy" guide. It's a checklist with actual ratios — trailer length vs. episode length, bold-statement counts, question caps, pattern-interrupt placement, music BPM, the three closing-line types — not a style opinion.

**Works with any AI assistant** — ChatGPT, Claude, Grok, Kimi, Gemini, or no AI at all (it's a plain checklist). See [Quick Start](#quick-start) below.

## What's in this repo

| File | What it's for |
| --- | --- |
| [`UNIVERSAL-PROMPT.md`](./UNIVERSAL-PROMPT.md) | Paste this into any LLM's custom instructions / system prompt / project knowledge to make it apply the protocol automatically |
| [`docs/RULES-AND-MATH.md`](./docs/RULES-AND-MATH.md) | The full research notes — every rule, every number, where each one is validated against a real trailer, and how the rules interact with each other |
| [`docs/CHECKLIST.md`](./docs/CHECKLIST.md) | A short, printable pre-production + editing + export checklist for everyday use |
| [`claude-skill/SKILL.md`](./claude-skill/SKILL.md) | The same protocol packaged as a Claude Skill (adds YAML frontmatter Claude's skill system expects) |

## Quick Start

**Using an AI assistant (recommended):**
1. Open `UNIVERSAL-PROMPT.md`, copy its whole content.
2. Paste it into:
   - **ChatGPT** → a Custom GPT's instructions, or a Project's "Project instructions"
   - **Claude** → a Project's custom instructions, or drop `claude-skill/SKILL.md` in as a Skill
   - **Grok / Kimi / Gemini / others** → their system-prompt or custom-instructions field
3. Give it your podcast transcript (or raw footage notes) and ask for a teaser cut-list.

**Without an AI assistant:**
Just work through `docs/CHECKLIST.md` by hand while you edit.

## Where this comes from

This protocol is built from public, freely-taught material from **Editing Explained**'s "Podcast Trailer Editing" masterclass — reorganized, cross-referenced, and documented as a reusable checklist. It is **not** official material from that channel, and this repo isn't affiliated with or endorsed by them. If you find this useful, go support the original creator: [youtube.com/@editingxplained](https://www.youtube.com/@editingxplained).

## Contributing

Found a podcast/channel where these numbers hold or break? Open an issue or PR with your findings — the goal is to keep refining the ratios with real data, the same way the original research did.

## License

MIT — see [`LICENSE`](./LICENSE). Use it, remix it, ship it.
