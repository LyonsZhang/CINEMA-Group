---
title: 'Joint modeling of recurrent events and a terminal event adjusted for zero inflation and a matched design'
authors:
  - Cong Xu
  - Vernon M Chinchilli
  - Ming Wang
date: '2018-09-13T00:00:00Z'
doi: '10.1002/sim.7682'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-11-16T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'Stat Med'
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
url_pdf: https://www.ncbi.nlm.nih.gov/pmc/articles/pmid/29682772/
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

In longitudinal studies, matched designs are often employed to control the potential confounding effects in the field of biomedical research and public health. Because of clinical interest, recurrent time-to-event data are captured during the follow-up. Meanwhile, the terminal event of death is always encountered, which should be taken into account for valid inference because of informative censoring. In some scenarios, a certain large portion of subjects may not have any recurrent events during the study period due to nonsusceptibility to events or censoring; thus, the zero-inflated nature of data should be considered in analysis. In this paper, a joint frailty model with recurrent events and death is proposed to adjust for zero inflation and matched designs. We incorporate 2 frailties to measure the dependency between subjects within a matched pair and that among recurrent events within each individual. By sharing the random effects, 2 event processes of recurrent events and death are dependent with each other. The maximum likelihood based approach is applied for parameter estimation, where the Monte Carlo expectation-maximization algorithm is adopted, and the corresponding R program is developed and available for public usage. In addition, alternative estimation methods such as Gaussian quadrature (PROC NLMIXED) and a Bayesian approach (PROC MCMC) are also considered for comparison to show our method's superiority. Extensive simulations are conducted, and a real data application on acute ischemic studies is provided in the end.

**Keywords:** Monte Carlo expectation-maximization algorithm; death; frailty models; joint modeling; recurrent events; zero inflation.
