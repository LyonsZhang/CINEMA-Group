---
title: 'ProgPerm: Progressive permutation for a dynamic representation of the robustness of microbiome discoveries'
authors:
  - Liangliang Zhang
  - Yushu Shi
  - Kim-Anh Do
  - Robert R. Jenq
  - Christine B. Peterson
date: '2021-09-13T00:00:00Z'
doi: 'https://doi.org/10.1186/s12859-021-04061-3'

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
url_pdf: https://bmcbioinformatics.biomedcentral.com/counter/pdf/10.1186/s12859-021-04061-3.pdf
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

**Background:** Identification of features is a critical task in microbiome studies that is complicated by the fact that microbial data are high dimensional and heterogeneous. Masked by the complexity of the data, the problem of separating signals (differential features between groups) from noise (features that are not differential between groups) becomes challenging and troublesome. For instance, when performing differential abundance tests, multiple testing adjustments tend to be overconservative, as the probability of a type I error (false positive) increases dramatically with the large numbers of hypotheses. Moreover, the grouping effect of interest can be obscured by heterogeneity. These factors can incorrectly lead to the conclusion that there are no differences in the microbiome compositions.

**Results:** We translate and represent the problem of identifying differential features, which are differential in two-group comparisons (e.g., treatment versus control), as a dynamic layout of separating the signal from its random background. More specifically, we progressively permute the grouping factor labels of the microbiome samples and perform multiple differential abundance tests in each scenario. We then compare the signal strength of the most differential features from the original data with their performance in permutations, and will observe a visually apparent decreasing trend if these features are true positives identified from the data. Simulations and applications on real data show that the proposed method creates a U-curve when plotting the number of significant features versus the proportion of mixing. The shape of the U-Curve can convey the strength of the overall association between the microbiome and the grouping factor. We also define a fragility index to measure the robustness of the discoveries. Finally, we recommend the identified features by comparing p-values in the observed data with p-values in the fully mixed data.

**Conclusions:** We have developed this into a user-friendly and efficient R-shiny tool with visualizations. By default, we use the Wilcoxon rank sum test to compute the p-values, since it is a robust nonparametric test. Our proposed method can also utilize p-values obtained from other testing methods, such as DESeq. This demonstrates the potential of the progressive permutation method to be extended to new settings.

**Keywords:** Differential test; Feature selection; Fragility index; Microbiome; Permutation; Robustness.



