# Autoresearch: Engineering an Auditable Agentic Research Loop for Event-Driven Earnings Prediction

**Trinity Research Notes · Valuation** · Version **v1** · November 2026  
**License:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) (paper)  
**Series:** Trinity Global Capital LLC — Quantitative Research & Agentic AI Systems Group  
**Disclaimer:** Proprietary methods discussion and public research findings. This is not investment advice and does not establish a deployable trading edge.

## Paper

[2026-11-06_autoresearch-auditable-agentic-research-loop-earnings-prediction_v1.pdf](./2026-11-06_autoresearch-auditable-agentic-research-loop-earnings-prediction_v1.pdf)

## Abstract

Quantitative strategy discovery faces a fundamental tension between research velocity and statistical validity: manual hypothesis testing is slow and inconsistent, whereas unconstrained automated search rapidly overfits historical noise. This paper presents Autoresearch, an agent-assisted quantitative research architecture that couples bounded hyperparameter and feature search with automated critique, strict walk-forward validation, and mandatory human promotion gates. We examine the application of this framework to event-driven corporate earnings prediction—specifically, forecasting the direction and magnitude of post-announcement equity price movements across industry cohorts.

Evaluating an out-of-sample validation dataset of N = 1,197 corporate earnings events across eight industry cohorts, we find an aggregate directional accuracy of 50.7% (95% Wilson confidence interval: 47.9%–53.5%), a ROC AUC of 0.503, a mean absolute magnitude error (MAE) of 8.60 percentage points, and an out-of-sample move R-squared of −5.614. Rather than establishing a deployable trading edge, the empirical audit exposes three actionable failure mechanisms: (i) severe magnitude overprediction in the top confidence quintile (20.1% predicted vs. 6.0% realized move) and top signal-strength quintile (24.2 percentage points MAE; Spearman ρ = −0.367), (ii) performance dilution from a generic global fallback model (48.4% accuracy across 50.7% of events) relative to specialized industry models such as Software (54.5% accuracy, n = 391), and (iii) statistically significant underperformance in Biotechnology (41.1% accuracy, n = 124, unadjusted p = 0.038). We demonstrate how an auditable validation harness transforms weak aggregate forecasts into targeted engineering interventions—prioritizing post-hoc probability calibration, robust quantile loss functions, immutable point-in-time prediction ledgers, and multiple-testing controls before scaling agent autonomy or committing capital.

## Canonical record

Public archive: [https://zenodo.org/records/24022841](https://zenodo.org/records/24022841)  
Version DOI: [https://doi.org/10.5281/zenodo.24022841](https://doi.org/10.5281/zenodo.24022841)

This repository does not link SSRN, arXiv, or Substack. Those records are not part of this release.

## How to cite

Trinity Global Capital LLC, Quantitative Research & Agentic AI Systems Group. (2026). *Autoresearch: Engineering an Auditable Agentic Research Loop for Event-Driven Earnings Prediction* (Trinity Research Notes · Valuation, v1). [https://doi.org/10.5281/zenodo.24022841](https://doi.org/10.5281/zenodo.24022841)

## Reproduction note

This repository publishes the public PDF, the CC BY 4.0 license, and citation metadata only. No source code and no dataset accompany the paper. The results are not independently reproducible from this repository.
