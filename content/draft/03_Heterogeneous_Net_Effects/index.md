---
title: "A super learner for heterogeneous net average treatment effects"
authors:
- admin
- Eva-Maria Oeß
date: "2025-04-02T00:00:00Z"
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

abstract: "We introduce a super learner for estimating heterogeneous net treatment effects under unit-varying outcome and cost effects. Our approach is designed for optimal assignment of a binary treatment that induces a cost–benefit trade-off. The net effect and its underlying outcome and cost components are characterized by unknown functional complexity, which our ensemble explores in a data-driven manner. Directly targeting the net effect performs well when the estimand is simpler than the outcome and cost effects individually. In contrast, separately learning both effects and subsequently aggregating them into the net effect is advantageous when the underlying components share similar functional complexity that translates into a similarly complex target estimand. A hybrid learning strategy succeeds in intermediate settings. Our ensemble nests all approaches and selects the winner by minimizing empirical risk. In a simulation study, we consider multiple scenarios in which each individual approach dominates the others and show that the ensemble further improves precision across most settings. We additionally present an empirical application using data from a large nonprofit organization, where we analyze the net effect of a fundraising campaign aimed at increasing pledge payments while mitigating donor attrition."

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




