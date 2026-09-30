# Portfolio Review

Get your product design portfolio reviewed the way a design hiring manager would actually review it — then fix what matters before you apply.

This repo contains the same review framework in two forms:

| | What it is | Works with |
|---|---|---|
| [`prompt/`](prompt/portfolio-review-prompt.md) | A copy-paste prompt | Claude, ChatGPT, Gemini or any AI assistant |
| [`skill/`](skill/portfolio-review/SKILL.md) | A Claude skill | Claude (claude.ai, desktop, Claude Code) |

## What you get

The review walks through six steps:

1. **First impression** — a simulated 1–3 minute screen: is it clear who you are, are the right projects on top, would a hiring manager click in?
2. **Case study deep dive** — each project scored 1–5 on seven dimensions, with evidence quoted from your portfolio:
   - Problem framing
   - Personal role & contribution
   - Decisions & trade-offs
   - User understanding & evidence
   - Craft
   - Outcome & impact
   - Storytelling
3. **Red flags** — common portfolio mistakes that quietly cost interviews.
4. **Level calibration** — what level your portfolio currently reads as (Junior / Mid / Senior / Staff) versus the level you're targeting.
5. **Action list** — prioritized fixes (must fix / should fix / nice to have), with concrete rewrites where useful.
6. **Self-check checklist** — a one-minute checklist marked ✅ / ⚠️ / ❌ for your portfolio, which you can re-run yourself after every round of edits.

Each case study also comes with the 2–3 questions an interviewer is most likely to ask you about it.

## How to use

### Option 1: Prompt (any AI assistant)

1. Open [`prompt/portfolio-review-prompt.md`](prompt/portfolio-review-prompt.md).
2. Copy everything under **Prompt**.
3. Paste it into your AI assistant and attach your portfolio.
4. Answer the few context questions it asks (target level, industry, background).

### Option 2: Claude skill

1. Download the [`skill/portfolio-review`](skill/portfolio-review) folder (or `portfolio-review.zip` from [Releases](../../releases), if available).
2. Zip the folder so that `portfolio-review/SKILL.md` is inside the zip.
3. In Claude, go to **Settings → Capabilities → Skills** and upload the zip.
4. Start a chat, attach your portfolio and ask something like *"Review my portfolio."*

Skills availability and setup steps may change over time — check [Claude's help center](https://support.claude.com) if the steps above don't match what you see.

## Tips for better results

- **Upload a PDF or screenshots** rather than a link. Many AI tools can't open password-protected sites, Notion pages behind a login, or pages that load content dynamically.
- **Tell it your target role.** A portfolio that's strong for a Junior role can read as thin for a Senior one; the feedback changes a lot.
- **Review one case study at a time** if your portfolio is long. You'll get deeper, more specific feedback.
- **Use the likely interview questions** to rehearse — ask the AI to run a mock interview on them.

## A note on privacy

Portfolios often include work covered by NDAs or confidential company information. Before uploading your portfolio to any AI tool, make sure you're comfortable with that tool's data policy and that you have the right to share the content.

## Contributing

Suggestions and improvements are welcome — open an issue or a pull request. Ideas that would be especially useful:

- Variations for specific fields (UX research, AI product design, design systems, UX writing)
- Translations of the prompt into other languages
- Examples of before/after case study rewrites

## License

[MIT](LICENSE)
