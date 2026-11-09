# Changelog

Dates are UTC unless noted. Only changes visible in the public terminal or data notes are listed here.

Each dated release has a version number (v0.N.0) and a matching git tag. Versions before v0.9.0 were numbered on 2026-11-09, after the fact.

## 2026-11-08 (v0.9.0)

- Trenches on phones: token, score and market cap fit a 390 px screen with no sideways scrolling. On the narrowest screens the top risk and Buy button move to a second line.
- On phones the pair panel and sheet now include the score history (Scored N times so far) and the audit note.
- First visit shows the page layout right away and starts loading the feed earlier.
- Engine footer: Solana and BNB use the same words, the RPC error rate reads N of M calls failed this hour, and notes explain that counts run since the current engine version started.
- Token page: each key figure appears once above the fold. Solana liquidity is labelled Liquidity (SOL side), with a note on where the number comes from.
- Price chart on phones: the toolbar fits in two rows with no cut-off buttons. Graduated tokens mark the last price as end of curve data.
- Pages for tokens synt does not track link to DexScreener only when DexScreener knows the token, and a paid DexScreener listing is marked as not a safety signal.
- The early access notice is now a one-line pill that no longer covers the table, and Got it hides it for a day.

## 2026-11-07 (v0.11.0)

- The early access notice is now a small card in the corner instead of a window that covers the page.
- Faster first load: each page loads only when you open it, and the price chart loads only on token pages.
- BNB Trenches now uses the same table as Solana, with the same columns and row density. Columns that are always empty at a given stage were removed.
- Price chart: a small synt mark in the top left corner replaces the chart library watermark.
- Price change windows longer than a pair's age now show a blank, and tapping it shows the pair's age, instead of a misleading figure.
- BNB charts state the rate used for USD prices, for example 1 SPCXB = $134.49.
- BNB token pages: the first two minute buyer figures are labelled clearly and note that they are not a share of total supply.
- Trenches: the Scored only filter now appears on BNB only, since every Solana row is already scored. The 30 second refresh pauses while the tab is hidden.

## 2026-11-04 (v0.10.0)

- Accounts opened on the public preview: sign in with a Solana wallet, or an EVM wallet such as MetaMask, by signing a message. A Solana address and an EVM address are separate accounts.
- Your watchlist and settings now follow your account, so they stay the same on every device you sign in from.
- A notification bell for score and price alerts on watchlist tokens, system messages, and following other accounts with follower counts.
- Trading from the terminal, non-custodial: Buy and Sell panels on Solana and BNB Chain token pages, plus quick buy in Trenches. Your own wallet signs every transaction and synt never holds your funds.
- Every trade opens a review step first, then shows live transaction status. Positions and a portfolio view are kept per chain.
- Selling your whole balance of a Solana token closes its token account and returns the rent to your wallet. The review step shows the amount.
- Support: the ? button in the terminal opens a support form that can include the page you were on.
- Terms and Privacy pages now cover accounts and trading, and you can delete your account yourself from settings.

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
