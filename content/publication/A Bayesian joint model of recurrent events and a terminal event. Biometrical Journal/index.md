---
title: 'A Bayesian joint model of recurrent events and a terminal event. Biometrical Journal'
authors:
  - Zheng Li
  - Vernon M. Chinchilli
  - Ming Wang
date: '2018-09-13T00:00:00Z'
doi: 'https://doi.org/10.1002/bimj.201700326'

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
url_pdf: https://onlinelibrary.wiley.com/doi/epdf/10.1002/bimj.201700326
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

Recurrent events could be stopped by a terminal event, which commonly occurs in biomedical and clinical studies. In this situation, dependent censoring is encountered because of potential dependence between these two event processes, leading to invalid inference if analyzing recurrent events alone. The joint frailty model is one of the widely used approaches to jointly model these two processes by sharing the same frailty term. One important assumption is that recurrent and terminal event processes are conditionally independent given the subject-level frailty; however, this could be violated when the dependency may also depend on time-varying covariates across recurrences. Furthermore, marginal correlation between two event processes based on traditional frailty modeling has no closed form solution for estimation with vague interpretation. In order to fill these gaps, we propose a novel joint frailty-copula approach to model recurrent events and a terminal event with relaxed assumptions. Metropolis-Hastings within the Gibbs Sampler algorithm is used for parameter estimation. Extensive simulation studies are conducted to evaluate the efficiency, robustness, and predictive performance of our proposal. The simulation results show that compared with the joint frailty model, the bias and mean squared error of the proposal is smaller when the conditional independence assumption is violated. Finally, we apply our method into a real example extracted from the MarketScan database to study the association between recurrent strokes and mortality.

**Keywords:** Bayesian inference; Markov chain Monte Carlo; joint frailty modeling; recurrent events; survival copula.
