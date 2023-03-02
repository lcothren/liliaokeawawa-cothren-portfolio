---
title: Online Optimization of Linear Time Invariant Dynamical Systems with Cost Perception
summary: This paper considers the problem of regulating a discrete-time linear time-invariant (LTI) system to solution trajectories of a convex optimization problem, with an unknown cost. We propose a data-driven, gradient-based feedback controller that uses estimates of the cost functions obtained by a trained neural network to control the LTI system. We identify sufficient conditions to guarantee exponential input-to-state stability (ISS) of the closed loop system with respect to errors due to disturbances, temporal variability of the cost functions, and the need to use estimated costs from a neural network. Finally, we provide an illustrative numerical example in the context of online ride-share scheduling.
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
  caption: States of the ride-share scheduling problem using an estimated gradient obtained via a feedforward neural network.  
  focal_point: Smart

links:
- icon: ai-arxiv
  icon_pack: ai
  name: Conference Proceedings
  url: [https://www.asilomarsscconf.org/PastConferences.html]
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
This paper considers the problem of regulating a discrete-time linear time-invariant (LTI) system to solution trajectories of a convex optimization problem, with an unknown cost. We propose a data-driven, gradient-based feedback controller that uses estimates of the cost functions obtained by a trained neural network to control the LTI system. We identify sufficient conditions to guarantee exponential input-to-state stability (ISS) of the closed loop system with respect to errors due to disturbances, temporal variability of the cost functions, and the need to use estimated costs from a neural network. Finally, we provide an illustrative numerical example in the context of online ride-share scheduling.
