<p align="center">
  <img src="assets/banner.svg" alt="Project Banner" width="720"/>
</p>

# Project: Power BI & Excel Data Validation Suite

**Tagline:** _Automated validation of Power BI & Excel financial reports using Python for reproducible BI QA._

## Project Summary
This repository provides an automated, reproducible validation pipeline to reconcile financial metrics between Excel and Power BI. It includes:

- `COMPREHENSIVE_VALIDATION.py` — Python validation script (pandas, numpy, openpyxl)
- `Captures+S8+6+nov+25 (2).xlsx` — Source Excel data (rankings, P&L)
- `GSO6116 (4).pbix` — Power BI report file (visuals & product/channel breakdowns)
- `FINAL_VALIDATION_REPORT.md` — Human-readable validation report
- `analysis_summary.txt` — Extracted data summaries

---

## Quickstart 
1. Create and activate a Python environment.
2. Install dependencies:

```bash
python -m pip install -r requirements.txt
```

3. Place the Excel file (`Captures+S8+6+nov+25 (2).xlsx`) in the repository root.
4. Run the validator:

```bash
python COMPREHENSIVE_VALIDATION.py
```

5. Check `FINAL_VALIDATION_REPORT.md` for the results.

---

## Why this project is relevant for Data Science roles
- Demonstrates data QA and reproducibility using Python and pandas
- Shows ability to interpret financial metrics (sales, margins, market share)
- Example of cross-tool verification (Excel ↔ Power BI) important for BI validation

---

## License & Contact
Add a LICENSE file (e.g., MIT) if you want to publish. Add your contact info (name & email) here for recruiter visibility.
