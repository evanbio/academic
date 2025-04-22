---
# Display name
title: Yibin Zhou # 姓名

# Name pronunciation (optional)
name_pronunciation: "Yee-bin Joe" # 发音

# Full name (for SEO) # 全名，用于搜索引擎优化，帮助网站被搜索到
first_name: Yibin
last_name: Zhou

# Status emoji
status:
  icon: 🧬 # tentative

# Is this the primary user of the site?
superuser: true # 是否主要用户，通常设为 true

# Highlight the author in author lists? (true/false)
highlight_name: true # 在作者列表中高亮显示名字

# Role/position/tagline
role: Graduate

# Organizations/Affiliations to display in Biography blox
organizations:
  - name: Fudan University
    url: https://www.fudan.edu.cn/

# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: at-symbol # 邮箱图标
    url: 'yibinzhou00@gmail.com'
    label: E-mail Me # 标签
#  - icon: brands/x 
#    url: https://twitter.com/GetResearchDev
#  - icon: brands/instagram
#    url: https://www.instagram.com/
  - icon: brands/github
    url: https://github.com/evanbio # GitHub 链接
  - icon: brands/linkedin
    url: https://www.linkedin.com/in/yibin-zhou  # LinkedIn 链接
  - icon: academicons/google-scholar
    url: https://scholar.google.com/citations?user=oDo9Be8AAAAJ # 你的 Google Scholar 链接
  - icon: academicons/orcid
    url: https://orcid.org/0009-0009-4600-8175

interests:
  - Machine Learning # 机器学习，符合你的 AI 研究方向
  - Data Analysis # 数据分析
  - Bioinformatics # 生物信息学，新增，结合网站领域的特点

education:
  - area: Master of Science in Clinical Pharmacy
    institution: Fudan University
    date_start: 2022-09-01
    date_end: ""
    summary: |
      GPA: 3.3 / 4.0

      Relevant Courses:
      - Clinical Pharmacology
      - Molecular Pharmacology
      - Pharmacogenomics
      - Medical Molecular Cell Biology

  - area: Bachelor of Engineering in Pharmaceutical Engineering
    institution: China Pharmaceutical University
    date_start: 2018-09-01
    date_end: 2022-06-30
    summary: |
      GPA: 3.5 / 5.0

      Relevant Courses:
      - Biochemistry
      - Medicinal Chemistry
      - Organic Chemistry
      - Pharmaceutical Analysis

work:
  - position: Creator & Developer
    company_name: "bioPalette: Color System for Bioinformatics Visualization"
    company_url: ''
    date_start: 2025-04-01
    date_end: ''
    summary: |
      - Designed and implemented an R package providing semantic, modular color palettes tailored for biological data visualization.
      - Integrated with ggplot2, ComplexHeatmap, ggVennDiagram, and other tools for multi-omics research.
      - Built reusable APIs, JSON-based scheme structure, and logging-enabled palette compilation workflows.

  - position: Founder & Maintainer
    company_name: "scFlowKit: Single-Cell RNA-seq Workflow Toolkit"
    company_url: ''
    date_start: 2025-04-01
    date_end: ''
    summary: |
      - Developed a reproducible scRNA-seq workflow including data import, QC, integration, and visualization.
      - Created general-purpose functions such as `read_sce()` supporting multiple formats (.h5, .loom, .mtx, .h5ad).
      - Focused on user-friendly design and Seurat / SingleCellExperiment compatibility.

  - position: Graduate Researcher & Co-author
    company_name: Clinical Research Collaboration
    company_url: ''
    date_start: 2023-10-01
    date_end: 2024-01-31
    summary: |
      - Co-authored a clinical study on pediatric post-traumatic endophthalmitis (DOI: 10.3390/antibiotics14010020).
      - Performed logistic regression and multivariate modeling on clinical and microbiological data.
      - Contributed to manuscript writing, figure preparation, and revision.

  - position: Writer & Designer
    company_name: "Cell by Cell: Personal Blog"
    company_url: https://blog.evanzhou.org
    date_start: 2025-01-01
    date_end: ''
    summary: |
      - Published bilingual articles on bioinformatics, academic writing, and scientific workflows.
      - Built on Hugo + NotionNext, deployed via Vercel with custom theming.

  - position: Learner & Documenter
    company_name: Google
    company_url: https://www.coursera.org
    date_start: 2025-03-01
    date_end: 2025-04-30
    summary: |
      - Completed Git training through "Happy Git with R" and Coursera.
      - Documented practical Git workflows for academic and data science projects.
      - Practiced GitHub Pages deployment, branch management, and collaborative commits.

  - position: Graduate Researcher
    company_name: Molecular Biology Lab
    company_url: ''
    date_start: 2022-09-01
    date_end: 2025-01-31
    summary: |
      - Investigated the role of 4EBP1-mTOR signaling in cSCC proliferation and angiogenesis.
      - Conducted RNA-seq, protein validation, and enrichment analyses to identify therapeutic targets.
      - Focused on multi-omics integration and translational application in cutaneous oncology.


# Skills
# Add your own SVG icons to `assets/media/icons/`
skills:
  - name: Programming
    items:
      - name: R
        description: Statistical computing and graphics
        percent: 90
        icon: r-project
      - name: Python
        description: Data analysis, scripting, visualization
        percent: 80
        icon: python
      - name: Bash
        description: Shell scripting and workflow automation
        percent: 60
        icon: terminal

  - name: Bioinformatics Tools
    items:
      - name: DESeq2 / Bioconductor
        description: Differential expression and enrichment analysis
        percent: 85
        icon: dna
      - name: Seurat
        description: Single-cell RNA-seq analysis
        percent: 80
        icon: cell
      - name: GSEA / BLAST
        description: Functional enrichment and sequence alignment
        percent: 70
        icon: database

  - name: Data Analysis
    items:
      - name: Survival Analysis
        description: Cox regression, Kaplan-Meier, hazard models
        percent: 80
        icon: heartbeat
      - name: GWAS
        description: Summary-statistics, association testing
        percent: 70
        icon: chart-bar
      - name: Visualization (ggplot2, ComplexHeatmap)
        description: Publication-quality bio plots
        percent: 90
        icon: palette

  - name: Tools & Platforms
    items:
      - name: Git & GitHub
        description: Version control & collaborative workflows
        percent: 85
        icon: github
      - name: Linux / Ubuntu
        description: Bioinformatics environment, shell tools
        percent: 75
        icon: linux
      - name: RStudio / LaTeX
        description: IDEs and document authoring
        percent: 90
        icon: file-code
      - name: Hugo & Netlify
        description: Static site generation & deployment
        percent: 80
        icon: globe

  - name: Domain Knowledge
    items:
      - name: Clinical Pharmacy
        description: Pharmacokinetics, pharmacogenomics
        percent: 85
        icon: capsule
      - name: Drug Development
        description: Translational research & target discovery
        percent: 70
        icon: flask

  - name: Interests & Expansion
    items:
      - name: AI in Drug Discovery
        description: Exploring TensorFlow & biomedical AI
        percent: 60
        icon: brain
      - name: Machine Learning
        description: Actively learning ML for omics data
        percent: 50
        icon: gears

languages:
  - name: English
    percent: 85
    description: TOEFL in preparation, strong reading & writing, improving listening & speaking
  - name: Chinese
    percent: 100
    description: Native speaker
  - name: Japanese
    percent: 15
    description: JLPT N1 scheduled, basic vocabulary & grammar


# Awards.
#   Add/remove as many awards below as you like.
#   Only `title`, `awarder`, and `date` are required.
#   Begin multi-line `summary` with YAML's `|` or `|2-` multi-line prefix and indent 2 spaces below.
awards:
  - title: Python Data Structures
    awarder: University of Michigan
    date: '2025-04-20'
    icon: coursera
    summary: |
      Completed with a perfect score. Covered data types, lists, dictionaries, and file handling in Python.

  - title: Programming for Everybody (Getting Started with Python)
    awarder: University of Michigan
    date: '2025-04-20'
    icon: coursera
    summary: |
      Introduced Python programming fundamentals including variables, conditionals, loops, and functions. Grade: 100%.

  - title: R Programming
    awarder: Johns Hopkins University
    date: '2025-04-16'
    icon: coursera
    summary: |
      Completed with 100% score. Covered R syntax, control structures, functions, and data visualization for statistical computing.

  - title: Introduction to Git and GitHub
    awarder: Google
    date: '2025-04-09'
    icon: coursera
    summary: |
      Gained hands-on experience in Git version control, GitHub repositories, and basic collaboration workflows. Grade: 100%.

---

## About Me

Pharmacy professional with a strong background in drug target discovery and biomarkers, currently focusing on bioinformatics and Python programming. Skilled in applying computational approaches to biomedical research, with a keen interest in collaborative projects. Seeking opportunities to contribute to innovative bioinformatics initiatives and open-source projects.
