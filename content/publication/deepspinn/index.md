---
title: "DeepSPInN – deep reinforcement learning for molecular structure prediction from infrared and 13C NMR spectra"
authors:
- admin
- Bhuvanesh Sridharan
- Sarvesh Mehta
- Yashaswi Pathak
- Siddhartha Laghuvarapu
- Girish Varma
- U. Deva Priyakumar
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
date: "2024-03-07T00:00:00Z"
doi: "10.1039/D4DD00008K"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Digital Discovery"
publication_short: ""

abstract: Molecular spectroscopy studies the interaction of molecules with electromagnetic radiation, and interpreting the resultant spectra is invaluable for deducing the molecular structures. However, predicting the molecular structure from spectroscopic data is a strenuous task that requires highly specific domain knowledge. DeepSPInN is a deep reinforcement learning method that predicts the molecular structure when given infrared and 13C nuclear magnetic resonance spectra by formulating the molecular structure prediction problem as a Markov decision process (MDP) and employs Monte-Carlo tree search to explore and choose the actions in the formulated MDP. On the QM9 dataset, DeepSPInN is able to predict the correct molecular structure for 91.5% of the input spectra in an average time of 77 seconds for molecules with less than 10 heavy atoms. This study is the first of its kind that uses only infrared and 13C nuclear magnetic resonance spectra for molecular structure prediction without referring to any pre-existing spectral databases or molecular fragment knowledge bases, and is a leap forward in automated molecular spectral analysis.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- ML for Chemistry
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://pubs.rsc.org/en/content/articlepdf/2024/dd/d4dd00008k
url_code: 'https://github.com/devalab/deepspinn'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Table of Contents image of DeepSPInN'
  focal_point: ""
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
slides: ""
---


