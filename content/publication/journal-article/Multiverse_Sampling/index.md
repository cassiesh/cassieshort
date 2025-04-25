---
title: "Lost in a Large EEG Multiverse? Comparing Sampling Approaches for Representative Pipeline Selection (preprint)."
authors:
- "Cassie Ann Short"
- "Andrea Hildebrandt"
- "Robin Bosse"
- "Stefan Debener"
- "Metin Oezyagcilar"
- "Katharina Paul"
- "Jan Wacker"
- "Daniel Kristanto"

# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2025-04-15"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*bioRxiv*"
# publication_short: ""

abstract: The multiplicity of defensible strategies for processing and analysing data has been implicated as a core contributor to the replicability crisis, creating uncertainty about the robustness of a result to variations in data processing choices. This issue is exacerbated where a large number of data processing pipelines are defensible, and where there is great heterogeneity in the pipelines applied in the literature, such as in processing and analysing electroencephalography (EEG) signals. In a multiverse analysis, equally defensible pipelines are computed and the robustness of the result to these variations is reported. However, a large number of defensible pipelines is sometimes infeasible to compute exhaustively, and researchers rely on sampling approaches. In these cases, pipelines are sampled from the full multiverse and the robustness is reported across these samples, assuming that they are representative for the entire multiverse. However, different sampling methods may yield different robustness results, introducing what we term multiverse sampling uncertainty. To illustrate, we computed a 528-pipeline multiverse analysis on EEG-recordings during an emotion classification task aiming to predict extraversion scores from the Late Positive Potential. We applied three sampling methods (random, stratified, and active learning) to sample 26 pipelines (5%), and evaluated the results in terms of the representativeness of the distribution of model fits to that of the full multiverse. Our results highlight variability in the representativeness of the distribution of model fits between samples. The active learning sample most closely represented the median model fit of the full multiverse. The need for representative pipeline sampling to mitigate bias in large multiverse analyses is discussed. 

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Multiverse Analysis
- Multiverse Sampling Uncertainty
- EEG Individual Differences
- Active Learning
- Machine Learning
- Open Source Tool
featured: false

# links:
# - name: ""
#   url: ""
# url_pdf: http://arxiv.org/pdf/1512.04133v1
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#  focal_point: ""
#  preview_only: false

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
# slides: example
---

# {{% callout note %}}
# Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
# {{% /callout %}}

# {{% callout note %}}
# Create your slides in Markdown - click the *Slides* button to check out the example.
# {{% /callout %}}

# Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/# writing-markdown-latex/).
