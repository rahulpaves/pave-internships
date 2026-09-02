# Pave Internships

A single-page website for Pave's student internship programmes in Dubai and Abu Dhabi.

Nine programmes, each with its own page: day-by-day plan, fees, and what students leave with.

- **Live site:** https://rahulpaves.github.io/pave-internships/
- **Source:** `index.html` — one self-contained file, no build step, no dependencies.

## Editing

Everything lives in `index.html`:

- **Programme content** — the `PROGRAMMES` array in the `<script>` block. Each entry has the title, field, colour, fees, day-by-day schedule and outcomes.
- **Booking link** — set `const CONTACT` to a `mailto:`, `https://` or `wa.me` link to turn the "Contact the Pave team" box into a live "Ask about dates" button.
- **Colours** — the `--c-*` tokens at the top of the `<style>` block, one per discipline.

Commit to `main` and GitHub Pages redeploys within a minute or two.
