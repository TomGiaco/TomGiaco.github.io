---
title: "pysigscore: gene signatures scoring across bulk and single-cell transcriptomics"
collection: publications
category: preprints
permalink: /publication/2026-08-09-pysigscore
excerpt: 'A Python framework for gene set scoring in bulk and single-cell RNA-seq, bringing together 18 scoring methods behind one interface, with built-in reliability analysis.'
date: 2026-08-09
venue: 'bioRxiv (under review)'
paperurl: 'https://doi.org/10.64898/2026.08.04.742537'
citation: 'Giacomello, T., Mazzara, S., Abbruzzese, G., Barberis, A., Tangherloni, A., &amp; Buffa, F. M. (2026). &quot;pysigscore: gene signatures scoring across bulk and single-cell transcriptomics.&quot; <i>bioRxiv</i>. doi:10.64898/2026.08.04.742537'
---

Gene signature scoring is a routine step in transcriptomics, but the choice of scoring method is rarely neutral: different methods can disagree substantially on the same data, and comparing them usually means stitching together several tools with incompatible interfaces.

`pysigscore` is a Python framework that brings 18 built-in scoring methods under a single API, together with a fully customisable scorer that lets users define and benchmark new scoring functions on equal footing. It works on both bulk and single-cell RNA-seq data.

Beyond computing scores, the package provides reliability analyses — p-value estimation and leave-one-out experiments — so that users can assess the significance of a score and understand how much individual genes contribute to it.

We validated `pysigscore` on the CCLE, TCGA and PBMC datasets, where it recovers the expected enrichment in liver, hypoxia, inflammatory and cell-cycle signatures. The package extends the functionality of the original R library [`sigscores`](https://github.com/alebarberis/sigscores) and is distributed on PyPI.
