---
title: "Learning-Based Safety-Stability-Driven Control for Safety-Critical Systems under Model Uncertainties"
authors:
- Lei Zheng
- Rui Yang
- Jiesen Pan
- Cheng Hui
- Haifeng Hu

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'


date: "2020-12-28T00:00:00Z"
doi: "10.1109/WCSP49889.2020.9299833"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-12-28T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Wireless Communications and Signal Processing*
publication_short: In *WCSP*

abstract: Safety and tracking stability are crucial for safety-critical systems such as self-driving cars, autonomous mobile robots, and industrial manipulators. To efficiently control safety-critical systems to ensure their safety and achieve tracking stability, accurate system dynamic models are usually required. However, accurate system models are not always available in practice. In this paper, a learning-based safety-stability-driven control (LBSC) algorithm is presented to guarantee the safety and tracking stability for nonlinear safety-critical systems subject to control input constraints under model uncertainties. Gaussian Processes (GPs) are employed to learn the model error between the nominal model and the actual system dynamics, and the estimated mean and variance of the model error are used to quantify a high-confidence uncertainty bound. Using this estimated uncertainty bound, a safety barrier constraint is devised to ensure safety, and a stability constraint is developed to achieve rapid and accurate tracking. Then the proposed LBSC method is formulated as a quadratic program incorporating the safety barrier, the stability constraint, and the control constraints. The effectiveness of the LBSC method is illustrated on the safety-critical connected cruise control (CCC) system simulator under model uncertainties.

# Summary. An optional shortened abstract.
summary: A learning-based safety-stability-driven control algorithm is presented to guarantee the safety and tracking stability for nonlinear safety-critical systems subject to control input constraints under model uncertainties.
tags:
- Source Themes
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://ieeexplore.ieee.org/abstract/document/9299833
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo academia's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).

