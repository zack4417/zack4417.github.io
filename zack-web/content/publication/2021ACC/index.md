---
title: "Safe learning-based tracking control for quadrotors under wind disturbances"
authors:
- Lei Zheng
- Rui Yang
- Jiesen Pan
- Cheng Hui
# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'


date: "2021-05-25T00:00:00Z"
doi: "10.23919/acc50511.2021.9482929"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-05-25T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *American Control Conference*
publication_short: In *ACC*

abstract: Enforcing safety on precise trajectory tracking is critical for aerial robotics subject to wind disturbances. In this paper, we present a learning-based safety-preserving cascaded quadratic programming control (SPQC) for safe trajectory tracking under wind disturbances. The SPQC controller consists of a position-level controller and an attitude-level controller. Gaussian Processes (GPs) are utilized to estimate the uncertainties caused by wind disturbances, and then a nominal Lyapunov-based cascaded quadratic program (QP) controller is designed to track the reference trajectory. To avoid unexpected obstacles when tracking, safety constraints represented by control barrier functions (CBFs) are enforced on each nominal QP controller in a way of minimal modification. The performance of the proposed SPQC controller is illustrated through numerical validations of (a) trajectory tracking under different wind disturbances, and (b) trajectory tracking in a cluttered environment with a dense time-varying obstacle field under wind disturbances.

# Summary. An optional shortened abstract.
summary: Enforcing safety on precise trajectory tracking is critical for aerial robotics subject to wind disturbances. In this paper, we present a learning-based safety-preserving cascaded quadratic programming control for safe trajectory tracking under wind disturbances. 
tags:
- Source Themes
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://ieeexplore.ieee.org/document/9482929
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
url_video: 'https://www.youtube.com/watch?v=p-K3v9Z4OvA&t=2s'

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

