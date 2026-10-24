# UGI Leaderboard Explorer

A single-page explorer for the [UGI Leaderboard](https://huggingface.co/spaces/DontPlanToEnd/UGI-Leaderboard) by DontPlanToEnd.

**Live site:** https://9pm1.github.io/ugi-leaderboard-explorer/

- Loads `ugi-leaderboard-data.csv` straight from the Hugging Face Space on every visit, so it never goes stale.
- A sortable table with column sets, a column picker and CSV export.
- Filters by model type, reasoning, author, architecture, ideology, size, release date and score, plus custom conditions on any column.
- A scatter plot of any two metrics.
- A detail panel per model with ranks and a plain-language explanation of every column.
- Publisher logos from Hugging Face avatars.

Everything is in `index.html`, with no build step and no dependencies. All data and benchmark credit goes to the UGI Leaderboard.
