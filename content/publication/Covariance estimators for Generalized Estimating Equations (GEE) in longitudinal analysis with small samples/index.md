---
title: 'Covariance estimators for Generalized Estimating Equations (GEE) in longitudinal analysis with small samples'
authors:
  - Ming Wang
  - Lan Kong
  - Zheng Li
  - Lijun Zhang
date: '2016-09-13T00:00:00Z'
doi: '10.1002/sim.7131'

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
url_pdf: https://www.ncbi.nlm.nih.gov/pmc/articles/pmid/26585756/
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

Generalized estimating equations (GEE) is a general statistical method to fit marginal models for longitudinal data in biomedical studies. The variance-covariance matrix of the regression parameter coefficients is usually estimated by a robust "sandwich" variance estimator, which does not perform satisfactorily when the sample size is small. To reduce the downward bias and improve the efficiency, several modified variance estimators have been proposed for bias-correction or efficiency improvement. In this paper, we provide a comprehensive review on recent developments of modified variance estimators and compare their small-sample performance theoretically and numerically through simulation and real data examples. In particular, Wald tests and t-tests based on different variance estimators are used for hypothesis testing, and the guideline on appropriate sample sizes for each estimator is provided for preserving type I error in general cases based on numerical results. Moreover, we develop a user-friendly R package "geesmv" incorporating all of these variance estimators for public usage in practice.

**Keywords:** Type I error; generalized estimating equations; hypothesis testing; longitudinal data; small sample size; variance estimator.
