# ✍️ Anastasia's Writing Room

*A free, private space to organize, sharpen, and finish your story — without ever handing the writing over to AI.*

**[→ Open the Writing Room](https://ms-amapostol.github.io/aawritingroom/)**

---

## What this is

Anastasia's Writing Room is a single-page writing studio for novels, memoirs, poetry collections, plays, screenplays, and more. It helps you shape your story, keep track of your characters and world, and get honest editorial feedback — all while you do 100% of the actual writing.

It runs entirely in your browser, using **your own Anthropic API key**. There's no account, no server, and no one but you ever sees your pages.

## The one rule this app follows

> **It suggests. It questions. It never writes your story for you.**

Every AI feature in this room — spine suggestions, character depth prompts, editorial notes, continuity checks — is designed to spark your own thinking, not replace it. If you ever see it try to hand you finished prose, that's a bug, not a feature.

## What's inside

- **Outline** — Shape your story on a proven structural spine (adapted to your form: a narrative arc for novels and memoirs, a collection arc for poetry, a linked-piece arc for vignettes), with an armature test, an elevator pitch, and room to write scenes out of order and fold them in later.
- **Characters** — Rich cards organized by Main / Supporting / Ancillary, with Want/Need/Flaw/Arc/Voice prompts, a voice-strength score read from your actual prose, portraits, and AI-composed image prompts for tools like Nano Banana or Midjourney.
- **World** — The same care applied to your setting: mention counts (what's actually load-bearing on the page vs. unused), a cohesion score, and a gap-finder that turns thin spots into questions you answer in your own words.
- **Writing** — Draft chapters or scenes with light industry-standard formatting scaffolds for screenplays and stage plays, an AI editor scoped to one chapter or your whole stitched draft, "Ask the editor" for direct questions about your pages, and a rotating tip from real writers to keep you moving.
- **Review** — Every continuity flag, editorial note, and armature-drift result lands in one place, so nothing gets lost in the scroll. Mark items resolved, backlog them, or let them go — your call, always.
- **Export** — Pull any part of your project (or all of it) to Word, Markdown, or print-ready PDF.

## Getting started

1. **Get an Anthropic API key** at [console.anthropic.com](https://console.anthropic.com). Usage is billed to your own account — this app has no markup and no middleman.
2. **Open the Writing Room** and paste your key into Settings.
3. **Start a project**, name it, and write one sentence on what it's really about. That's it — everything else builds from there.

## Your writing, your machine, your responsibility

This app stores everything **only in your browser** (`localStorage`) — nothing is ever sent anywhere except directly to Anthropic's API when you use an AI feature. That means:

- No one, including the creator of this tool, can see your writing.
- Clearing your browser data, switching browsers, or switching devices will **not** carry your projects over.
- **Back up regularly.** Settings → *Back up all projects* downloads everything as one `.json` file. *Restore from backup* brings it back, on this device or any other.

There is currently no cloud sync. If that changes, this README will say so.

## Running it yourself

This is one self-contained HTML file — no build step, no dependencies to install.

- **Easiest:** use the hosted link above.
- **Fully offline:** download `index.html` from this repo and open it in any modern browser. It works with no internet connection except for the AI calls themselves.
- **Host your own copy:** fork this repo, enable GitHub Pages (Settings → Pages → Deploy from branch → `main` / root), and you'll have your own URL in about a minute.

## Method & credit

Structural guidance draws on the **Story Spine** (Kenn Adams, popularized by Pixar) as taught through Brian McDonald's *Invisible Ink*, and on standard poetry-collection and stage/screen formatting conventions — all expressed here in original wording. This project isn't affiliated with or endorsed by any of them; go read their work, it's excellent.

## Support this project

This tool is free and always will be. If it helped you finish something you're proud of, you're welcome to [buy me a coffee](https://buymeacoffee.com/aabuildsfreeapps) — it goes straight toward more hours building features like this. Never required, always appreciated.

## Feedback

I'd genuinely love to hear from you — what worked, what didn't, what you wish it did. Find me on [LinkedIn](https://www.linkedin.com/in/aapostol1211/) and say hello.

## License & disclaimer

This project is shared publicly so people can use it for free — but **all rights are reserved**. There is no open-source license attached. That means:

- You're welcome to **use the hosted app or your own downloaded copy**, exactly as it is, at no cost.
- You do **not** have permission to modify, repackage, redistribute, rehost under a different name, or sell this code or any derivative of it.
- If you'd like to adapt it, build on it, or use it somewhere else — just ask. Reach out on [LinkedIn](https://www.linkedin.com/in/aapostol1211/); I'm happy to talk about it.

The tool itself is provided as-is, for the love of writing. No guarantees about outcomes, and not responsible for what you create with it — your words are entirely your own.

© Anastasia Apostol 2026. All rights reserved. 

---

*Happy writing.* 🖋️
