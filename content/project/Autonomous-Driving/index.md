---
title: Autonomous Driving
summary: Motion Planning for self-driving vehicles.
tags:
#- System
date: "2020-12-20T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Screenshot of our motion planning algorithm (FELP) working in CARLA
  focal_point: Smart

#links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

This is an on-going research project funded by Qualcomm.
The goal of the project is advance the motion/behavior planning algorithms for self-driving vehicles.

As an initial step, we made the following assumptions to make the problem more accessible:

* The traffic is a deterministic system.
* The behavior of agent vehicles (vehicles around the self-driving/ego vehicle) are known.
  We assume agent vehicles are lane follows with acceleration modulated by an intelligent driver model.

We proposed Feedback Enhanced Lattice Planner (FELP).
The contribution of the work were:

* We used feedback, instead of open-loop, motion primitives for the ego vehicle (thus the name of the method).
  The lattice dimension to be searched is reduced, leading to a reduction in runtime complexity.
* We introduced two variants of FELP to further reduce the runtime complexity to polynomial time.
* We further proposed a directed graph map to model the structured road environment.

Below is a video highlighting FELP working with CARLA simulator.

[![Sun IROS2020](https://img.youtube.com/vi/TxMY1dvHFog/hqdefault.jpg)](https://www.youtube.com/watch?v=TxMY1dvHFog)

Related publication:
[[Sun, IROS2020]](https://arxiv.org/abs/2007.05794)
[[Code]](https://github.com/KumarRobotics/conformal_lattice_planner)

For the next step, we beg the question of modeling the stochasticity in traffic dynamics and planning motions for the ego vehicle therein.

