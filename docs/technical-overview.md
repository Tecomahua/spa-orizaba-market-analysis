# Technical overview

## Verified technologies

| Purpose | Technology |
| --- | --- |
| Data processing | Python, pandas, NumPy |
| Charts | Matplotlib |

These dependencies are listed in the related public analysis repository’s requirements.txt. The repository contains a Python pipeline for ENIGH, DENUE, and ITER inputs and chart generation.

## Analysis flow

1. Load public source files supplied by the analyst.
2. Normalize and validate selected fields needed by the analysis.
3. Transform and aggregate income/spending, demographic, and establishment information.
4. Calculate descriptive indicators and prepare charts for interpretation.

The public showcase contains no runnable analysis code or source datasets. It communicates the methodology and limits without duplicating the separate implementation repository.

## Interpretation limits

- ENIGH context is state/national, not municipal demand for a SPA.
- DENUE records are listings, not observed sales or proof of demand.
- Census counts describe population, not the addressable customer base.
- The public analysis repository explicitly does not reproduce the report’s suggested-zone score as a reproducible neighborhood-level calculation.
- No predictive model, machine learning, ROI estimate, or geospatial map is represented in this showcase.

## Privacy and reproducibility

Raw CSV files, derived data tables, coordinates, the full report, and the original Git history are not included. Reproducing the analysis requires downloading source data from the relevant official sources and following the methodology in the separate repository.
