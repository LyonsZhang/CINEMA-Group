---
title: 'Piecewise Negative Binomial Regression in Analyzing Hypoglycemic Events with Missing Observations'
authors:
  - Ming Wang
  - Junxiang Luo
  - Haoda Fu
  - Yongming Qu
date: '2014-09-13T00:00:00Z'
doi: '10.472/2155-6180.1000195'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-11-16T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'Journal of Biometrics & Biostatistics'
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
url_pdf: https://www.hilarispublisher.com/open-access/piecewise-negative-binomial-regression-in-analyzing-hypoglycemic-events-with-missing-observations-2155-6180.1000195.pdf
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

**Abstract**

In diabetes clinical trials, hypoglycemia can be captured. Negative binomial regression is emerging as a standard method for analyzing hypoglycemic events by considering overdispersion. However, in negative binomial regression for hypoglycemic events, variability of the subjects lost to follow up due to dropout is adjusted through an offset parameter, which assumes that dropout is missing completely at random and constant hypoglycemia rate over time. This assumption is vulnerable because dropout may be due to the excessive observed hypoglycemic events and the hypoglycemic event rate may change over time. In addition, the traditional way of using negative binomial regression to analyze hypoglycemic events only compares the counts of hypoglycemic events during a specified period. However, researchers may be interested in comparing hypoglycemic event rates between treatment groups at different time periods to understand the trend over time. Fitting a negative binomial model for each time period ignoring data from other periods may decrease testing power and introduce bias if the assumption of missing completely at random does not hold. We propose piecewise negative binomial regression to incorporate multiple time periods in one model through a generalized linear mixed-effect model. Due to clinical interest, we considered multiple weighting methods to estimate the overall relative rate of hypoglycemia over multiple periods between treatments. Simulations showed that piecewise negative binomial regression performed better than the traditional negative binomial regression in preserving Type I error. As an illustration, piecewise negative binomial regression was implemented in analyzing real data from a Type 2 diabetes clinical trial.
