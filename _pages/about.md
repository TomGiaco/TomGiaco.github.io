---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD student in Computer Science at [Bocconi University](https://www.unibocconi.it/) in Milan, where I work on artificial intelligence methods for understanding gene regulation. My PhD is funded by a scholarship from the Fondo Italiano per la Scienza (FIS).

Before starting the PhD, I completed an MSc in Artificial Intelligence and a BSc in Mathematical and Computing Sciences for Artificial Intelligence, both at Bocconi. Since 2024 I have been part of Prof. Francesca Buffa's group in the Department of Computing Sciences, and in 2026 I spent several months as a visiting researcher at the [Weatherall Institute of Molecular Medicine](https://www.imm.ox.ac.uk/), University of Oxford, working with Prof. Jim Hughes on epigenomics and gene regulation.

Research interests
======
My research sits at the intersection of **machine learning** and **computational biology**. I am interested in how modern deep learning architectures can be used to make sense of the regulatory logic of the genome, and in what those models can tell us about disease.

* **Gene Regulatory Network inference.** I develop methods that reconstruct the interactions between transcription factors and their target genes from single-cell data. Much of this work builds on and extends the [CellOracle](https://morris-lab.github.io/CellOracle.documentation/) framework with enrichment-based approaches, with the aim of producing networks that are not only accurate but biologically interpretable, so that they can prioritise targets for experimental validation.

* **Sequence-based models of gene regulation.** I work with pre-trained transformer models of the genome, such as Enformer and AlphaGenome, and study how their learned representations can be used to infer cell-type-specific regulatory relationships rather than only to predict assay tracks.

* **Multi-omics integration.** Regulation is written across several biological layers at once. I am interested in how RNA-seq, ATAC-seq and TF ChIP-seq can be combined, and in architectures that model both the individual modalities and their interactions without the simplifying assumptions that limit many current GRN methods.

* **Cancer biology.** Most of my work is motivated by cancer research, where identifying dysregulated gene programs can give insight into how a tumour progresses and where it might be vulnerable.

* **Tooling for computational biology.** I believe methods are only useful if other people can run them. I am the lead developer of [`pysigscore`](https://doi.org/10.64898/2026.08.04.742537), a Python package for gene signature scoring across bulk and single-cell transcriptomics.

Get in touch
======
I am always happy to discuss research, collaborations, or anything at the boundary between AI and genomics. The quickest way to reach me is by [email](mailto:tommaso.giacomello@phd.unibocconi.it), and my code is on [GitHub](https://github.com/TomGiaco).
