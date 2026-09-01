# Stel

**Stel** (short for *Stock Evaluation Ledger*) is a single-page, offline-first
checklist for evaluating a stock before committing to it long-term.

Instead of just listing metrics, every item comes with a concrete
**good vs. bad example** — so you're not left guessing whether a P/E of 40
or an ROIC of 6% is actually a problem.

## How it works

- Work through 8 sections in order: **Valuation → Profitability → Growth →
  Financial Health → Efficiency & Moat → Management & Ownership →
  Dividends → Qualitative Context**
- Check off what the stock passes; Stel tracks a live score and a
  WEAK / MIXED / STRONG verdict as you go
- Progress saves per ticker in `localStorage` — evaluate multiple stocks
  without losing your place
- Export your evaluation as plain text, copy it to your clipboard, or
  print/save it as a PDF
- Ends with a gut-check: would you hold this through a 40% drawdown, based
  on fundamentals alone?

## Stack

Single HTML file. No build step, no backend, no dependencies — just open
`index.html` or host it on GitHub Pages.

## Disclaimer

Educational tool, not financial advice. Always do your own due diligence.
