# Week 3: Marks report pipeline (WB-03, Part A)

Read a student-marks CSV, write a summary JSON, and log bad rows instead of crashing.
Part B (the team pull request) lives in your team's repo; put its links in your submission Notes.

## Checklist
- [ ] Reads `roll_no, name, subject, marks` from a CSV
- [ ] `summary.json`: per student total, average and grade; per subject average, highest and lowest
- [ ] Bad rows are skipped and written to `errors.txt` with a reason
- [ ] Uses `with` blocks, the `csv` and `json` modules, and at least one custom exception
- [ ] Built inside a venv; `requirements.txt` committed
- [ ] Run steps below are correct

## How to run

```bash
python -m venv .venv
# Windows: .venv\Scripts\activate    macOS/Linux: source .venv/bin/activate
pip install -r requirements.txt
python report.py marks.csv
```
