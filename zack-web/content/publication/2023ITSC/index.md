---
title: "Real-Time Parallel Trajectory Optimization with Spatiotemporal Safety
Constraints for Autonomous Driving in Congested Traffic"
authors:
- Lei Zheng
- Rui Yang
- Zengqi Peng
- Haichao Liu
- Michael Yu Wang
- Jun Ma
# Author notes (optional)
author_notes:
  - 'Equal contribution'
  
date: "2023-09"
doi: "10.1109/itsc57777.2023.10422203"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-24T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Intelligent Transportation Systems*
publication_short: In *ITSC*

abstract: In dense traffic scenarios, ensuring safety while keeping high task performance for autonomous driving is a critical challenge. To address this problem, this paper proposes a computationally-efficient spatiotemporal receding horizon control (ST-RHC) scheme to generate a safe, dynamically feasible, energy-efficient trajectory in control space, where different driving tasks in dense traffic can be achieved with high accuracy and safety in real time. In particular, an embodied spatiotemporal safety barrier module considering proactive interactions is devised to mitigate the effects of inaccuracies resulting from the trajectory prediction of other vehicles. Subsequently, the motion planning and control problem is formulated as a constrained nonlinear optimization problem, which favorably facilitates the effective use of off-the-shelf optimization solvers in conjunction with multiple shooting. The effectiveness of the proposed ST-RHC scheme is demonstrated through comprehensive comparisons with state-of-the-art algorithms on synthetic and real-world traffic datasets under dense traffic, and the attendant outcome of superior performance in terms of accuracy, efficiency and safety is achieved.

# # Summary. An optional shortened abstract.
summary: Present an integrated decision and trajectory planning approach for the autonomous vehicles to achieve high travel efficiency in dynamic and congested environments.
tags:
- academia
- robotics
- learning
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/document/10422203
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
url_video: 'https://www.youtube.com/watch?v=86oQ83jVPYg'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
# slides: example
---

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo academia's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
