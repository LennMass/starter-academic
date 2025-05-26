---
title: "Shrinkage Bayesian Causal Forest with Instrumental Variable"
authors:
- Jens Klenke
- admin
date: "2025-04-19T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "This paper proposes a novel framework for estimating heterogeneous treatment effects using Instrumental Variables (IV) in observational studies with sparse data and imperfect compliance. To address these limitations, we build upon the Bayesian Instrumental Variable Causal Forest (BCF-IV) framework that has been developed to estimate the conditional Complier Average Causal Effect (CACE) non-parametrically while retaining interpretability. BCF-IV uses Bayesian Additive Regression Trees (BART) to identify treatment effect heterogeneity and to estimate the conditional CACE based on the conditional Intention-To-Treat (ITT) effects and the proportion of compliers. Our approach extends BCF-IV by proposing a Shrinkage Bayesian Instrumental Variable Causal Forest (SBCF-IV) algorithm. SBCF-IV adopts the SoftBART algorithm and makes two major contributions. First, SBCF-IV implicitly discriminates between relevant and irrelevant covariates when estimating conditional ITT effects and proportions of compliers. Secondly, our approach implements varying posterior splitting probabilities from SoftBART into the discovery of heterogeneous subgroups. These modifications enhance SBCF-IV's ability to handle sparse data and to detect variables that drive the heterogeneity of treatment effects. A simulation study suggests that a more precise estimation of conditional CACE can be achieved while maintaining interpretability, particularly in scenarios with sparsity, confounding, and nonlinearity. In an empirical application, we revisit the Oregon Health Insurance Experiment to demonstrate the use of SBCF-IV in comparison to BCF-IV and discuss the differences in the estimates for the conditional CACE."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
# - Large Language Models

featured: true

#links:
#- name: Custom Link
#  url: http://example.org
#url_pdf: http://arxiv.org/pdf/1512.04133v1
#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'
share: false # Show social sharing links?

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
   caption: ''
   focal_point: ""
   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---




