---
title: Online Optimization of Dynamical Systems with Deep Learning Perception
summary: This paper considers the problem of regulating a nonlinear dynamical system whose state cannot be directly measured. Leveraging neural networks to approximate system states, we demonstrate input to state stability of the closed-loop of the dynamical system and our data-driven controller.
# This paper considers the problem of controlling a dynamical system when the state cannot be directly measured and the control performance metrics are unknown or partially known. In particular, we focus on the design of data-driven controllers to regulate a dynamical system to the solution of a constrained convex optimization problem where i) the state must be estimated from nonlinear and possibly high-dimensional data; and, ii) the cost of the optimization problem -- which models control objectives associated with inputs and states of the system -- is not available and must be learned from data. We propose a data-driven feedback controller that is based on adaptations of a projected gradient-flow method; the controller includes neural networks as integral components for the estimation of the unknown functions. Leveraging stability theory for perturbed systems, we derive sufficient conditions to guarantee exponential input-to-state stability (ISS) of the control loop. In particular, we show that the interconnected system is ISS with respect to the approximation errors of the neural network and unknown disturbances affecting the system. The transient bounds combine the universal approximation property of deep neural networks with the ISS characterization. Illustrative numerical results are presented in the context of control of robotics and epidemics. 
# {{< icon name="download" pack="fas" >}} Download the {{< staticref "uploads/ArXiv_LC_OJCS_MLwC.pdf" "newtab" >}}arXiv eprint{{< /staticref >}}.
# This is an extended version of the paper accepted for publication to the IEEE Open Journal of Control Systems - Special Section on Machine Learning with Control, containing proofs.
# Subjects:	Optimization and Control (math.OC); Systems and Control (eess.SY)
# Cite as:	arXiv:2205.09574 [math.OC]
# 	(or arXiv:2205.09574v2 [math.OC] for this version)
 
# https://doi.org/10.48550/arXiv.2205.09574
# Focus to learn more

tags:
- Optimization
- Gradient Methods
- Neural Networks
- Regulation
- Perception-based control
date: "2021-01-01"

# Optional external URL for project (replaces project detail page).
# external_link: "https://proceedings.mlr.press/v168/"

image:
  caption: Simulations for perception-based control of robotics.
  focal_point: Smart

links:
- icon: ai-arxiv
  icon_pack: ai
  name: arXiv
  url: https://arxiv.org/abs/2205.09574
# url_code: ""
# url_pdf: ""
# url_slides: ""
# url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: ""
---
This paper considers the problem of controlling a dynamical system when the state cannot be directly measured and the control performance metrics are unknown or partially known. In particular, we focus on the design of data-driven controllers to regulate a dynamical system to the solution of a constrained convex optimization problem where i) the state must be estimated from nonlinear and possibly high-dimensional data; and, ii) the cost of the optimization problem -- which models control objectives associated with inputs and states of the system -- is not available and must be learned from data. We propose a data-driven feedback controller that is based on adaptations of a projected gradient-flow method; the controller includes neural networks as integral components for the estimation of the unknown functions. Leveraging stability theory for perturbed systems, we derive sufficient conditions to guarantee exponential input-to-state stability (ISS) of the control loop. In particular, we show that the interconnected system is ISS with respect to the approximation errors of the neural network and unknown disturbances affecting the system. The transient bounds combine the universal approximation property of deep neural networks with the ISS characterization. Illustrative numerical results are presented in the context of control of robotics and epidemics. This paper was accepted for publication to the IEEE Open Journal of Control Systems - Special Section on Machine Learning with Control, 2022.
