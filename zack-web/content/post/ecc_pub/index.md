---
title: 'March 2024: New conference article of the European Control Conference.'
subtitle: 'Incremental Bayesian Learning for Fail-Operational Control in Autonomous Driving'
summary: Present a real-time fail-operational controller for autonomous driving in the presence of time-varying environmental disturbances. This controller is designed to guide autonomous vehicles back to a predefined safe state asymptotically, while upholding task efficiency.
authors:
- Lei Zheng
- Rui Yang
- Zengqi Peng
- Wei Yan
- Michael Yu Wang
- Jun Ma
tags:
- academia
categories: []
date: "2024-03-01T00:00:00Z"
lastmod: ""
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []

# Set captions for image gallery.
gallery_item:
- album: gallery
  caption: Default
  image:
---

**Abrupt maneuvers by surrounding vehicles (SVs) can typically lead to safety concerns and affect the task efficiency of the ego vehicle (EV), especially with model uncertainties stemming from environmental disturbances. This paper presents a real-time fail-operational controller that ensures the asymptotic convergence of an uncertain EV to a safe state, while preserving task efficiency in dynamic environments. An incremental Bayesian learning approach is developed to facilitate online learning and inference of changing environmental disturbances. Leveraging disturbance quantification and constraint transformation, we develop a stochastic fail-operational barrier based on the control barrier function. With this development, the uncertain EV is able to converge asymptotically from an unsafe state to a defined safe state with probabilistic stability. Subsequently, the stochastic fail-operational barrier is integrated into an efficient fail-operational controller based on quadratic programming. This controller is tailored for the EV operating under control constraints in the presence of environmental disturbances, with both safety and efficiency objectives taken into consideration.**