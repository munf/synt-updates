# Reading an audit score

A synt audit score runs from 0 to 100. On its own a number like 87 says little, so the terminal always shows it with its **base rate**: what happened to earlier pairs that received the same score.

## Both sides of the base rate

For each score the table shows two outcomes, measured after the audit was published:

- **Collapsed**: the share of pairs at that score whose price collapsed.
- **Rose 3×**: the share of pairs at that score whose price reached three times its level at publication.

Public table, measured 2026-10-04 on 12,783 labelled pairs:

| Audit score | Collapsed | Rose 3× |
|---|---|---|
| 91 | 9.5% | 2.6% |
| 87 | 13.2% | 2.4% |
| 80 | 20.5% | 2.0% |
| 75 | 24.9% | 1.8% |
| 67 | 32.7% | 3.3% |
| 50 | 49.7% | 5.2% |

## What this means

- Higher scores collapse less often. At score 91, 9.5% collapsed. At score 50, 49.7% did.
- A high score still carries risk. Roughly one in ten score 91 pairs collapsed.
- The score separates pairs that collapse. It does not pick winners: the rose 3× column does not rise with the score.

## What a score is not

- Not a buy or sell signal.
- Not a judgement about the people behind a token.
- Not final. The table is re-measured as more pairs are labelled. The table above stays fixed until its next public update.
