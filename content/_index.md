---
title: ""
date: 2025-10-13
type: landing

design:
  spacing: "5rem"

sections:
  # Profile & Bio
  - block: resume-biography-3
    content:
      username: admin
      text: ""
      button:
        text: Download CV
        url: uploads/resume.pdf

  # Research Focus - clean & concise
  - block: markdown
    content:
      title: 'Research Focus'
      text: |-
        Computational biology • Single-cell omics • Drug target discovery

        Building reproducible bioinformatics workflows and open-source tools.
    design:
      columns: '1'

  # Technical Skills
  - block: features
    content:
      title: Technical Stack
      items:
        - name: R & Bioconductor
          icon: r-project
          icon_pack: fab
          description: Seurat, DESeq2, ComplexHeatmap
        - name: Python
          icon: python
          icon_pack: fab
          description: Data analysis & scripting
        - name: Bioinformatics
          icon: dna
          icon_pack: fas
          description: Multi-omics analysis
        - name: Data Visualization
          icon: chart-bar
          icon_pack: fas
          description: ggplot2, custom palettes
        - name: Version Control
          icon: git-alt
          icon_pack: fab
          description: Git, GitHub workflows
        - name: Web Development
          icon: code
          icon_pack: fas
          description: Hugo, Markdown
    design:
      columns: '3'

  # Open Source Projects
  - block: collection
    id: projects
    content:
      title: Open Source Projects
      subtitle: 'R packages & bioinformatics tools'
      filters:
        folders:
          - project
    design:
      view: showcase
      columns: '2'
      flip_alt_rows: true

  # Publications - single section
  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publication
    design:
      view: citation
---
