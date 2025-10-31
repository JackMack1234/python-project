# python-project (data analysis)

This small project contains a CLI helper to analyze CSV files, produce a
Markdown report and save plots.

Quick start

1. Create and activate your virtual environment (you already did):

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

2. Run the analysis tool on the sample CSV:

```powershell
.\.venv\Scripts\python .\src\data_analysis.py data\sample.csv --report reports/sample_report.md --plots reports/plots
```

Files
- `src/data_analysis.py` - CLI tool
- `data/sample.csv` - small sample dataset
- `requirements.txt` - packages

If you want, I can add more features (interactive notebook, more plots, automated tests).
