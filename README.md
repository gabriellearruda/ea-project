# Harmonograph

**Compare cost-effectiveness analyses (CEAs) from different authors under shared assumptions.**

Each study embeds its own premises implicitly and non-standardized, preventing reuse, direct comparison, and coherent portfolio-level views. Harmonograph solves this.

## What it does

- Upload or link cost-effectiveness spreadsheets
- Automatic parsing to apply a semantic interoperability layer between CEAs
- Side-by-side study comparison with uncertainty modeling (Squiggle)
- Sensitivity analysis: swap premises and see how portfolio distribution/ranking changes
- Private portfolios (saved comparisons) and public (publishable)
- Export to Cross-Cause Cost Effectiveness Model and Moral Parliament
- 100% open source

## Target users

- Grantmakers
- Incubators (e.g. Ambitious Impact)
- Effective giving organizations

## Status

🟡 **Visual prototype** — illustrative data, no real calculation. See [live demo](https://gabriellearruda.github.io/ea-project/).

## Stack (planned)

- Frontend: Next.js + TypeScript
- Backend: FastAPI (Python) for parsing
- Database: Supabase (Postgres + Auth)
- Uncertainty modeling: [Squiggle](https://www.squiggle-language.com/)

## License

MIT
