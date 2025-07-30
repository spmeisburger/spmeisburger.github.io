---
title: "Meisburger and Ando, Acta D 2024"
date: 2024-04-12
categories:
  - first author
  - Diffuse Scattering
beamlines:
  - F1
figure: /images/insulin-maps-noaxes.png

ref-title: "Scaling and merging macromolecular diffuse scattering with _mdx2_"
ref-authors: "Meisburger SP, Ando N"
ref-journal: "Acta Cryst D"
ref-volume: "80(5)"
ref-pages: "299-313"
ref-year: 2024
ref-doi: 10.1107/S2059798324002705
ref-pmcid: PMC11066883
ref-pmid:  38606664
---

Diffuse scattering is a promising method to gain additional insight into protein dynamics from macromolecular crystallography experiments. Bragg intensities yield the average electron density, while the diffuse scattering can be processed to obtain a three-dimensional reciprocal-space map that is further analyzed to determine correlated motion. To make diffuse scattering techniques more accessible, software for data processing called mdx2 has been created that is both convenient to use and simple to extend and modify. mdx2 is written in Python, and it interfaces with DIALS to implement self-contained data-reduction workflows. Data are stored in NeXus format for software interchange and convenient visualization. mdx2 can be run on the command line or imported as a package, for instance to encapsulate a complete workflow in a Jupyter notebook for reproducible computing and education. Here, mdx2 version 1.0 is described, a new release incorporating state-of-the-art techniques for data reduction. The implementation of a complete multi-crystal scaling and merging workflow is described, and the methods are tested using a high-redundancy data set from cubic insulin. It is shown that redundancy can be leveraged during scaling to correct systematic errors and obtain accurate and reproducible measurements of weak diffuse signals.