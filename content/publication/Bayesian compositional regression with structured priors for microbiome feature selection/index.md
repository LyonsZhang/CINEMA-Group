---
title: 'Bayesian compositional regression with structured priors for microbiome feature selection'
authors:
  - Liangliang Zhang
  - Yushu Shi
  - Kim-Anh Do
  - Robert R. Jenq
  - Christine B. Peterson
date: '2020-09-13T00:00:00Z'
doi: 'https://doi.org/10.1111/biom.13335'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-11-16T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'BMC Bioinformatics'
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
url_pdf: https://www.ncbi.nlm.nih.gov/pmc/articles/pmid/32686846/
url_code: ''
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

The microbiome plays a critical role in human health and disease, and there is a strong scientific interest in linking specific features of the microbiome to clinical outcomes. There are key aspects of microbiome data, however, that limit the applicability of standard variable selection methods. In particular, the observed data are compositional, as the counts within each sample have a fixed-sum constraint. In addition, microbiome features, typically quantified as operational taxonomic units, often reflect microorganisms that are similar in function, and may therefore have a similar influence on the response variable. To address the challenges posed by these aspects of the data structure, we propose a variable selection technique with the following novel features: a generalized transformation and z-prior to handle the compositional constraint, and an Ising prior that encourages the joint selection of microbiome features that are closely related in terms of their genetic sequence similarity. We demonstrate that our proposed method outperforms existing penalized approaches for microbiome variable selection in both simulation and the analysis of real data exploring the relationship of the gut microbiome to body mass index.



