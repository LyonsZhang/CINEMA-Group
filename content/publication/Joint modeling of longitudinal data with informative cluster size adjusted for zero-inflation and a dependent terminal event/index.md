---
title: 'Joint modeling of longitudinal data with informative cluster size adjusted for zero-inflation and a dependent terminal event'
authors:
  -  Biyi Shen
  -  Chixiang Chen
  -  Danping Liu
  -  Somnath Datta
  -  Nasrollah Ghahramani
  -  Vernon M Chinchilli
  -  Ming Wang
date: '2021-09-13T00:00:00Z'
doi: '10.1002/sim.9081'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-11-16T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'Statistics in Medicine'
publication_short: 'Stat Med.'

abstract: 

# Summary. An optional shortened abstract.
summary: 
tags:
  - Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.ncbi.nlm.nih.gov/pmc/articles/pmid/34057216/
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

Repeated measures are often collected in longitudinal follow-up from clinical trials and observational studies. In many situations, these measures are adherent to some specific event and are only available when it occurs; an example is serum creatinine from laboratory tests for hospitalized acute kidney injuries. The frequency of event recurrences is potentially correlated with overall health condition and hence may influence the distribution of the outcome measure of interest, leading to informative cluster size. In particular, there may be a large portion of subjects without any events, thus no longitudinal measures are available, which may be due to insusceptibility to such events or censoring before any events, and this zero-inflation nature of the data needs to be taken into account. On the other hand, there often exists a terminal event that may be correlated with the recurrent events. Previous work in this area suffered from the limitation that not all these issues were handled simultaneously. To address this deficiency, we propose a novel joint modeling approach for longitudinal data adjusting for zero-inflated and informative cluster size as well as a terminal event. A three-stage semiparametric likelihood-based approach is applied for parameter estimation and inference. Extensive simulations are conducted to evaluate the performance of our proposal. Finally, we utilize the Assessment, Serial Evaluation, and Subsequent Sequelae of Acute Kidney Injury (ASSESS-AKI) study for illustration.

**Keywords:** competing risk; informative cluster size; joint modeling; longitudinal data analysis; zero-inflation.
