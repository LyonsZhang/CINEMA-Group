---
title: 'A statistical framework for recovering pseudo-dynamic networks from static data'
authors:
  -  Chixiang Chen
  -  Biyi Shen
  -  Tianzhou Ma
  - Ming Wang
  -  Rongling Wu
date: '2022-09-13T00:00:00Z'
doi: '10.1093/bioinformatics/btac038'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-11-16T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'Biometrical Journal'
publication_short: ''

abstract: 

# Summary. An optional shortened abstract.
summary: 
tags:
  - Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://academic.oup.com/bioinformatics/article-lookup/doi/10.1093/bioinformatics/btac038
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

## Abstract

**Motivation:** The collection of temporal or perturbed data is often a prerequisite for reconstructing dynamic networks in most cases. However, these types of data are seldom available for genomic studies in medicine, thus significantly limiting the use of dynamic networks to characterize the biological principles underlying human health and diseases.

**Results:** We proposed a statistical framework to recover disease risk-associated pseudo-dynamic networks (DRDNet) from steady-state data. We incorporated a varying coefficient model with multiple ordinary differential equations to learn a series of networks. We analyzed the publicly available Genotype-Tissue Expression data to construct networks associated with hypertension risk, and biological findings showed that key genes constituting these networks had pivotal and biologically relevant roles associated with the vascular system. We also provided the selection consistency of the proposed learning procedure and evaluated its utility through extensive simulations.

**Availability and implementation:** DRDNet is implemented in the R language, and the source codes are available at https://github.com/chencxxy28/DRDnet/.

**Supplementary information:** Supplementary data are available at Bioinformatics online.
