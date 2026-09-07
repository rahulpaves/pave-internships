# Pave Internships

A single-page website for Pave's student internship programmes in Dubai, Abu Dhabi and online.

Twenty-five programmes, each with its own page: day-by-day plan, fees, and what students leave with.

- **Live site:** https://rahulpaves.github.io/pave-internships/
- **Source:** `index.html` — one self-contained file, no build step, no dependencies.

## Editing

Everything lives in `index.html`:

- **Programme content** — the `PROGRAMMES` array in the `<script>` block. Each entry has the title, field, colour, fees, day-by-day schedule and outcomes.
- **Booking contact** — the `CONTACT` object holds the email, phone and WhatsApp number used by the sidebar buttons and the footer.
- **Colours** — the `--c-*` tokens at the top of the `<style>` block, one per discipline.

Cards are listed A–Z by programme name, so a new entry can be added anywhere in the array.

Commit to `main` and GitHub Pages redeploys within a minute or two.
