---
title: 'High Dimensional Classification for Spatially Dependent Data with Application to Neuroimaging'
authors:
  - Yingjie Li
  - Liangliang Zhang
  - Tapabrata Maiti 
date: '2020-09-13T00:00:00Z'
doi: '10.1214/20-EJS1743'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-11-16T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'Electronic Journal of Statistics'
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
url_pdf: https://projecteuclid.org/journalArticle/Download?urlId=10.1214%2F20-EJS1743
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

Discriminating patients with Alzheimer’s disease (AD) from healthy subjects is a crucial task in the research of Alzheimer’s disease. The task can be potentially achieved by linear discriminant analysis (LDA), which is one of the most classical and popular classification techniques. However, the classification problem becomes challenging for LDA because of the high-dimensionality and the spatial dependency of the brain imaging data. To address the challenges, researchers have proposed various ways to generalize LDA into high-dimensional context in recent years. However, these existing methods did not reach any consensus on how to incorporate spatially dependent structure. In light of the current needs and limitations, we propose a new classification method, named as Penalized Maximum Likelihood Estimation LDA (PMLE-LDA). The proposed method uses *Matérn* covariance function to describe the spatial correlation of brain regions. Additionally, PMLE is designed to model the sparsity of high-dimensional features. The spatial location information is used to address the singularity of the covariance. Tapering technique is introduced to reduce computational burden. We show in theory that the proposed method can not only provide consistent results of parameter estimation and feature selection, but also generate an asymptotically optimal classifier driven by high dimensional data with specific spatially dependent structure. Finally, the method is validated through simulations and an application into ADNI data for classifying Alzheimer’s patients.



