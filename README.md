# PA — Personal Accountant

A chat-driven personal finance, goals, and life-planning tracker. Talk to
Claude about income, expenses, bills, goals, and plans — Claude logs them
into the structured files here and uses them to give grounded advice,
track progress, and run periodic reviews.

See `CLAUDE.md` for how Claude operates this repo.

## Structure

```
finances/
  income.csv          # date, source, amount, currency, notes
  expenses.csv        # date, category, amount, currency, notes
  subscriptions.md     # recurring bills/subscriptions
  budget.md            # monthly targets by category
  net-worth.md         # periodic net worth snapshots
goals/
  goals.md              # active goals
  reviews/YYYY-MM.md    # monthly reviews
documents/
  records.md            # index of important documents (metadata only)
planning/
  future-planning.md    # career/life planning notes
```

## Currencies

Primary: QAR (salary). Secondary: PKR. Others noted per-entry as needed.
Amounts are always stored in their original currency — no silent conversion.
