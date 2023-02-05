---
title: 'Inference for marginal linear models for clustered longitudinal data with potentially informative cluster sizes'
authors:
  - Ming Wang
  - Maiying Kong
  - Somnath Datta
date: '2011-09-13T00:00:00Z'
doi: 'https://doi.org/10.1177/0962280209347043'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-11-16T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'Statistical Methods in Medical Research'
publication_short: 'Stat Methods Med Res'

abstract: 

# Summary. An optional shortened abstract.
summary: 
tags:
  - Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://journals.sagepub.com/doi/10.1177/0962280209347043?url_ver=Z39.88-2003&rfr_id=ori:rid:crossref.org&rfr_dat=cr_pub%20%200pubmed
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

Clustered longitudinal data are often collected as repeated measures on subjects arising in clusters. Examples include periodontal disease study, where the measurements related to the disease status of each tooth are collected over time for each patient, which can be considered as a cluster. For such applications, the number of teeth for each patient may be related to the overall oral health of the individual and hence may influence the distribution of the outcome measure of interest leading to an informative cluster size. Under such situations, generalised estimating equations (GEE) may lead to invalid inferences. In this article, we investigate the performance of three competing proposals of fitting marginal linear models to clustered longitudinal data, namely, GEE, within-cluster resampling (WCR) and cluster-weighted generalised estimating equations (CWGEE). We show by simulations and theoretical calculations that, when the cluster size is informative, GEE provides biased estimators, while both WCR and CWGEE achieve unbiasedness under a variety of 'working' correlation structures for temporal measurements within each subject. Statistical properties of confidence intervals have been investigated using the probability-probability plots. Overall, CWGEE appears to be the recommended choice for marginal parametric inference with clustered longitudinal data that achieves similar parameter estimates and test statistics as WCR while avoiding Monte Carlo computation. The corresponding Wald tests have desirable power properties as well. We illustrate our analysis using a temporal data set on periodontal disease, which clearly demonstrates the need for CWGEE over GEE.
