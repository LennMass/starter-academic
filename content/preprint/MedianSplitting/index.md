---
title: "Median-based Splitting Rules for Causal Trees and Forests"
authors:
- admin
- Karolina Gliszczyńska-Schroeder 
date: "2025-04-19T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "Submitted (under review)"
publication_short: "Submitted (under review)"

abstract: "Heavy-tailed and skewed outcomes are common in the randomized experiments and observational studies used to estimate heterogeneous treatment effects, yet the mean-squared-error criterion that guides splitting in honest causal trees is sensitive to the extreme values they generate. Building on the causal forest framework (Athey and Imbens, 2016; Wager and Athey, 2018), we introduce the Median Squared Deviation (MSD) criterion, which replaces the leafwise difference in means in the honest splitting objective with the Hodges–Lehmann location estimator while leaving honest leaf estimation and forest inference unchanged. Two further median-based rules, the Median Absolute Deviation (MAD) and the Least Median of Squares (LMS), serve as robust baselines. We evaluate the criteria in a simulation study covering precision, bias, and confidence interval coverage. MSD restricts its robustness to split selection and lowers the error of conditional average treatment effect estimates under heavy-tailed and skewed outcomes. Further, we re-visit two empirical applications: the first analyzes the electoral effects of a Mexican conditional cash transfer program on precinct-level observations, while the second application studies antiretroviral treatments in HIV-positive adults."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
# - Large Language Models

featured: true

#links:
#- name: Custom Link
#  url: http://example.org
url_pdf: ""
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
