---
title: "Safe Learning-Based Feedback Linearization Tracking Control for Nonlinear System with Event-Triggered Model Update"
authors:
  - Wu, Zhixuan
  - Rui Yang
  - Lei Zheng
  - Cheng Hui
# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: "2022-04-08T00:00:00Z"
doi: "10.1109/LRA.2022.3146930"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-04-08T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Robotics and Automation Letters*
publication_short: In *IEEE RAL (Presentation at IEEE ICRA 2022)*

abstract: Learning-based methods are powerful in handling complex scenarios. However, it is still challenging to use learning-based methods under uncertain environments while stability, safety, and real-time performance of the system are desired to guarantee. In this letter, we propose a learning-based tracking control scheme based on a feedback linearization controller in which uncertain disturbances are approximated online using Gaussian Processes (GPs). Using the predicted distribution of disturbances given by GPs, a Control Lyapunov Function (CLF) and Control Barrier Function (CBF) based Quadratic Program is applied, with which probabilistic stability and safety are guaranteed. In addition, the trajectory is optimized first by Model Predictive Control (MPC) based on the linearized dynamics systems to further reduce the tracking error. We also design an event trigger for GPs updates to improve efficiency while stability and safety of the system are still guaranteed. The effectiveness of the proposed tracking control strategy is illustrated in numerical simulations.

# Summary. An optional shortened abstract.
summary: We propose a learning-based tracking control scheme based on a feedback linearization controller in which uncertain disturbances are approximated online using Gaussian Processes. Using the predicted distribution of disturbances given by GPs, a Control Lyapunov Function and Control Barrier Function based Quadratic Program is applied, with which probabilistic stability and safety are guaranteed.

tags:
- academia
- robotics
- learning
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/document/9697413
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
