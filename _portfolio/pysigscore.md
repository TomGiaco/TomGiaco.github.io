---
title: "pysigscore — gene signature scoring in Python"
excerpt: "A Python package bringing 18 gene signature scoring methods under a single API, for bulk and single-cell transcriptomics."
collection: portfolio
---

`pysigscore` is a Python framework for gene set scoring in bulk and single-cell RNA-seq data. It integrates 18 built-in scoring methods with a fully customisable scorer, so that new scoring functions can be defined and benchmarked against established ones on equal footing.

The package also provides reliability analyses — p-value estimation and leave-one-out experiments — to assess the significance of a score and the contribution of individual genes to it. It extends the functionality of the original R library [`sigscores`](https://github.com/alebarberis/sigscores) and is deployed as a PyPI package.

Validated on the CCLE, TCGA and PBMC datasets, where it recovers the expected enrichment in liver, hypoxia, inflammatory and cell-cycle signatures.

**Role:** lead developer. **Preprint:** [bioRxiv](https://doi.org/10.64898/2026.08.04.742537)
