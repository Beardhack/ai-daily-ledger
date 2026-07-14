# AI Daily Ledger

A recurring, source-linked briefing on recent AI discussion across X/Twitter.

The latest edition is published at:

<https://beardhack.github.io/ai-daily-ledger/>

Past editions are listed at:

<https://beardhack.github.io/ai-daily-ledger/editions/>

## Publishing a new edition

1. Save the reviewed HTML as `site/editions/YYYY-MM-DD/index.html`.
2. Save its Markdown source as `sources/YYYY-MM-DD.md`.
3. Copy the reviewed HTML to `site/index.html` so the root URL always shows the latest edition.
4. Add the edition to `site/editions/index.html`.
5. Commit and push to `main`.

The GitHub Actions workflow deploys the contents of `site/` to GitHub Pages on every push to `main`. Native X post embeds require client-side access to X's widget script.
