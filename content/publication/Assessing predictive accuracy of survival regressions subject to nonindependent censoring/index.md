---
title: 'Assessing predictive accuracy of survival regressions subject to nonindependent censoring'
authors:
  -  Ming Wang
  -  Qi Long
  -  Chixiang Chen
  -  Lijun Zhang
date: '2020-09-13T00:00:00Z'
doi: '10.1002/sim.8420'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-11-16T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'npj Systems Biology and Applications'
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
url_pdf: https://pubmed.ncbi.nlm.nih.gov/31814158/
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

Survival regression is commonly applied in biomedical studies or clinical trials, and evaluating their predictive performance plays an essential role for model diagnosis and selection. The presence of censored data, particularly if informative, may pose more challenges for the assessment of predictive accuracy. Existing literature mainly focuses on prediction for survival probabilities with limitation work for survival time. In this work, we focus on accuracy measures of predicted survival times adjusted for a potentially informative censoring mechanism (ie, coarsening at random (CAR); non-CAR) by adopting the technique of inverse probability of censoring weighting. Our proposed predictive metric can be adaptive to various survival regression frameworks including but not limited to accelerated failure time models and proportional hazards models. Moreover, we provide the asymptotic properties of the inverse probability of censoring weighting estimators under CAR. We consider the settings of high-dimensional data under CAR or non-CAR for extensions. The performance of the proposed method is evaluated through extensive simulation studies and analysis of real data from the Critical Assessment of Microarray Data Analysis.

**Keywords:** informative censoring; predictive accuracy; sensitivity analysis; survival regression.
