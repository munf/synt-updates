# Changelog

Dates are UTC unless noted. Only changes visible in the public terminal or data notes are listed here.

## 2026-10-23

- This public changelog opened, with notes on how to read an audit score and on what the BNB recorder measures.

## 2026-10-22

- Terminal: very small prices are written with subscript zeros (for example $0.0₅2921) instead of long strings of zeros.
- Terminal: the price chart no longer folds decimals, and its unit label now matches the data.
- Token page: market cap, liquidity and volume in USD now use the live SOL rate. Before this fix a fallback rate was used, which overstated USD values.
- Token page: an agent confidence of 0% is no longer shown, and a slot metric that is no longer measured was removed.
- The leaderboard route is closed until it can show real data. It redirects to Trenches.
- Copy and page titles cleaned up across the terminal.

## 2026-10-21

- Discovery opened on the public preview: short data notes written from synt's own recordings of new Solana and BNB pairs. Each note shows where every number comes from.
- Every note has its own link (`/p/<id>`) with a share card.

## 2026-10-20

- Service moved to a new server. Solana recording has a gap from 2026-10-19 03:00 to 2026-10-19 20:42 UTC.
- BNB recorder (four.meme and Flap) running continuously, with a backfill so its history has no gap.

## 2026-10-09

- Terminal preview opened to the public: Trenches (new pairs with score and top risks), token pages with live price and chart, and the engine footer.

## 2026-10-04

- Public audit score table measured on 12,783 labelled pairs. This is the table shown next to every score. See [docs/reading-a-score.md](docs/reading-a-score.md).
