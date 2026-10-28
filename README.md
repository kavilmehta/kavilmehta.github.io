# Kavil Mehta — personal academic website

Live at **https://kavilmehta.github.io**

A single static page (`index.html`). No build step, no database. Any change saved to the `main` branch goes live in 1–2 minutes.

## Common edits (all in `index.html`, editable right on GitHub with the pencil icon)

| To change | Find this in index.html |
| --- | --- |
| Add a paper | the `pub-data` block — copy one entry, edit it. `type` is `journal`, `proceedings` or `chapter`. Add `"doi"` (or `"url"` for arXiv) to make it clickable. `"badge": "pick"` or `"new"` adds a label. |
| Profile links (ResearchGate, Scholar, LinkedIn, ORCID) | `PROFILE_LINKS` near the bottom. Empty = button hidden. |
| Bio | the `01 / About` section |
| Positions | the `04 / Experience` section |
| Awards | the `05 / Recognition` section |
| Colours / fonts | the `THEME` block at the top of the `<style>` |
| Headshot | upload `assets/headshot.jpg`, then replace the `KM` avatar div with `<img src="assets/headshot.jpg" alt="Kavil Mehta">` |

## Run locally
Open `index.html` in any browser.
