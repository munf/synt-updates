# Changelog

Dates are UTC unless noted. Only changes visible in the public terminal or data notes are listed here.

Each dated release has a version number (v0.N.0) and a matching git tag. Versions before v0.9.0 were numbered on 2026-11-09, after the fact.

## 2026-10-29 (v0.8.0)

- Trenches: the WHY and TOP RISK lines now fit properly when the side panel is open, and card styling was tidied.

## 2026-10-28 (v0.7.0)

- BNB pairs in Trenches and on the token page now show a 0 to 100 score in the same format as Solana, with percentages shown to one decimal.
- Pages that had no live data behind them are now closed instead of showing empty placeholders.

## 2026-10-23 (v0.6.0)

- This public changelog opened, with notes on how to read an audit score and on what the BNB recorder measures.

## 2026-10-22 (v0.5.0)

- Terminal: very small prices are written with subscript zeros (for example $0.0₅2921) instead of long strings of zeros.
- Terminal: the price chart no longer folds decimals, and its unit label now matches the data.
- Token page: market cap, liquidity and volume in USD now use the live SOL rate. Before this fix a fallback rate was used, which overstated USD values.
- Token page: an agent confidence of 0% is no longer shown, and a slot metric that is no longer measured was removed.
- The leaderboard route is closed until it can show real data. It redirects to Trenches.
- Copy and page titles cleaned up across the terminal.

## 2026-10-21 (v0.4.0)

- Discovery opened on the public preview: short data notes written from synt's own recordings of new Solana and BNB pairs. Each note shows where every number comes from.
- Every note has its own link (`/p/<id>`) with a share card.

## 2026-10-20 (v0.3.0)

- Service moved to a new server. Solana recording has a gap from 2026-10-19 03:00 to 2026-10-19 20:42 UTC.
- BNB recorder (four.meme and Flap) running continuously, with a backfill so its history has no gap.

## 2026-10-09 (v0.2.0)

- Terminal preview opened to the public: Trenches (new pairs with score and top risks), token pages with live price and chart, and the engine footer.

## 2026-10-04 (v0.1.0)

- Public audit score table measured on 12,783 labelled pairs. This is the table shown next to every score. See [docs/reading-a-score.md](docs/reading-a-score.md).
