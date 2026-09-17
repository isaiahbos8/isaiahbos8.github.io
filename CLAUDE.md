# isaiahbos8.github.io

Isaiah Bos's personal website, published via GitHub Pages. Its main job right
now is to work as an **internship/job-search portfolio** — it needs to make a
good first impression on someone deciding whether to interview him.

## Voice & tone

Write copy that is **warm, personal, and values-first** — not a résumé dump.
Lead with who Isaiah is before what he's accomplished. The through-line for
everything on the site is: **approachable, honest, curious, and passionate
about doing meaningful work.** When adding or revising content, ground claims
in specific real experience rather than generic buzzwords (e.g. "I've learned
people open up when they feel heard" tied to his peer educator role, not just
"I'm a good listener").

Finance/business credentials matter (this is a job-search tool), but they
should never crowd out the personal framing — his nonprofit and community work
(Guiding Light, peer education) belongs in the main narrative, not as an
afterthought below the finance résumé bullets.

## Design system — treat as locked in

The current look is the standing design. Don't propose a new color scheme,
font pairing, or layout style unless Isaiah explicitly asks for a redesign —
just extend the existing system for new content.

- **Palette**: warm cream background (`--bg:#fbf7f0`), terracotta/amber accent
  (`--accent:#e0713a`, `--accent-2:#e8a13f`), warm near-black text
  (`--text:#2a2521`). No red/black corporate-finance look.
- **Type**: `Fraunces` (serif) for headings, `Inter` for body text.
- **Motifs**: organic "blob" shape behind the headshot, soft card panels with
  a warm border, a timeline component for experience, a marquee for skill
  pills, scroll-reveal animations via `IntersectionObserver`.

## Structure

Single `index.html` file with inline `<style>` and `<script>` — no build
step, no framework, no separate CSS/JS files. Keep it that way unless the
site grows enough that Isaiah asks to split it up.

Images live in `assets/` (e.g. `assets/isaiah-headshot.jpg`).

## Sourcing personal info

It's fine to pull real content from Isaiah's resume or other personal files
(e.g. his OneDrive Resumes/Headshots folders) when it's clearly relevant to a
request to update the site — that's the expected way to keep the site
accurate. Don't invent accomplishments, dates, or affiliations that aren't
grounded in something real he's provided or that's findable in those files.

Only publish his phone number on the site if given permission (spam risk for a public page).
Email and LinkedIn are fine.

## Publishing

**Always ask before pushing changes live** — make edits locally, show/describe
them, and confirm before running `git push`. This repo has a
`.claude/skills/github-pages` skill (kept out of git via `.gitignore`) with
the full playbook for committing, publishing, and checking build/deploy
status in plain language — use it for git/GitHub work on this repo.
