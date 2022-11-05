---
title: "Learning-Based Predictive Path Following Control for Nonlinear Systems Under Uncertain Disturbances"
authors:
- Rui Yang
- Lei Zheng
- Jiesen Pan
- Hui Cheng
# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'


date: "2021-04-01T00:00:00Z"
doi: "10.1109/lra.2021.3062805"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-04-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Robotics and Automation Letters*
publication_short: In *IEEE RAL (Presentation at IEEE ICRA 2021)* 

abstract: Accurate path following is challenging for autonomous robots operating in uncertain environments. Adaptive and predictive control strategies are crucial for a nonlinear robotic system to achieve high-performance path following control. In this letter, we propose a novel learning-based predictive control scheme that couples a high-level model predictive path following controller (MPFC) with a low-level learning-based feedback linearization controller (LB-FBLC) for nonlinear systems under uncertain disturbances. The low-level LB-FBLC utilizes Gaussian Processes to learn the uncertain environmental disturbances online and tracks the reference state accurately with a probabilistic stability guarantee. Meanwhile, the high-level MPFC exploits the linearized system model augmented with a virtual linear path dynamics model to optimize the evolution of path reference targets, and provides the reference states and controls for the low-level LB-FBLC. Simulation results illustrate the effectiveness of the proposed control strategy on a quadrotor path following task under unknown wind disturbances.

# Summary. An optional shortened abstract.
summary: A learning-based MPFC control paradigm for nonlinear systems under uncertain disturbances, coupling a high-level model predictive path following controller for proactivity with a low-level learning-based feedback linearization controller for adaptivity. Following that, nonlinear systems can rapidly rejoin their reference trajectory after sudden wind disturbances with stability guarantees.

tags:
- academia
- robotics
- learning
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: http://dx.doi.org/10.1109/lra.2021.3062805
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
