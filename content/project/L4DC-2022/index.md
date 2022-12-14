---
title: Data-enabled Gradient Flow as Feedback Controller - Regulation of Linear Dynamical Systems to Minimizers of Unknown Functions
summary: This paper considers the problem of regulating a linear dynamical system subject to external disturbances to the solution of a convex optimization problem with an unknown or partially-known cost. Our results demonstrate exponential input-to-state stability of the closed-loop system with our gradient-flow based controller. 
# This paper considers the problem of regulating a linear dynamical system to the solution of a convex optimization problem with an unknown or partially-known cost. We design a data-driven feedback controller - based on gradient flow dynamics - that (i) is augmented with learning methods to estimate the cost function based on infrequent (and possibly noisy) functional evaluations; and, concurrently, (ii) is designed to drive the inputs and outputs of the dynamical system to the optimizer of the problem. We derive sufficient conditions on the learning error and the controller gain to ensure that the error between the optimizer of the problem and the state of the closed-loop system is ultimately bounded; the error bound accounts for the functional estimation errors and the temporal variability of the unknown disturbance affecting the linear dynamical system. Our results directly lead to exponential input-to-state stability of the closed-loop system. The proposed method and the theoretical bounds are validated numerically. 
# {{< icon name="download" pack="fas" >}} Download the {{< staticref "uploads/arXivPaperL4DC.pdf" "newtab" >}}arXiv eprint{{< /staticref >}}.
# This is an extended version of the paper accepted for publication to the 4th Annual Learning for Dynamics and Control Conference containing proofs.
tags:
- Optimization
- Learning-Based Control
- Learning-Based Optimization
- Gradient Flow
- Regulation
date: "2021-12-03T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Simulations with time-varying disturbance.
  focal_point: Smart

links:
- icon: ai-arxiv
  icon_pack: ai
  name: ArXiv
  url: https://arxiv.org/abs/2112.01652
- icon: fa-memo-circle-check
  icon_pack: fa
  name: Proceedings of Machine Learning Research
  url: https://proceedings.mlr.press/v168/
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
This paper considers the problem of regulating a linear dynamical system to the solution of a convex optimization problem with an unknown or partially-known cost. We design a data-driven feedback controller - based on gradient flow dynamics - that (i) is augmented with learning methods to estimate the cost function based on infrequent (and possibly noisy) functional evaluations; and, concurrently, (ii) is designed to drive the inputs and outputs of the dynamical system to the optimizer of the problem. We derive sufficient conditions on the learning error and the controller gain to ensure that the error between the optimizer of the problem and the state of the closed-loop system is ultimately bounded; the error bound accounts for the functional estimation errors and the temporal variability of the unknown disturbance affecting the linear dynamical system. Our results directly lead to exponential input-to-state stability of the closed-loop system. The proposed method and the theoretical bounds are validated numerically. This paper was accepted for publication to the 4th Annual Learning for Dynamics and Control Conference, 2022.
