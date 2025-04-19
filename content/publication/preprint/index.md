---
title: "Estimating PATE under positivity violations:
SBART+SPL for high-dimensional covariates"
authors:
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

abstract: The positivity assumption is a fundamental requirement for causal inference in
the potential outcomes framework, ensuring that all individuals have a positive prob-
ability of receiving each treatment option. However, real-world datasets often violate
this assumption, particularly in regions of non-overlap where one treatment group
is underrepresented or entirely absent for certain combinations of confounding vari-
ables. Traditional approaches, such as trimming and weighting, address these viola-
tions but typically modify the target population, potentially introducing bias. The
Bayesian Additive Regression Trees with Spline Models (BART+SPL) approach has
been proposed as a solution to this issue. BART+SPL combines Bayesian Addi-
tive Regression Trees (BART) for imputation in regions of treatment overlap with
spline models (SPL) for extrapolation into non-overlap regions, preserving the ini-
tial target population. However, BART+SPL’s performance is compromised when
dealing with high-dimensional covariates. To address this limitation, this paper pro-
poses SBART+SPL, an extension of the BART+SPL framework that integrates Soft-
BART into the estimation procedure. SoftBART generalizes BART by implement-
ing smooth decision rules and sparsity-inducing splitting probabilities. A simulation
study demonstrates that SBART+SPL yields better precision and improved cover-
age compared to BART+SPL when estimating population average treatment effects
(PATE) in the presence of high-dimensional covariates and violations of the posi-
tivity assumption. Additionally, the applicability of SBART+SPL is illustrated by
re-analyzing an empirical study that evaluates the impact of exposure to natural gas
compressor stations on cancer mortality rates across U.S. counties.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
# - Large Language Models

featured: true

links:
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

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

# This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

# {{% callout note %}}
# Create your slides in Markdown - click the *Slides* button to check out the example.
# {{% /callout %}}

# Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
