This repository trains an XGBoost classifier on the UCI Credit Card dataset (`UCI_Credit_Card.csv`) and provides interpretability using SHAP. It includes global feature importance, local explanations for misclassified samples, and a simple subgroup bias check (age groups).


## Files
- `credit_risk_shap_analysis.py` — main Python script to train model and produce SHAP plots.
- `UCI_Credit_Card.csv` — dataset (place in repo root).
- `README.md` — this file.
- `REPORT_bias_analysis.md` — 500-word bias analysis.
- `MISCLASSIFIED_EXPLANATIONS.md` — textual explanation for selected misclassified samples.


## Dependencies
Use a virtual environment. Example with `venv`:


```bash
python -m venv venv
source venv/bin/activate # on Windows: venv\Scripts\activate
pip install -r requirements.txt