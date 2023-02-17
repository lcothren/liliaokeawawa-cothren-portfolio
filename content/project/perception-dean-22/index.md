---
title: Perception-based Sampled-data Optimization of Dynamical Systems
summary: Motivated by perception-based control problems in  autonomous systems, this paper addresses the problem of developing feedback controllers to regulate the inputs and the states of a dynamical system to optimal solutions of an optimization problem when one has no access to exact measurements of the system states. In particular, we consider the case where the states need to be estimated from high-dimensional sensory data received only at discrete time intervals. We develop a sampled-data feedback controller that is based on adaptations of a projected gradient descent method, and that includes neural networks as integral components to estimate the state of the system from perceptual information. We derive sufficient conditions to guarantee (local) input-to-state stability of the control loop. Moreover, we show that the interconnected system tracks the solution trajectory of the underlying optimization problem up to an error that depends on the approximation errors of the neural network and on the time-variability of the optimization problem; the latter originates from time-varying safety and performance objectives, input constraints, and unknown disturbances. As a representative application, we illustrate our results with numerical simulations for vision-based autonomous driving. 
# {{< icon name="download" pack="fas" >}} Download the {{< staticref "uploads/arXivPaperL4DC.pdf" "newtab" >}}arXiv eprint{{< /staticref >}}.
# This is an extended version of the paper accepted for publication to the 4th Annual Learning for Dynamics and Control Conference containing proofs.
tags:
- Optimization
- Learning-Based Control
- Gradient Flow
- Regulation
- Perception-Based Control
date: "2021-12-03T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Sample trajectory of the vehicle tracking the check points represented by red stars. 
  focal_point: Smart

links:
- icon: ai-arxiv
  icon_pack: ai
  name: ArXiv
  url: [https://arxiv.org/abs/2211.10020]
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
Motivated by perception-based control problems in  autonomous systems, this paper addresses the problem of developing feedback controllers to regulate the inputs and the states of a dynamical system to optimal solutions of an optimization problem when one has no access to exact measurements of the system states. In particular, we consider the case where the states need to be estimated from high-dimensional sensory data received only at discrete time intervals. We develop a sampled-data feedback controller that is based on adaptations of a projected gradient descent method, and that includes neural networks as integral components to estimate the state of the system from perceptual information. We derive sufficient conditions to guarantee (local) input-to-state stability of the control loop. Moreover, we show that the interconnected system tracks the solution trajectory of the underlying optimization problem up to an error that depends on the approximation errors of the neural network and on the time-variability of the optimization problem; the latter originates from time-varying safety and performance objectives, input constraints, and unknown disturbances. As a representative application, we illustrate our results with numerical simulations for vision-based autonomous driving. This work has been submitted to IFAC 2023 for possible publication.
