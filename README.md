# OPOR Go-Live 2 Command Centre Intelligence System

A healthcare analytics and AI prototype built to support Nova Scotia Health's OPOR rollout.
Analyzes incident data, predicts ticket priority, clusters issue patterns, and generates
AI-powered triage recommendations for Go-Live 2 command-centre teams.

---

## Problem
Large healthcare EHR go-lives generate a surge of support incidents (access, devices,
documentation, medication orders). Without a triage system, teams lose time triaging
manually and critical issues can be missed.

## Solution
A three-layer decision-support prototype:
- **Layer A — Data Processing**: Understand Go-Live 1-style incident patterns
- **Layer B — Machine Learning**: Classify priority + cluster recurring issue types
- **Layer C — Generative AI**: Auto-generate a triage recommendation per ticket

## Tech Stack
Python · Pandas · Scikit-learn · Matplotlib/Seaborn · KMeans Clustering · Jupyter

## Dataset Note
This project uses a realistic synthetic proxy dataset modeled on go-live support patterns.
Not real NSH or IWK operational data.

## Project Context
- IWK Health OPOR Go-Live 1: December 6, 2025
- NSH Central Zone Go-Live 2: May 9, 2026

## Repo Structure
data/ · notebooks/ · reports/figures/ · notes/
