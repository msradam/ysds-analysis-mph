# YSDS Analysis - Team Hotfix - MIT Policy Hackathon 2025

Data analysis supporting the Youth Safety & Design Standard federal policy proposal.

## Structure

- `notebooks/` - Analysis pipeline (run in order 01-05)
  - `01_teen_behavioral_analysis` - Kaggle dataset (67,921 sessions)
  - `02_policy_tracker_analysis` - Integrity Institute bills (146 bills)
  - `03_data_completion` - Missing data filling
  - `04_mechanism_classification` - AI-assisted bill coding
  - `05_synthesis` - Final analysis + figures

- `data/` - Source datasets and classification results
- `output/figures/` - Publication-ready visualizations
- `policy_dashboard.py` - Interactive legislative explorer (Streamlit)

## Key Outputs

- **Finding:** 146 state bills, 3% passage rate, design-based survived
- **Dashboard:** https://ysds-policy-dashboard.streamlit.app
- **Figures:** Combined landscape chart in `output/figures/`

## Citation

Teen behavioral data: [Kaggle - Teenage Online Behavior](https://www.kaggle.com/datasets/datasetinventor/teenage-online-behavior-and-cybersecurity-risks)  
Legislative data: [Integrity Institute Tech Policy Tracker](https://www.integrityinstitute.org/legislative-tracker)

MIT Policy Hackathon 2025 - Team Hotfix
