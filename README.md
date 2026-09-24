# Hey, I'm Luka

Python developer from Maribor, Slovenia. I build automation, web scrapers and websites for small businesses. Second-year IT student at FERI Maribor, freelancing alongside my studies.

Open for freelance work. I work in English and Slovenian.

## What I build

**Automation and scraping**: Python and Playwright pipelines that replace repetitive manual work
**Websites for small businesses**: fast, multilingual, hand-coded, no page builders and no bloat
**Internal tools and dashboards**: Flask and FastAPI apps that do one job well

## Selected work

**[napotnica](https://github.com/PuhmeisterLuka/napotnica)**
Collects public Slovenian student job listings, scores them against your profile with an LLM, then drafts a tailored CV and cover note. Playwright scraper, SQLite, Flask UI, 66 tests running on CI, and a small design system I built for my own projects. The commit history is the clearest picture of how I work.

**[loadout](https://github.com/PuhmeisterLuka/loadout)**
Self-hosted training dashboard that merges Hevy lifting data and GPX/FIT run data into one training-load view. 125 passing tests, encrypted API credentials, one-command demo mode. `DECISIONS.md` covers the tradeoffs the code doesn't explain on its own, `LATER.md` is the honest backlog of what I left out and why.

**[polymarket-ai](https://github.com/PuhmeisterLuka/polymarket-ai)**
I took over a broken five-agent LLM trading pipeline and got it working. Market prices were never parsed at all, so the whole system had been running on meaningless 50/50 defaults. One SQLAlchemy session was shared across a thread pool. A float rounding bug was silently rejecting every maximum-size bet, which meant it threw away its own best opportunities. Once it actually ran, I tested five strategies against real Polymarket data and all five lost money. `REPORT.md` documents that instead of dressing up a fake positive.

**[Folio-pdf](https://github.com/PuhmeisterLuka/Folio-pdf)**
Desktop PDF toolkit. Merge, split, compress, rotate, batch process a whole folder, export pages as images. Everything runs locally, so your files never leave your machine. Python and CustomTkinter.

## Stack

Python (Flask, FastAPI, Playwright, PyMuPDF, SQLAlchemy), JavaScript, HTML and CSS.

## Contact

Email: luka@puhmeister.dev
LinkedIn: [in/luka-puhmeister](https://linkedin.com/in/luka-puhmeister)

Ask me about web scraping, PDF automation, or what five failed strategies taught me about measuring things properly. Away from the keyboard I train five days a week, which is why half my repos are about workout data.
