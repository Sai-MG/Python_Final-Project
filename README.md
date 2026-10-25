# FinTrack — Personal Finance & Expense Tracker

## Requirements
- Python 3.10 or newer

## Run on Windows (VS Code)
Open this folder in VS Code, then choose Terminal > New Terminal. Run each command separately:

```powershell
py -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
python app.py
```

Then open http://127.0.0.1:5000 in your browser and create an account.

The SQLite database (`finance.db`) is created automatically when the app starts.
Keep `app.py`, `requirements.txt`, `templates`, and `static` together in this folder.
Press Ctrl+C in the terminal to stop the server.
