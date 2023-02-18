---
title: "Safe learning-based gradient-free model predictive control based on cross-entropy method"
authors:
- Lei Zheng
- Rui Yang
- Wu, Zhixuan
- Jiesen Pan
- Cheng Hui
# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'


date: "2022-04"
doi: "10.1016/j.engappai.2022.104731"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-02-04T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Engineering Applications of Artificial Intelligence*
publication_short: In *EAAI*

abstract: In this paper, a safe and learning-based control framework for model predictive control (MPC) is proposed to optimize nonlinear systems with a non-differentiable objective function under uncertain environmental disturbances. The control framework integrates a learning-based MPC with an auxiliary controller in a way of minimal intervention. The learning-based MPC augments the prior nominal model with incremental Gaussian Processes to learn the uncertain disturbances. The cross-entropy method (CEM) is utilized as the sampling-based optimizer for the MPC with a non-differentiable objective function. A minimal intervention controller is devised with a control Lyapunov function and a control barrier function to guide the sampling process and endow the system with high probabilistic safety. The proposed algorithm shows a safe and adaptive control performance on a simulated quadrotor in the tasks of trajectory tracking and obstacle avoidance under uncertain wind disturbances.

# # Summary. An optional shortened abstract.
summary: A safe and learning-based control framework for model predictive control is proposed to optimize nonlinear systems with a non-differentiable objective function under uncertain environmental disturbances. The control framework integrates a learning-based MPC with an auxiliary controller in a way of minimal intervention. The proposed approach provides a promising solution to the propagation of stochastic state distributions in MPC, allowing for improved task performance while ensuring high levels of safety.
tags:
- academia
- robotics
- learning
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://www.sciencedirect.com/science/article/abs/pii/S0952197622000409?via%3Dihub
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

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
