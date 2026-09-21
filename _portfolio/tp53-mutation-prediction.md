---
title: "TP53 mutation prediction from cancer cell line expression"
excerpt: "Predicting TP53 mutation status from CCLE transcriptomics with tree-based models, at ~81% F1-score."
collection: portfolio
---

A group project for the AI Lab course, predicting the mutation status of TP53 — one of the most frequently mutated tumour suppressor genes — directly from gene expression data.

I built the pipeline for preprocessing and batch correction of the Cancer Cell Line Encyclopedia (CCLE) datasets, which is the step that makes the downstream signal usable at all. We then predicted TP53 mutation status with Random Forest and XGBoost, reaching roughly 81% F1-score, with hyperparameters optimised using Optuna.

The project work was later used by Prof. Salwa Lin in a research grant proposal.

**Methods:** Random Forest, XGBoost, Optuna, batch correction, CCLE.
