# Personal Expense Tracker (Python)

A lightweight command-line app to log expenses, save them to CSV, and track a monthly budget.

## Features
- Add expenses with date, category, amount, description
- View all saved expenses (prints in a tidy table-like format)
- Set & track monthly budget (warns if over budget)
- Save/load from **`expenses.csv`**

## Quick Start
```bash
# 1) Ensure Python 3.x is installed
python --version

# 2) Run the app
python expense_tracker.py
```

The first time you save, it creates/updates `expenses.csv` with headers:
```
Date, Category, Amount, Description
```

> **Tip:** `Amount` is stored as a formatted string like `$12.50`, which the program parses when summing totals.

## Files
- `expense_tracker.py` — the CLI app
- `expenses.csv` — your expenses data file
- `Expense_Tracker_Writeup.pdf` — 1–2 page project write-up
- `screenshots/` — PNGs for main menu, CSV preview, and budget output

## Example Workflow
1. Run `python expense_tracker.py`
2. Choose **Add expense** to enter some items
3. Choose **Track budget** to set a monthly budget and see remaining balance
4. Choose **Save expenses** to persist data to `expenses.csv`

## License
MIT — see [LICENSE](LICENSE).
