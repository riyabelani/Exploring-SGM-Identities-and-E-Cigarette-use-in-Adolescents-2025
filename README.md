# Exploring SGM Identities and E-Cigarette Use in Adolescents (CHIS 2025)

This repository contains the Jupyter Notebook and supporting files for the GenAI final project analyzing e-cigarette use among sexual and gender minority (SGM) adolescents using the CHIS 2025 teen data.

Included in this folder:
- `FinalProject.ipynb` — analysis notebook with methods, results, and discussion.
- `teen_variable_mapping.json` — compact variable mapping used by the notebook.
- `figures/` — generated figures (PNG) comparing prevalence and age at first use by SGM status.
- `.gitignore` — excludes raw data files from the repository.

Important notes:
- Raw data files (e.g., `teen_cleaned.parquet`, `teen.sas7bdat`, `*.xpt`) are intentionally excluded and are not committed to this repo.
- To reproduce the analysis, place the raw data files in the Week_5 folder (or update the paths in the notebook), then run the setup/data-loading cells. The notebook uses `pandas`, `pyreadstat`, `statsmodels`, `seaborn`, and `matplotlib`.

Quick start (locally):
```
python -m pip install pandas pyreadstat statsmodels seaborn matplotlib
# Open the notebook in JupyterLab or Jupyter Notebook and run the cells
```

If you want me to include a `requirements.txt` or publish this as a GitHub Pages site, tell me and I can add it.

— Riya
