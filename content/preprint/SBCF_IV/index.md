---
title: "Shrinkage Bayesian Causal Forest with Instrumental Variable"
authors:
- admin
- Jens Klenke
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

abstract: "We propose Shrinkage Bayesian Causal Forest with Instrumental Variable (SBCF-IV), a method for discovering and estimating subgroups with heterogeneous Complier Average Causal Effects (CACE) in sparse high-dimensional settings with imperfect compliance. SBCF-IV places a sparsity-inducing Dirichlet prior on splitting probabilities within Bayesian Additive Regression Trees used to estimate the conditional intention-to-treat and the complier share, concentrating posterior mass on the few covariates that genuinely moderate the complier effect. The resulting split frequencies then enter a downstream CART as variable-level costs, directing it toward the relevant moderator variables and yielding an interpretable partition of the covariate space. The Bayesian feature-selection mechanism thus regularizes effect estimation and simultaneously steers subgroup discovery. Monte Carlo experiments show that, as the share of irrelevant covariates grows, SBCF-IV recovers the true partition more reliably than BCF-IV at both the tree and unit level, and retains nominal coverage in regimes where BCF-IV's intervals deteriorate. We apply the method to the Oregon Health Insurance Experiment and the 401(k) eligibility data."

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
