# ProspectDB — Integrated Prospect Grading


**Author:** John Liakakos
**Contact:** [email@example.com] | https://www.linkedin.com/in/john-liakakos


## Objective


ProspectDB is a reproducible pipeline that aggregates junior/college statistics, computes age-adjusted percentiles, applies a scouting rubric, and produces ranked prospect lists and player cards to support draft and development decisions.


## What this answers
- Which prospects are outperforming peers when adjusted for age and league?
- Which prospects show positive development trends worth investing in?
- How to prioritize limited scouting resources across a draft class.


## Key outputs
- `reports/top50_prospects.pdf` — executive Top-50 prospects list (sample).
- `dashboard/` — Streamlit app (demo) to explore prospect cards.
- `data/` — cleaned and processed datasets (CSV).
- `notebooks/` — reproducible analysis notebooks.


## Methods & approach
- Age-adjustment and percentile ranking by position.
- Simple league-translation factors (configurable).
- Combined scoring: 60% statistical signal, 40% scouting-weighted rubric (traits).
