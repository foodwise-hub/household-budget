# Ledger — household budget

A shared household budget tracker. One static page, no server:

- **Sign in with Google** (Google Identity Services, token flow)
- **Google Sheets is the database** — every change is written to a shared
  Sheet with the signed-in user's own OAuth token, so both partners see
  the same data
- Monthly spending vs. a budget or a "typical month" baseline, category
  budgets, recurring payments with autopay posting, one-time budget
  raises, savings goals, net-worth snapshots, Chase CSV import with
  categorization rules

Live at <https://foodwise-hub.github.io/household-budget/>.

Access requires a Google account that has edit access to the shared
budget spreadsheet.
