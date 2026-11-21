# Inside a Software Factory

An interactive explainer that shows non-technical audiences what a **software factory** does:
an assembly line where people write requests, AI workers build the changes in sealed rooms,
automatic checks and a human reviewer approve them, and once a week the factory studies its
own mistakes and improves its instructions.

**Live page:** https://ghifiardi.github.io/software-factory-explainer/
**Bahasa Indonesia:** https://ghifiardi.github.io/software-factory-explainer/#id

The page is bilingual (English / Bahasa Indonesia). Switch with the toggle at the top; the choice
is remembered, and links ending in `#id` or `#en` open in that language.

## What you can do on the page

- Watch work orders move through eight stations: requests → triage → front gate → AI workshop →
  quality checks → safety inspector → human review → shipped.
- Send your own request (clear, vague, sensitive, or from a stranger) and see how the factory handles it.
- Click any station or work order for a plain-language explanation, plus how it maps to the real system.
- Watch the weekly self-improvement loop raise first-time success and cut people-time per change.

All numbers are illustrative. Visitors whose browser language is Indonesian see Bahasa Indonesia first. The page is a single self-contained HTML file with no build step
and no dependencies beyond Google Fonts. Open `index.html` in a browser to run it locally.

## Based on

The design follows a real starter kit: requests are GitHub issues, the AI builder is an AI coding agent
running in a disposable GitHub Actions machine, the checks are the project's own CI, and changes
ship as reviewed pull requests.
